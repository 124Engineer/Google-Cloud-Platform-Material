# GCP IAM Links

- 📘 Checklist "IAM Best practices" - [link](https://cloud.google.com/iam/docs/using-iam-securely)
- 📘  Article "Least Priviledge" - [link](https://cloud.google.com/iam/docs/using-iam-securely#least_privilege)
- 📘 Article "GCP IAM Roles Explained" covers when to use which type of role - [link](https://medium.com/google-cloud/gcp-iam-roles-explained-af84955346e7)
- 📘 Article "GCP Security Whitepapers" - [link](https://services.google.com/fh/files/misc/security_whitepapers_march2018.pdf)
- 📚 Docs "GCP Security Best Practices - [link](https://cloud.google.com/security/best-practices)

## Usability Tips

To view the associated permissions with for a GCP IAM role, you can use this command (update for your `service.role` use case):
```
gcloud iam roles describe roles/cloudfunctions.serviceAgent
```
