**Virtual Private Cloud**

**VPC Architecture**

![](RackMultipart20220827-1-ibnu65_html_67c1cdbb44063652.png)

**Step1: Create VPC**

Go to AWS management console, On the top left search for " **VPC**" in the search tab and click on **VPC - isolated cloud resources**

On the left side, click on " **your VPCs**" which is under **Virtual private cloud**

Click on " **Create VPC**" which is located at top right

Fill the details of " **VPC Settings**"

\> Select " **VPC Only**"

\> Fill the name **"My\_VPC\_123"** for " **Name tag** _ **- optional** __"_

_\>_ Select " **IPv4 CIDR manual input**" for "IPv4 CIDR block"

\> Fill " **10.0.0.0/16**" for **IPv4 CIDR**

\> Select " **No IPv6 CIDR block**" for " **IPv6 CIDR block**"

\> Select " **Default**" for " **Tenancy**"

After selecting and filling above details click on " **Create VPC**", which located at right bottom

**Step2: Create Subnet**

After creation of VPC, click on " **Subnets**" which is located under " **your VPC**" at top left

Click on " **Create Subnet**" which is located at top right

Select " **My\_VPC\_123"** for " **VPC ID**"

Under " **Subnet settings**" fill and select the following details

\> Fill " **My\_subnet\_123**" for " **subnet name"**

\> Select " **\<your current availability zone\>**" for " **Availability zone**"

\> Fill "1 **0.0.0.0/24**" for " **IPv4 CIDR block**"

After selecting and filling required details and click on " **create subnet**" which is at bottom

**Step3: Create Internet Gateways**

Click on " **Internet gateway**", which is at top left under " **route tables**"

Click on " **Create Internet gateway**", which is located at top right

Fill name "my\_internet\_gateway123" for "Name tag"

Click on " **Create Internet gateway**", which is bottom

Click on " **Actions**" which is at on top right and click on " **Attach to VPC**"

Select available VPC " **My\_VPC\_123"** for " **Available VPCs**" and click on " **Attach Internet gateway"**

**Step4: Create Route Table**

Click on " **Route tables**" which is at top left under Subnets

Click on " **Create route tables**"

Fill name " **my-route-table123**" for Name _- optional_

Select VPC " **My\_VPC\_123**" for " **VPC**"

Click on " **Create route table**", which is at bottom

**Step5: Assign Internet Gateway to Route table**

Click on " **Route Tables**" on top left

Select the created route table " **my-route-table123**"

Click on " **Routes**" which is at little bit bottom

Now click on " **Edit routes**" which is right bottom

Click on " **Add route**"

\> Fill " **0.0.0.0/0**" under " **Destination**"

\> Fill "\< **internet gateway id\>**" under " **Target"** and Click on " **Save changes**"

**Step6: Assign subnet to Route table**

Click on " **Route Tables**" on top left

Select the created route table " **my-route-table123**"

Click on " **subnet-associations**" which is at little bit bottom

Now click on " **Edit subnet associations**" which is right bottom

Select " **my\_subnet\_123**" and click on " **save associations**"
