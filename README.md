# GitHub Actions Pipeline - Node.js CI

A simple GitHub Actions workflow that demonstrates Continuous Integration with Node.js environment setup and personalized messaging.

## 🚀 Features

- **Automated CI/CD**: Triggers on every push and pull request to main branch
- **Node.js Setup**: Configures Node.js 14.x environment on Ubuntu latest
- **Personalized Output**: Displays custom message with GitHub username
- **Professional Workflow**: Uses latest GitHub Actions best practices

## 📋 Workflow Details

### Triggers
- Push to `main` branch
- Pull requests to `main` branch

### Jobs
- **Environment**: `ubuntu-latest`
- **Node.js Version**: 14.x
- **Steps**:
  1. Checkout repository code
  2. Setup Node.js environment
  3. Display personalized message

### Output
```
Hello from @Vasanthadithya-mundrathi!
```

## 📁 Files

- `.github/workflows/node.js.yml` - Main workflow configuration
- `README.md` - Project documentation

## 🔧 How to Use

1. Push any changes to the main branch
2. Go to the "Actions" tab in your GitHub repository
3. View the workflow execution and logs
4. See the personalized message in the "Log message" step

## 🎯 Purpose

This project demonstrates:
- GitHub Actions workflow creation
- CI/CD pipeline implementation
- YAML configuration for automation
- Professional DevOps practices

