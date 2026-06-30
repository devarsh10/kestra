## Deploying Kestra and running the CircleCI pipeline

As part of exploring Kestra's orchestration capabilities, I deployed Kestra locally via Docker and built a sample workflow modeled after our existing Mifos Gazelle CircleCI pipeline. The workflow replicates our deploy-and-verify sequence — simulating pod deployment, verifying readiness, and validating service endpoints via HTTP requests — demonstrating how our current CI/CD verification logic could be orchestrated using Kestra. Screenshot of the successful execution attached below.

<img width="823" height="1650" alt="image" src="https://github.com/user-attachments/assets/ec453b1e-135f-4a88-8df5-427f8701acd9" />

<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/c25b56fe-0182-4a42-857e-f91eb6f84747" />

### Reference
https://github.com/openmf/mifos-gazelle/blob/dev/.circleci/config.yml
