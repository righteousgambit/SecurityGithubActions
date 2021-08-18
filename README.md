# SecurityGithubActions
This is a repository for deploying security controls as Github Actions for your Github projects. The intent is to achieve feature parity with or exceed the capabilities provided natively @ Gitlab via [Auto DevOps](https://docs.gitlab.com/ee/topics/autodevops/)
  
## TODO
- __container scanning__
  - Trivy
- __dependency list__
  - Gitlab custom dependency listing tool?
- __dependency scanning__
  - Analyzers
    - Ruby
      - Gemnasium
      - bundler-audit
    - Python
      - standard analyzer of requirements.txt or variations (e.g. requirements.pip)
    - Java and Scala
    - JavaScript
      - Gemnasium (supports multiple lockfiles)
      - Retire.js (does not support multiple lockfiles)
    - PHP, Go, C, C++, .NET, C# (supports multiple lockfiles)
- __dynamic application security testing (DAST)__
- __DAST API__
- __API fuzzing__
- __Secret Detection__
- __Security Dashboard__
- __Coverage fuzzing__
- __Cluster Image Scanning__

## Not Included in Gitlab, but proposed based on AErmie examples
- __various IAC scanners__
- __various linters__
