# 🚀 GitHub Actions

## Continuous Testing

I use GitHub Actions to automate:

- Regression Tests
- Smoke Tests
- Scheduled Runs
- Reports
- Artifact Uploads

```yaml
name: QA Automation

on:
  push:
    branches:
      - main
```