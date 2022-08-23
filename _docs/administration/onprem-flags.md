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
| branchesPagination |deprecated|||| 
| buildsPointerPagination | new builds list pointer pagination | 1.0.175 | TRUE | Value changed in 1.0.194 |
| codefreshV2 | Allow access to CSDP for Admin users | ??? | FALSE ||
| codefreshV2NonAdmins | Allow access to CSDP for all users | ??? | FALSE ||
| credsInArgsForHttpChartRepos | set CREDENTIALS_IN_ARGUMENTS to true for http/https charts repositories | 1.0.194 | FALSE | how is it used? |
| filterContextsByABACRules | Support RBAC for shared configuration | 1.1.1 | FALSE ||
| downloadLog |deprecated|||| 
| fixStepExtenderFailFast | Fix correct passing of fail_fast property on execution of StepExtender | ??? | TRUE | When true, fail fast property is not ignored| 
| freestyleRegistryContext | Add steps in Codefresh pipelines that push images to different AWS accounts | 1.1.1 | FALSE ||
| groupingBuildsByPipelines |deprecated|||| 
| imageRegexp | Use new regexp for searching image during annotation | 1.0.194 | FALSE | Searching for annotations in image was slow for specific SaaS customer with large number of images. <br> Regex optimizes search queries in databaseFor<BR> No need to turn for on-prem |
| lateVariableInterpolation | Allow variables to be evaluated later in the process (instead of the init phase) | ??? | Allow to use modified pipeline variables in a typed step or to use a variable some fields like registry for example|
| log-throttle | Enables improved log throttling in logs terminal component | 1.0.194 | FALSE | what are log terminal component? |
| pipelineEnforcementsFlag | Enable pipeline enforcements feature | 1.0.175 | TRUE | Value changed in 1.0.194 |
| pipelineInfoEnable | Enable pipeline info on workflow | ??? | TRUE | |
| pipelineWhiteListFlag | Enable pipeline whitelist settings feature | 1.0.175 | TRUE | Value changed in 1.0.194 |
| pipelinePvcFlag | Enable keep PVCs for pending approval | 1.0.175 | TRUE | Value changed in 1.0.194 |
| platformAnalytics | Enable charts for platform analytics | 1.2.12 | TRUE | |
| newBuildDesign | New builds design |  ??? | TRUE | Value changed in 1.0.194 |
| pendingApprovalConcurrencyApplied | Applies concurrency limits of pipeline on pending approval workflows | 1.0.175 | TRUE | Value changed in 1.0.194 |
| redirectToCSDP | Default to CSDP and prevent Classic usage | ??? | FALSE | TRUE for account created after 2022-10-19 |
| saml | SAML | 1.2.12 | TRUE |
| showClassicCodefreshButton | Show button to return to Classic UI from CSDP | ??? | TRUE | |
