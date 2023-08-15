# Security scanning with Trivy

TBD

## How to use:

### Example 1: Basic setup, no arguments needed


```yml
- name: Run security scan
  uses: propertylift/github.action.security-scan
  with:
    severity: '%list_of-severities%'
    token: ${{ secrets.GITHUB_TOKEN }}
  ```


## Inputs:

| Parameter Name                     | Required | Default  | Description |
|------------------------------------|----------|----------|---------|
| severity                           | No       | UNKNOWN,LOW,MEDIUM,HIGH,CRITICAL | Location of python interpreter |
| token                              | Yes      | -        | GITHUB_TOKEN |
