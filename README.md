
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

 ![App Screenshot](https://gitlab.01procenter.com/01procenter/proassociates/batch-2/aws/design-secure-apps-and-arch/design-secure-access-to-aws-resources/aws-resource-policies/uploads/513f83ee6687af0c6f2a2ca3fdbe7115/image.png)
   
-JSON FORMAT:
 ![Policy in Json format ](https://gitlab.01procenter.com/01procenter/proassociates/batch-2/aws/design-secure-apps-and-arch/design-secure-access-to-aws-resources/aws-resource-policies/-/issues/1#note_1525)
 
 -Attaching the policy to the user:
  ![Attching policy](https://gitlab.01procenter.com/01procenter/proassociates/batch-2/aws/design-secure-apps-and-arch/design-secure-access-to-aws-resources/aws-resource-policies/-/issues/1#note_1526)

  -Accesing user from aws cli:
  ![Attaching policy](https://gitlab.01procenter.com/01procenter/proassociates/batch-2/aws/design-secure-apps-and-arch/design-secure-access-to-aws-resources/aws-resource-policies/-/issues/1#note_1527).

  
  


    


    




## License

[MIT](https://choosealicense.com/licenses/mit/)

