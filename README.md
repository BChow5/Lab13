# Lab13

![lab 13 screenshot 1](https://github.com/user-attachments/assets/85ec974e-7193-48e4-8823-62c62729f8f2)


![lab 13 screenshot 2](https://github.com/user-attachments/assets/98000a8f-2018-4cb4-b7f2-faca3dcd0a91)

- The state file is created to the bucket after the `terraform apply` completes.
- The lock file is present only while a state changing operation is in progress. Such as terraform plan or apply.
- The lock file is not always in the bucket after is is created. it's meant to be temporary to prevent 2 people from making changes at the same time. the lock file is deleted after the command is finished.
