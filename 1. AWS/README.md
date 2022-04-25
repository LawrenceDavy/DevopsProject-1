<strong>IAM User</strong>

<br>
<hr>

Apprently, it's not good practice to work with cloud tools using root access due to possible security concerns. Therefore, we must create an IAM user with administrative privileges to complete these tasks.

<br>
<hr>

Go the to IAM dashboard -> Users -> Set user details.
Enter a username and give programmatic access. Also create a custom password for the new user.
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-1.png">

<br>
<hr>

In the set permissions section, select Attach existing policies directly and check AdministratorAccess.
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-2.png">

<br>
<hr>

Once that is done you have the option to download the csv file that contains the new users credentials.
DO NOT lose this file, otherwise you will not be able to login into the AWS cli and you will have to ask the root user to create new credentials for you.
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-3.png">

<br>
<hr>

Before we sign in as the IAM user, we might as well add billing to the IAM user to make it more convenient to check the costs of running the servers. Go the root user account section and scroll down until you reach the IAM User and Role Access to Billing Information. Check Activate IAM Access and click update.

<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-5.png">
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-6.png">

<br>
<hr>

Go back to IAM dashboard and click on the IAM user. On the permission tab, click add permissions. Under Grant permissions, select Attach existing policies directly, then select the Billing policy.

<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-7.png">
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-8.png">
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-9.png">
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-10.png">

<br>
<hr>

Now the settings for the user is created, sign in as the IAM user as this will be what we using for the remainder of the project.
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/aws/aws-4.png">


