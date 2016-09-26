#Installation
<hr>

## First Download code
Download the [Repo code here](https://github.com/Kitsui/AWS-CMS-LAMBDA)

## Set up your Environment
1. Open up your Terminal and navigate to the CMS directory's root.

2. Ensure that your AWS Terminal has already been configured with the right credentials for the Account you wish to deploy to.

##Perform setup steps

1. To deploy, run the following command in your terminal window  
**CMS-Name :** name for your CMS  
**AWS-Region :** AWS Region the CMS is be installed on.  
```Python
python setup.py CMS-Name AWS-Region
```
After the Setup script has finished its work, navigate to [Amazon Web Services](aws.amazon.com) and login to verify your installation was successful.  
You should be able to see new resources within the **S3 bucket**, **Dynamo Database**, **API gateway** and **Lambda** with the same CMS-Name suffixed to the resource name.

<br />
<hr>

#Removal
##Information
Right now the removal 

##Perform removal steps

3. To Remove, run the following command in your terminal window.

```Python
python remove.py
```
You will be prompted with a list of installed CMS with a corresponding Number, _type_ the **Number** of the CMS you wish to **Remove** and hit **Enter**.

<br />
<hr>

#Updating Lambda Package

##Information
The following instructions is for **_Deploying_** the **Lambda** package after modifying or adding functionality  
more information about developing on **Lambda** click [here](https://github.com/Kitsui/AWS-CMS-LAMBDA)

##Perform update steps

3. To Update, run the following command in your terminal window.

```Python
python update.py
```
You will be prompted with a list of installed CMS with a corresponding Number, _type_ the **Number** of the CMS you wish to **Update** and hit **Enter**.
