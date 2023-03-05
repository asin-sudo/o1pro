
# Determining the appropriate use of resource policies for AWS services



## Authors

- Asin Pokharel


## Documentation

[Documentation AWS IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)


## Project Description:
   - Learn about AWS Policies and create the policies as per the required permission
## Objectives:
  - Learn about AWS Policy
  - What is identity-based policy?
  - Create a custom policy that provides the EC2 full access, S3 bucket create access.
  - Assign the policy to the user and check the access using aws cli.
  
## AWS POLICY:
  -- In AWS, a policy is an object that, when linked to an entity or resource, determines the rights for that resource or entity. When a principal, like a user, submits a request, AWS assesses these rules. Whether a request is approved or rejected depends on the permissions in the policies. 
## AWS POLICY:
  -- In AWS, a policy is an object that, when linked to an entity or resource, determines the rights for that resource or entity. When a principal, like a user, submits a request, AWS assesses these rules. Whether a request is approved or rejected depends on the permissions in the policies. 

### Identity Based Policy:
 - The policy is used for granting permissions to an identity. It can be attached to the user groups. Permissions in the policy are responsible if the request made by user is allowed or denied.
    - The Key elements of policy are:
        - Effect – Specifies whether to allow or deny.
        - Action:  what are things we can do on the specific resource.
        - Resource: The resource which the policy is applied.



  
## Usage:

    -Creating custom policy for EC2 full access and S3 bucket create access.

 ![App Screenshot](https://github.com/asin-sudo/o1pro/blob/main/identity1.jpg?raw=true)
   
-JSON FORMAT:
 ![Policy in Json format ](https://raw.githubusercontent.com/asin-sudo/o1pro/main/identity2.jpg)
 
 -Attaching the policy to the user:
  ![Attching policy](https://github.com/asin-sudo/o1pro/blob/main/identity3.png?raw=true)

  -Accesing user from aws cli:
  ![Attaching policy](https://github.com/asin-sudo/o1pro/blob/main/identity4.png?raw=true).

  
  


    


    




## License

[MIT](https://choosealicense.com/licenses/mit/)

