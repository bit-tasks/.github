## Bit and Git CI/CD

The Bit Tasks organization contains different scripts, tools and CI/CD solutions to use Bit with Git.

### GitHub :octocat:

| GitHub Marketplace Tasks | Docker Shell Scripts | Examples (Marketplace Tasks) | Dependabot |
|---------------------------|-----------------------------|---------------------------|------------|
| [Initialize Bit](https://github.com/bit-tasks/init) | [github.bit.init](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.init) | [Examples](https://github.com/bit-tasks/github-action-examples) | [Setup Guide](https://github.com/bit-tasks/dependabot) |
| [Bit Verify Components](https://github.com/bit-tasks/verify) | [github.bit.verify](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.verify) | | |
| [Bit Tag and Export](https://github.com/bit-tasks/tag-export) | [github.bit.tag-export](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.tag-export) | | |
| [Bit Pull Request Build](https://github.com/bit-tasks/pull-request) | [github.bit.pull-request](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.pull-request) | | |
| [Bit Lane Cleanup](https://github.com/bit-tasks/lane-cleanup) | [github.bit.lane-cleanup](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.lane-cleanup) | | |
| [Commit Bitmap](https://github.com/bit-tasks/commit-bitmap) | [github.bit.commit-bitmap](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.commit-bitmap) | | |
| [Dependency Update](https://github.com/bit-tasks/dependency-update) | [github.bit.dependency-update](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.dependency-update) | | |
| [Branch Lane](https://github.com/bit-tasks/branch-lane) | [github.bit.branch-lane](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/github.bit.branch-lane) | | |



### GitLab ![GitLab Logo](https://docs.gitlab.com/assets/images/gitlab-logo-header.svg)

| Docker Shell Scripts | Examples (GitLab Pipelines) |
|-----------------------------|-----------------------------|
| [gitlab.bit.init](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.init) | [Examples](https://github.com/bit-tasks/gitlab-pipeline-examples) |
| [gitlab.bit.verify](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.verify) | |
| [gitlab.bit.tag-export](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.tag-export) | |
| [gitlab.bit.merge-request](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.merge-request) | |
| [gitlab.bit.lane-cleanup](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.lane-cleanup) | |
| [gitlab.bit.commit-bitmap](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.commit-bitmap) | |
| [gitlab.bit.dependency-update](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.dependency-update) | |
| [gitlab.bit.branch-lane](https://github.com/bit-tasks/bit-docker-image/blob/main/scripts/gitlab.bit.branch-lane) | |


### Jenkins :jenkins:

- **Tasks (Pipeline Scripts)**
  - [Initialize Bit](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/bit-init)
  - [Bit Verify Components ](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/verify)
  - [Bit Tag and Export](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/tag-export)
  - [Bit Pull Request Build  ](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/pull-request)
  - [Bit Lane Cleanup  ](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/lane-cleanup)
  - [Commit Bitmap  ](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/commit-bitmap)
  - [Dependency Update](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/dependency-update)
  - [Branch Lane](https://github.com/bit-tasks/jenkins-examples/blob/main/jenkins-files/branch-lane)


- **Examples (Pipeline Scriptrs)**
  - [Examples](https://github.com/bit-tasks/jenkins-examples)


### Azure DevOps

#### Azure DevOps Examples


### Other Scripts


#### Shell Scripts :shell:


#### Node Scripts :nodejs:



### Bit Docker Image
You can use the [Bit Docker image](https://github.com/bit-tasks/bit-docker-image) with various CI/CD tools. Select from these available images:

- **Latest Stable:** 
  ```
  bitsrc/stable:latest
  ```
  
- **Nightly:** 
  ```bash
  bitsrc/nightly:latest
  ```

