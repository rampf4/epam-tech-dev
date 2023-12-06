
## Create account

Go to <https://aws.amazon.com/resources/create-account/> 

## Usage

Set the configuration for Elastic Beanstalk Application

```bash
eb init -p python-3.11 epam-tutorial --region us-east-1   
```

Create the resources and deploy your application 

```bash
eb create epam-env 
```

To update your current application 

```bash
eb deploy
```

To delete all the resources created
```bash
eb terminate epam-env
```



## S3

Configuring a static website on Amazon S3 <https://docs.aws.amazon.com/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html>
