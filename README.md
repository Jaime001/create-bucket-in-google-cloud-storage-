# How to create a bucket in google cloud storage?

Guide to create a bucket step by step in google cloud to store files

### Let’s start

Visit the webpage [google cloud](https://cloud.google.com/) and create an account. When you create the account follow the next steps.

### Step 1: Create bucket

- #### *Go to storage and click in +create bucket*

- #### Name your bucket

![image](screenshots/BucketName.png)


- #### Choose where to store your data

![image](screenshots/Data.png)

- #### Choose a default storage class for your data

![image](screenshots/StorageClass.png)

- #### Choose how to control access to objects

![image](screenshots/ChooseHow.png)

- #### Advanced settings (optional)

![image](screenshots/AdvancedSettings.png)

#### Bucket Created:

![image](screenshots/bucketCreteed.png)

### Step 2: Create the credentials

- #### Go to API's & Services

![image](screenshots/APIs.png)

- #### Next go to credentials in the left menu

![image](screenshots/credentials.png)

- #### Click on CREATE CREDENTIALS

![image](screenshots/create-credentials.png)

- #### Select Service account

![image](screenshots/service-account.png)

- #### Insert the name for the service account. The description is optional.

![image](screenshots/service-account-name.png)

- #### Select the role Owner

![image](screenshots/role-owner.png)

- #### Click on Create key. Grant users access is optional.

![image](screenshots/create-key.png)

- #### Select JSON in key type and click on create

![image](screenshots/json-option.png)

- #### The file with the credentials will be download

![image](screenshots/file-download.png)

  File downloaded
  ![image](screenshots/file.png)

- #### Finally click on Done

![image](screenshots/done.png)

**If everything is correct you can see the credential created**

![image](screenshots/service-created.png)

**Now you have to add the json file to your project**