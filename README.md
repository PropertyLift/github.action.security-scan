# Security scanning with Trivy

TBD

## How to use:

### Example 1: Basic setup, no arguments needed


```yml
- name: Configure environment
  uses: propertylift/github.action.security-scan
  with:
    severity: '%list_of-severities%'
    githubToken: ${{ secrets.GITHUB_TOKEN }}
  ```


## Inputs:

| Parameter Name                     | Required | Default  | Description |
|------------------------------------|----------|----------|---------|
| severity                           | No       | UNKNOWN,LOW,MEDIUM,HIGH,CRITICAL | Location of python interpreter |
| githubToken                        | Yes      | -        | GITHUB_TOKEN |
