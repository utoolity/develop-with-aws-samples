# Develop with AWS (Samples)

This repository provides samples for [Develop with AWS](https://go.utoolity.net/apps/develop-with-aws), a Utoolity solution to integrate your AWS DevOps toolchain with the Jira Software Open DevOps experience.

## Supported AWS services

Develop with AWS aims to support many applicable AWS services and resource types down the road, refer to [Integrations](https://utoolity.atlassian.net/wiki/spaces/UDAWS/pages/3994550555) for details – it currently allows you to:

* Track CodePipeline, CodeBuild, and CloudFormation activity …
  * … on the Jira [deployments view](https://support.atlassian.com/jira-software-cloud/docs/enable-deployments/) and as issue [release information](https://support.atlassian.com/jira-software-cloud/docs/view-release-information-for-an-issue/)
    * Note that Jira currently only supports CodeBuild and CloudFormation activity triggered via CodePipeline actions.
  * … in the Compass [activity feed](https://developer.atlassian.com/cloud/compass/components/what-is-an-activity-feed/) and as component [activity](https://developer.atlassian.com/cloud/compass/components/view-a-components-activity/) and [metrics](https://developer.atlassian.com/cloud/compass/components/connect-or-disconnect-component-metrics/)

## License

Licensed under the MIT License, see [LICENSE](LICENSE) for details.
