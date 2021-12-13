---
title: "Codefresh On-Premises Feature Flags"
description: "List and description of the different feature flags"
group: administration
redirect_from:
  - /docs/enterprise/onprem-flags/
toc: true
---

## Introduction

This manual will describe the different feature flags available for the [Codefresh on-prem](codefresh-on-prem.md) instance.

{: .table .table-bordered .table-hover}
| Feature Flag Name | Description | Version | Default Value | Note |
| ---------------------------- | ------------------------------------ | -------- | ----- | ------------------------------------ |
| azureNestedGroupSync | Enables ability to sync nested groups from Azure AD | 1.0.194 | FALSE | does it sync sub-groups as well into team or just users in sub-groups |
| credsInArgsForHttpChartRepos | set CREDENTIALS_IN_ARGUMENTS to true for http/https charts repositories | 1.0.194 | FALSE | how is it used? |
| imageRegexp | Use new regexp for searching image during annotation | 1.0.194 | FALSE | add info on what is new regexp by opposition to "old" |
| log-throttle | Enables improved log throttling in logs terminal component | 1.0.194 | FALSE | what are log terminal component? |
| pipelineEnforcementsFlag | Enable pipeline enforcements feature | 1.0.175 | TRUE | Value changed in 1.0.194 |
| pipelineWhiteListFlag | Enable pipeline whitelist settings feature | 1.0.175 | TRUE | Value changed in 1.0.194 |
| pipelinePvcFlag | Enable keep PVCs for pending approval | 1.0.175 | TRUE | Value changed in 1.0.194 |
| newBuildDesign | New builds design |  ??? | TRUE | Value changed in 1.0.194 |
| pendingApprovalConcurrencyApplied | Applies concurrency limits of pipeline on pending approval workflows | 1.0.175 | TRUE | Value changed in 1.0.194 |
| buildsPointerPagination | new builds list pointer pagination | 1.0.175 | TRUE | Value changed in 1.0.194 |
