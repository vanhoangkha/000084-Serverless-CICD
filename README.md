# Serverless - CI/CD with AWS CodePipeline

> CI/CD for serverless applications.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series, available in English and Vietnamese.

**Read the workshop online:** https://vanhoangkha.github.io/000084-Serverless-CICD/

## Overview

Continuous Integration, Continuous Delivery, Continuous Deployment (CI/CD) are software development practices for producing software in short cycles between merging source code changes and updating applications. The ultimate goal of these practices is to reduce the costs, time, and risks by delivering software in small pieces.

In workshop 7 of this series, we will know about CI/CD flow building so that every time you change and push source code on the git repository, it will automatically re-update our services and applications. There are many tools for us to build CI/CD, the most popular are Jenkins, Gitlab CI, Circle CI. In this workshop, we will use AWS's CodePipeline.

## Workshop contents

1. Preparation
2. Build SAM pipeline
   - Create Git repository
   - Create SAM pipeline
3. Build pipeline for front-end
   - Create Git repository
   - Create pipeline
4. Test web operation
5. Cleanup

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone https://github.com/vanhoangkha/000084-Serverless-CICD.git
cd 000084-Serverless-CICD
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages (`*.md` English, `*.vi.md` Vietnamese) |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
