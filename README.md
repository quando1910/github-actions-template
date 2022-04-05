# Github Action Template
## Install
- Copy yml file into `.github/workflows`.
- Please update the content file proper with your project situation. I also leave the comment in each file, so that it's easy to update.
- Push code to your repo and check.

### Description
- `ci-workflow.yml`: check eslint each time have PR with specific branch.
- `deploy-to-s3.yml`: build & deploy code into s3 bucket and clear cache in cloudfront also.
