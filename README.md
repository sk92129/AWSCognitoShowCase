# Showcase for AWS Cognito, RESTful-Springboot integration, and Flutter app integration

The set up of AWS Cognito creates a userpool.  

![image](https://github.com/user-attachments/assets/e5adf6de-6ebb-466c-add9-74f132de356f)


Once the AWS cognito is set up, a front end application framework such as Flutter can set up their own customize UI.

Here is the sample Sign-In screen.

![image](https://github.com/user-attachments/assets/3d57ada7-0aa9-4f68-9683-554c0a411a13)


If the user does not have an account, they can click on the "Create New Account" button to sign up.

Here is a sample Sign-Up screen:

![image](https://github.com/user-attachments/assets/cc75f8a0-8f60-47cf-9454-6f435c0a8b0c)

During the registration, AWS Cognito by default will perform an email verification process by sending an email with a code.

![image](https://github.com/user-attachments/assets/3e50c844-1e68-4f5f-abf3-ed041ca4838d)

The user will view their email inbox and fetch the code to paste into the verification screen.

![image](https://github.com/user-attachments/assets/b9348ee2-d0b5-4222-a28d-93c68f531a35)

After this step, the user pool will have the user.  The user will be there even before the email account has been verified.

![image](https://github.com/user-attachments/assets/eb714784-0b36-4bba-8f3f-dceaa1b6598b)



