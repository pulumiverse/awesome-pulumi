# Awesome Pulumi [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of resources on [Pulumi](https://www.pulumi.com/).
[<img src="./pulumi.svg" align="right" width="100">](https://pulumi.com)
Your [contributions](https://github.com/pulumiverse/awesome-pulumi/blob/master/CONTRIBUTING.md) are welcome!

Pulumi is a multi-language and multi-cloud development platform. It lets you create all aspects of cloud programs using real languages and real code, from infrastructure on up to the application itself. Just write programs and run them, and Pulumi figures out the rest.

## Contents

* [Official Resources](#official-resources)
* [Books](#books)
* [Tutorials and Blog Posts](#tutorials-and-blog-posts)
* [Providers](#providers)
* [Tools](#tools)
* [Libraries](#libraries)
* [Talks and Videos](#talks-and-videos)
* [Projects using Pulumi](#projects-using-pulumi)

## Official Resources

[Get Started](https://www.pulumi.com/docs/get-started/) - Getting Started with Pulumi.

[Documentation](https://www.pulumi.com/docs/) - Pulumi documentation covering what Pulumi is, how to get started using it, and reference materials for its features and supported cloud providers.

[Pulumi Registry](https://www.pulumi.com/registry/) - A searchable collection of Pulumi Packages published by Pulumi and our partners.

[Blog](https://www.pulumi.com/blog/) - Pulumi blog covering what is new, technical how-tos, customer stories, etc.

[IaC Recommended Practices](https://www.pulumi.com/blog/iac-recommended-practices-code-organization-and-stacks/) - Blog series discussing recommended practices related to stack organization, project structure, access control setup, deployments, and refactoring. 

## Books

[The Pulumi Book](https://thepulumibook.com) - A book that shows you how to use Pulumi to build serverless applications of all kinds using TypeScript and Amazon Web Services.

## Tutorials and Blog Posts

### Beginner Guides

- Introduction to Pulumi - [Katacoda](https://www.katacoda.com/jaxxstorm/courses/introduction-to-pulumi-ts) and [GitHub](https://github.com/pulumi/introduction-to-pulumi)
- [Pulumi - What and Why?](https://www.sanjaybhagia.com/2020/09/10/pulumi-what-and-why)
  - [How it works](https://www.sanjaybhagia.com/2020/09/21/pulumi-how-it-works)
  - [Configuration management](https://www.sanjaybhagia.com/2021/01/15/pulumi-configuration-management)
  - [Secrets Management](https://www.sanjaybhagia.com/2021/01/26/pulumi-secrets-management)
  - [State Management](https://www.sanjaybhagia.com/2021/02/01/pulumi-state-management)
  - [Things I Wish I Knew Earlier About Pulumi](https://vsupalov.com/pulumi-learnings/)

### What is Pulumi?

- [Pulumi: A True Infrastructure as Code Paradigm](https://betterprogramming.pub/pulumi-a-true-infrastructure-as-code-paradigm-ac07c530e219)
- [Infrastructure as Code in TypeScript with Pulumi](https://blog.bitsrc.io/infrastructure-as-code-in-typescript-with-pulumi-31619abfe5d4)
- [WTH is Pulumi?](https://samcogan.com/wth-is-pulumi/)
- [What is Pulumi? Key Concepts and Features Overview](https://spacelift.io/blog/what-is-pulumi)

### AWS

- [Integrating EC2 macOS workers with EKS and GitLab](https://aws.amazon.com/blogs/opensource/integrating-ec2-macos-workers-with-eks-and-gitlab/)
- [Pulumi and LocalStack — beyond the basics](https://delitescere.medium.com/pulumi-and-localstack-beyond-the-basics-d993f3b94d17)
- [The Progression of Self Service at KPMG (Part 1)](https://medium.com/kpmg-uk-engineering/the-progression-of-self-service-at-kpmg-part-1-8923e64966e4)
- [Pulumi AWS Tutorial: Create a Lambda Function That Sends You Morning Emails Via SNS](https://travis.media/pulumi-aws-create-lambda-sns/)
- [Creating CodeBuild projects with Pulumi](https://dev.to/danielrbradley/replacing-build-servers-with-pulumi-aws-28fm)
- [Pulumi & AWS minimum viable build](https://katiekodes.com/pulumi-minimum-viable-build/)
- [DynamoDB + Pulumi - The Ultimate Guide w/ Examples](https://dynobase.dev/dynamodb-pulumi/)
- [Automating AWS IaC with Github Actions](https://fearlessaws.substack.com/p/automating-infrastructure-as-code)
- [Lambda function URL with custom hostname](https://medium.com/@etienne.callies_59291/aws-lambda-function-url-with-custom-hostname-using-pulumi-454bf4062b00)
- [Cron-scheduled lambda](https://medium.com/@etienne.callies_59291/scheduled-lambda-with-pulumi-88830aa0b4fe)
- [Production Grade Static Site on AWS using Route53, CloudFront, and S3](https://medium.com/aws-in-plain-english/deploying-a-production-grade-static-site-on-aws-using-route53-cloudfront-and-s3-with-pulumi-17d95f9a283a)
- [Deploy a Docker Based API using AWS Lambda Function URLs and CloudFront. No API Gateway needed.](https://medium.com/aws-in-plain-english/simplifying-serverless-deploy-a-docker-based-api-using-aws-lambda-function-urls-no-api-gateway-c18016591663)
- [Multi-service ECS Fargate cluster accessible via HTTPS custom hostname](https://medium.com/@etienne.callies_59291/deploy-your-aws-ecs-cluster-with-pulumi-0cdd5b949303)

### Azure

- [Workshop to learn Pulumi on Azure](https://github.com/TechWatching/pulumi-azure-workshop) 
- [Cloud Governance - The Best Way (Azure)](https://cloud-right.com/2020/03/cloud-governance-pulumi)
  - [ Managing Deployment Secrets with Pulumi ](https://cloud-right.com/2020/06/pulumi-encrypt-secrets-azure-keyvault)
- [Getting started with Pulumi on Azure](https://cloud-right.com/2019/03/azure-pulumi-getting-started)
- [Using Pulumi on Azure Storage Accounts](https://cloud-right.com/2019/10/pulumi-azure-storage)
- [API's From Dev to Production - Part 11 - Pulumi](https://dev.to/newday-technology/api-s-from-dev-to-production-part-11-pulumi-3pmk)
- [Introduction to Infrastructure as Code on Azure using Python with Pulumi](https://devblogs.microsoft.com/devops/infrastructure-as-code-azure-python-wpulumi/?WT.mc_id=devops-33154-jagord)
- [Pulumi with an Azure Blob Storage Backend](https://www.techwatching.dev/posts/pulumi-azure-backend)
- [How to provision an Azure SQL Database with Active Directory authentication](https://www.techwatching.dev/posts/sqldatabase-active-directory-authent)
- [Using the Azure SDK with Pulumi](https://samcogan.com/using-the-azure-sdk-with-pulumi/)
- [Storing Pulumi State in Azure](https://samcogan.com/storing-pulumi-state-in-azure/)
- [Introduction to Infrastructure as Code and Pulumi with Azure](https://www.codeproject.com/Articles/5334973/Introduction-to-Infrastructure-as-Code-and-Pulumi)
  - [Pulumi in Action on Azure](https://www.codeproject.com/Articles/5335047/Pulumi-in-Action-on-Azure)
  - [Advanced Pulumi on Azure](https://www.codeproject.com/Articles/5335048/Advanced-Pulumi-on-Azure)
- [Create an Azure-Ready GitHub Repository using Pulumi](https://www.techwatching.dev/posts/azure-ready-github-repository)
- [Deploying to Azure from Azure DevOps without secrets](https://www.techwatching.dev/posts/ado-workload-identity-federation)

### DigitalOcean

- [Think Outside the Stack With Pulumi](https://shawn.vause.us/posts/think-outside-stack-pulumi)

### Google Cloud

- [GKE Autopilot Kubernetes Cluster with Pulumi Infrastructure as Code](https://medium.com/@felipegirotti/gke-autopilot-kubernetes-cluster-with-pulumi-infrastructure-as-code-c74ae8f7ee0f)
  - [Install Ingress-Nginx and ExternalDNS with Pulumi on GKE Autopilot](https://medium.com/@felipegirotti/install-ingress-nginx-and-externaldns-with-pulumi-on-gke-autopilot-6417c13f99ce)
  - [Gitlab Pipelines, Build, Tests, and Deploy Private Images (GKE, Pulumi)](https://medium.com/@felipegirotti/gitlab-pipelines-build-tests-and-deploy-private-images-gke-pulumi-480d5d56759b)
- [Running containerized android tests in GCP using Pulumi and Selenoid](https://medium.com/@madhankumaravelu93/running-containerized-android-tests-in-gcp-using-pulumi-and-selenoid-faf4c398cd6c)

### Comparison

- [Pulumi vs Terraform](https://pritchard.dev/pulumi-vs-terraform/)
- [Why will I choose Pulumi over Terraform for my next project?](https://www.techwatching.dev/posts/pulumi-vs-terraform)

### CrossGuard (Policy as Code)
- [Getting Started with Policy as Code](https://fearlessaws.substack.com/p/getting-started-with-policy-as-code)

### Miscellaneous
- [Pulumi - Why it Matters](https://blog.effective-flow.ch/posts/2022/pulumi-why-it-matters)
- [Serverless Redis with Cloudflare Workers & Pulumi](https://dev.to/fllstck/serverless-redis-with-cloudflare-workers-pulumi-12ke)
- [Observable Infrastructure as Code](https://dev.to/fllstck/observable-infrastructure-as-code-52ha)
- [My experience migrating my infrastructure from Terraform to Pulumi](https://blog.ekik.org/my-experience-migrating-my-infrastructure-from-terraform-to-pulumi)
- [Building an ML Platform from Scratch](https://www.aporia.com/blog/building-an-ml-platform-from-scratch/)
- [Creating Infrastructure Components with Pulumi and Bit](https://blog.bitsrc.io/creating-pulumi-aws-components-with-bit-4c3691eb0adb)
- [Building Fauna’s GDPR-compliant distributed and scalable database infrastructure with Pulumi](https://fauna.com/blog/building-faunas-gdpr-compliant-distributed-and-scalable-database)
- [Building Dispo](https://regynald.com/)
- [Managing Rancher Resources using Pulumi as an Infrastructure as Code Tool](https://community.suse.com/posts/managing-rancher-resources-using-pulumi-as-an-infrastructure-as-code-tool)
- [Adding Security Contexts to Helm Charts with Pulumi Transformations](https://samcogan.com/adding-security-contexts-to-helm-charts-with-pulumi-transformations/)
- [Debugging Pulumi Infrastructure as Code in Visual Studio](https://samcogan.com/debugging-pulumi-code-in-visual-studio/)
- [Pulumi OCI Provider: How to create a Minecraft ARM instance on Oracle Cloud Infrastructure](https://blog.ediri.io/pulumi-oci-provider-how-to-create-a-minecraft-arm-instance-on-oracle-cloud-infrastructure)
- [Pulumi Function Serialisation by Example](https://mark.smithson.me/pulumi-function-serialisation-by-example)
- [Pulumi Development with GitHub Codespaces](https://samcogan.com/pulumi-development-with-github-codespaces/)
- [Implementing Feature Flags with Pulumi](https://medium.com/itnext/implementing-feature-flags-with-pulumi-df578fc9ea43)

## Providers

- [`jaxxstorm/pulumi-rke`](https://github.com/jaxxstorm/pulumi-rke) - Provision an RKE Kubernetes cluster with Pulumi
- [`jaxxstorm/pulumi-scaleway`](https://github.com/jaxxstorm/pulumi-scaleway) - Provision to Scaleway using Pulumi
- [`brandonkal/pulumi-command`](https://github.com/brandonkal/pulumi-command) - A simple Pulumi provider that allows one to run arbitrary commands and treat their outputs as a resource
- [`unplatform-io/pulumi-commercetools`](https://github.com/unplatform-io/pulumi-commercetools) - CommerceTools resource provider for Pulumi

## Tools

- [`ksrichard/gocloud`](https://github.com/ksrichard/gocloud) - Create cloud based applications in Go
- [`getcoconut/coconut`](https://github.com/getcoconut/coconut) - Serverless development tools around the Pulumi Cloud Framework (PCF)
- [`nebulis-io/pulumi-react-app`](https://github.com/nebulis-io/pulumi-react-app) - Deploy react apps
- [`ikovac/CICD-pipeline-with-pulumi`](https://github.com/ikovac/CICD-pipeline-with-pulumi) - Deploy CICD pipelines
- [`vitobotta/pulumi-kubernetes-deployments`](https://github.com/vitobotta/pulumi-kubernetes-deployments) - Automate deployments of applications and services to K8s
- [`localstack/pulumi-local`](https://github.com/localstack/pulumi-local) - Use Pulumi with LocalStack, easy-to-use test/mocking for cloud apps
- [`env0`](https://www.env0.com) - Automate your Pulumi workflows with extra control over RBAC, Pull Request Automation, and other helpful features. 
- [`tmeckel/pulumi-tf-provider-cookiecutter`](https://github.com/tmeckel/pulumi-tf-provider-cookiecutter) - A Cookiecutter template to create a Pulumi provider out of a Terraform Provider using TF Bridge
- [`Deskypus`](https://deskypus.github.io) - Cross-platform desktop app to supercharge your local development experience whether you use self-managed or Pulumi Cloud as your backend
- [`Deskypus Deeplink`](https://github.com/deskypus/deeplink#installation) A browser extension that deep-links into Deskypus while browsing Pulumi Cloud
- [`spigell/pulumi-hcloud-kube-hetzner`](https://github.com/spigell/pulumi-hcloud-kube-hetzner) - Deploy and manage Kubernetes (k3s) cluster with Hetzner Cloud.

## Libraries

- [`jen20/pulumi-aws-vpc`](https://github.com/jen20/pulumi-aws-vpc) - Node.js and Python implementation of the AWS VPC Best-Practice Guidelines
- [`place1/kloudlib`](https://github.com/place1/kloudlib) - A collection of NPM libraries for deploying commonly used open source software to Kubernetes using Pulumi.
- [`vitobotta/pulumi-kubernetes-deployments`](https://github.com/vitobotta/pulumi-kubernetes-deployments) - A collection of Pulumi scripts used to automate repetitive deployments of applications and services to Kubernetes.
- [`webiny/webiny-js`](https://github.com/webiny/webiny-js) - Platform for building serverless applications and APIs
- [`m3o/platform`](https://github.com/m3o/platform) - Infrastructure automation for the Micro platform
- [`cfeenstra67/statey`](https://github.com/cfeenstra67/statey) - Infrastructure-as-code framework written in Python
- [`tabetalt/pulumix`](https://github.com/tabetalt/pulumix) - Set of template-driven Pulumi resources used to configure Tabetalt's intrastructure as code.
- [`codedevote/pulumix`](https://github.com/codedevote/pulumix) - Simple extensions and helpers to use with Pulumi
- [`pulumiverse/katwalk`](https://github.com/pulumiverse/katwalk) - Library for LLM backend deployments using Pulumi

## Reference Architectures
- [Office Booker](https://github.com/o2Labs/office-booker) - Real-time office space booking app
- [Zephyr](https://github.com/pulumi/zephyr-app) - Online store

## Talks and Videos

- [Infrastructure as Code & GitOps | Rawkode Live](https://www.youtube.com/watch?v=s9zjayZ1oxA)
- [Pulumi - IaC in your favorite programming language!](https://www.youtube.com/watch?v=vIjeiDcsR3Q)
- [Pulumi - Infrastructure as Code (IaC) Using Programming Languages](https://www.youtube.com/watch?v=oE3BUi_N0qc)
- [Getting from code to cloud with VS Code and Pulumi](https://www.youtube.com/watch?v=keEf2eoH-js)
- [Pulumi - Simplified in Three Minutes](https://www.youtube.com/watch?v=S1-j-qTYQgY)
- [The Ultimate Walkthrough to building a Pulumi Dynamic Provider](https://www.youtube.com/watch?v=H4nehfvCLm8)
- [Quick Tech - Pulumi-Intro](https://www.youtube.com/watch?v=X2pWCPrgieI)
- [How To Import Existing Resource to Pulumi](https://www.youtube.com/watch?v=O3BL7sEX1EQ)
- [PulumiTV](https://www.youtube.com/c/PulumiTV/videos)
- [Infrastructure as code - is it really?](https://www.youtube.com/watch?v=mukFFVM-jgg) - Shahid Iqbal
- [Infrastructure as Real Code - An Intro to Pulumi](https://www.youtube.com/watch?v=cBPfKVm6G1E) - Chris Klug

## Projects using Pulumi

### Open Source
- [Daily.dev](https://daily.dev/)[^dailydev]

### Commercial Products
- [FeedHive](https://feedhive.io/)[^feedhive]

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Geoffrey Huntley has waived all copyright and related or neighboring rights to this work.

[^dailydev]: [Daily.dev tech stack](https://github.com/dailydotdev/daily#-tech-stack)
[^feedhive]: [Saas template from the creator of FeedHive](https://github.com/SimonHoiberg/saas-template#tech-stack)
