# Lab M5.02 - Terraform CI/CD Pipeline

**Cloud Engineering Bootcamp - Week 5, Day 1**  
**Module:** Cloud Automation & CI/CD

## Start Here: Fork, Clone, and Submit
You will complete this lab by working in **your own fork** of the lab repository and submitting a **Pull Request (PR)**.
1. **Fork the lab repository** to your GitHub account.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/<your-github-username>/ce-lab-terraform-cicd-pipeline.git
   cd ce-lab-terraform-cicd-pipeline
   ```
3. **Follow all instructions below** and save your work in this repo (files, screenshots, and notes).
4. **When finished, submit your work:**
   - `git add` → `git commit` → `git push`
   - Open a **Pull Request** from your fork back to the original lab repo
   - Copy the **PR URL** and paste it into the **Lab Submission** field in the Student Portal

## 📋 Lab Overview

Build an automated CI/CD pipeline for Terraform infrastructure deployments using GitHub Actions. Learn how to safely automate infrastructure changes with proper validation and approval workflows.

## 🎯 Learning Objectives

- Automate Terraform workflows with GitHub Actions
- Implement infrastructure validation and testing
- Configure Terraform backend for state management
- Set up approval workflows for production deployments
- Integrate AWS credentials securely

## 📁 Repository Structure

```
.
├── .github/
│   └── workflows/
│       ├── terraform-plan.yml
│       └── terraform-apply.yml
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── outputs.tf
│   └── backend.tf
├── README.md
└── .gitignore
```

## Submission

Complete the lab as described in the instructions and save your work in this repo (files, screenshots, and notes):

1. **Terraform CI/CD Workflows**
   - Automated `terraform plan` on PRs
   - Automated `terraform apply` on merge to main
   - Proper AWS credentials configuration

2. **Infrastructure Code**
   - Working Terraform configuration
   - Remote state backend configuration
   - Variable management

3. **Documentation**
   - Workflow explanations
   - Deployment process documentation

## 🎓 Grading Rubric

| Criteria | Points |
|----------|--------|
| **Terraform Automation** | 35 |
| **Workflow Configuration** | 30 |
| **Security & Secrets** | 20 |
| **Documentation** | 15 |
| **Total** | 100 |

## 💡 Tips

- Use GitHub secrets for AWS credentials
- Implement PR comments for `terraform plan` output
- Add manual approval for production deployments
- Test with non-production resources first

## 📚 Resources

- [Terraform GitHub Actions](https://github.com/hashicorp/setup-terraform)
- [AWS Credentials in GitHub Actions](https://github.com/aws-actions/configure-aws-credentials)

<!-- ## 🚀 Submission

Submit your repository URL through the course platform. -->
