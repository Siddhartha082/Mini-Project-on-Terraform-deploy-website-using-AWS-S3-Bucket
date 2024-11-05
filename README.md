# Hosting static website using Terraform using AWs S3 module
![image](https://github.com/user-attachments/assets/d7289ae2-1ef0-4554-b8cc-0a5a9d535719)
![image](https://github.com/user-attachments/assets/3c6cc410-db22-4a76-9c12-9f0a573e7654)
![image](https://github.com/user-attachments/assets/e390d3bb-6eda-4c5f-b031-af48cd538fe3)
# Aws Provider – terraform
https://registry.terraform.io/providers/hashicorp/aws/latest/docs
![image](https://github.com/user-attachments/assets/808527f6-db3d-4f5f-ace0-f7fb2ff13919)
![image](https://github.com/user-attachments/assets/41985050-f47a-499f-b305-b6f7fbe71183)
# tf init
![image](https://github.com/user-attachments/assets/bbba15d2-b1a4-4004-a344-71cac277623f)
# now Start working with TF creating s3 bucker + static iP …
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket
![image](https://github.com/user-attachments/assets/25a47b4c-1b87-4218-821d-49a62bb6a494)
![image](https://github.com/user-attachments/assets/36e80dc2-e44d-48ed-9dd9-e93a3bdbb8f8)
![image](https://github.com/user-attachments/assets/10640e71-72cf-441a-97e7-ee487f19ec1e)
![image](https://github.com/user-attachments/assets/dd35e524-f01b-4d39-8f16-6d1ab2af3b22)
# tf plan
![image](https://github.com/user-attachments/assets/3b09c4b7-a2e1-4256-badf-4459e8da4246)
![image](https://github.com/user-attachments/assets/6e56e22b-895d-4887-b48e-c245f8741de6)
# now Apply  tf  - to create s3 bucket
![image](https://github.com/user-attachments/assets/264db217-bda9-46cc-8c9d-7fe433605693)
# Aws S3 Bucket
![image](https://github.com/user-attachments/assets/48a71234-9d66-46be-8a68-a3ccba9569f1)
# Make the Buket Public
![image](https://github.com/user-attachments/assets/fc0888eb-019f-42ba-a07c-cf02dff7978e)
# make Static Website Host - Enable
![image](https://github.com/user-attachments/assets/13c403dc-606f-43d5-8d53-dcded90796f0)
![image](https://github.com/user-attachments/assets/02ce9f23-97be-471d-a504-9fb13834d97b)
## https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket_ownership_controls
![image](https://github.com/user-attachments/assets/7296072b-bd8d-4359-aa63-76bdde2c1df7)
![image](https://github.com/user-attachments/assets/5a3b90e6-78d2-4381-b01a-9bb77727a66f)
# Bucket Public
![image](https://github.com/user-attachments/assets/69a9fb27-e022-4515-afea-60245b6be3ed)
# example - code
![image](https://github.com/user-attachments/assets/e3ba3e83-c752-4d1d-a0b9-9b4c381e2328)
![image](https://github.com/user-attachments/assets/e3259bbb-f086-4f4e-8d5c-e01aeddb528d)
# tf plan
![image](https://github.com/user-attachments/assets/7342a100-546d-4535-a6b1-fa3ac33afe42)
# now add Resource: aws_s3_bucket_acl
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket_acl
![image](https://github.com/user-attachments/assets/b56a5b25-4739-4aad-bf12-e4f33dc5d02b)
![image](https://github.com/user-attachments/assets/292714bf-7143-4b15-b5ac-2396dabc55c6)
![image](https://github.com/user-attachments/assets/428a2b91-6170-46a3-9538-500244c813fa)
![image](https://github.com/user-attachments/assets/2f5ae3f4-d8cd-4a9e-9d0d-78d15205dbdb)
![image](https://github.com/user-attachments/assets/ef10d4d0-c647-44df-9633-558bf805e860)
# website aws_s3_bucket_website_configuration
![image](https://github.com/user-attachments/assets/35180c2d-4df0-4784-b695-bd9e1c7897a4)
# Put this index.html inside s3 bucket 
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_object
![image](https://github.com/user-attachments/assets/8ccf95ea-9946-4a3c-9b4f-9d70eae27519)
![image](https://github.com/user-attachments/assets/0d2e0618-abd6-4553-9d20-88583baf4135)
![image](https://github.com/user-attachments/assets/d4520ae7-9ad4-4f7c-981f-50e8762fcb27)
![image](https://github.com/user-attachments/assets/0d2031ea-7475-47a3-9a92-b12aadf2b6d7)
# Object Added
![image](https://github.com/user-attachments/assets/48c59088-1244-47de-afa8-8e370af53221)
# now Configure Website on terraform
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket_website_configuration
![image](https://github.com/user-attachments/assets/c4dd5531-126a-4e94-8d69-bb67839e74bb)
![image](https://github.com/user-attachments/assets/086623f2-d407-409d-aa44-49d1b8bab9b5)
![image](https://github.com/user-attachments/assets/73403714-a271-4da2-a926-687e3a81f5a0)
![image](https://github.com/user-attachments/assets/407d280b-e18e-44ae-b421-1d080a818914)
# buckets – Permission – Static Host
![image](https://github.com/user-attachments/assets/13ef28d6-bc6a-48ba-b4d7-89ca43f456de)
![image](https://github.com/user-attachments/assets/aa6d071a-cc3d-42a8-b845-f1dd66eda238)
# Output
![image](https://github.com/user-attachments/assets/6fa8afa7-8e1a-4bff-8a12-0aaff7da9389)
# # final part destroy all in S3 .
![image](https://github.com/user-attachments/assets/d3d40b67-7af8-41f8-94c3-2b9f1754b76a)
![image](https://github.com/user-attachments/assets/b5d7b0e8-e620-4b44-ae25-cd904d8f2976)

