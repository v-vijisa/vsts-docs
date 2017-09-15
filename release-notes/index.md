---
title: VSTS Features Timeline
author: alexcnichols
ms.author: alexn
ms.date: 09/09/2017
ms.topic: article
ms.prod: vs-devops-alm
ms.technology: vs-devops-articles
ms.manager: douge
description: VSTS feature updates and release notes
---

# VSTS Features Timeline

## Features under development

This feature list is a peek into our roadmap. It identifies some of the significant features we are currently working on and a rough timeframe for when you can expect to see them. It is not comprehensive but is intended to provide some visibility into key investments. Most features are linked to a blog post and/or UserVoice entry where you can learn more and comment. These features and dates are the current plans at this time and are subject to change. The “Planned Date” reflects when the feature will be available on VSTS, the “Server” column reflects when it will be available in TFS on-premises, if applicable, and the “Area” column reflects the area of the product the feature aligns with most.

<table>
      <thead>
        <tr><th>Planned Date</th>
		<th>Feature</th>
		<th>Server</th>
        <th>Area</th>
        </tr>
    </thead>
	    <tbody>
        <tr><td>2017 Q3</td><td>Work Items – Query page refresh</td><td>TBD</td><td>Work</td></tr>
        <tr><td>2017 Q3</td><td>Work Items – Favoriting Backlogs, Boards, and Sprints</td><td>TBD</td><td>Work</td></tr>
        <tr><td>2017 Q3</td><td>Work Items – New project work items hub</td><td>TBD</td><td>Work</td></tr>
        <tr><td>2017 Q3</td><td>Code search – indexing of multiple Git branches</td><td>TBD</td><td>Code</td></tr>
        <tr><td>2017 Q3</td><td>Git – Fork a repository and create pull requests for upstream</td><td>TFS vNext</td><td>Code</td></tr>
        <tr><td>2017 Q3</td><td>Git – Project and repo policies for file size and casing</td><td>TBD</td><td>Code</td></tr>
        <tr><td>2017 Q3</td><td>Git – Improved Branch Updates design and searching for deleted branches</td><td>TFS vNext</td><td>Code</td></tr>
        <tr><td>2017 Q3</td><td>[CI/CD – Concurrent pipelines](https://www.visualstudio.com/docs/build/concepts/licensing/concurrent-pipelines-ts#pipeline-issues) – design improvement to not consume a pipeline until an agent is assigned</td><td>TFS vNext</td><td>Build</td></tr>
        <tr><td>2017 Q3</td><td>[Agent-based deployment in Release Management](https://blogs.msdn.microsoft.com/visualstudioalm/2017/03/03/deployment-groups/) – UX improvements, Sharing of VMs</td><td>TFS vNext</td><td>Release</td></tr>
        <tr><td>2017 Q3</td><td>[Release Management – New RM editor and templates](https://blogs.msdn.microsoft.com/visualstudioalm/2017/05/26/new-release-definition-editor-in-team-services/)</td><td>TFS vNext</td><td>Release</td></tr>
        <tr><td>2017 Q3</td><td>Release Management improved orchestration – Better notifications on Releases, Branch triggers with include/exclude filters, and ag based triggers and Selective Artifacts</td><td>TBD</td><td>Release</td></tr>
        <tr><td>2017 Q3</td><td>Release Management better traceability – Integration with Jenkins, Code, Work, and Package hubs</td><td>TBD</td><td>Release</td></tr>
        <tr><td>2017 Q3/Q4</td><td>Azure Portal Continuous Delivery support – Azure App Services (AppTypes/Repos), VMs, and ACS Containers</td><td>TBD</td><td>Release</td></tr>
        <tr><td>2017 Q3</td><td>Azure Deployments first class support and task improvements – Kubernetes, VMScaleSet, Azure Functions, and Service Fabric Clusters</td><td>TBD</td><td>Release</td></tr>
        <tr><td>2017 Q3</td><td>Package Management – Upstreams sources for public registries (NuGet.org, Maven Central, etc.) and VSTS feeds across the organization and/or account</td><td>TBD</td><td>Package</td></tr>
        <tr><td>2017 Q3</td><td>Package Management – Maven general availability</td><td>TFS vNext</td><td>Package</td></tr>
        <tr><td>2017 Q3</td><td>Automated Testing – Ability to configure a batch size for better distribution across agents and frequent results publishing</td><td>TFS vNext</td><td>Test</td></tr>
        <tr><td>2017 Q3</td><td>Automated Testing – Parallel testing on multiple agents in a pool in build</td><td>TFS vNext</td><td>Test</td></tr>
        <tr><td>2017 Q3</td><td>Automated Testing – Support for running ordered tests in build/release pipelines</td><td>TFS vNext</td><td>Test</td></tr>
        <tr><td>2017 Q3</td><td>Automated Testing – Re-run failed tests in Build and RM</td><td>TFS vNext</td><td>Test</td></tr>
        <tr><td>2017 Q3</td><td>Automated Testing – Automation agents do not need Visual Studio to run tests (test platform acquisition through alternate means)</td><td>TFS vNext</td><td>Test</td></tr>
        <tr><td>2017 Q3</td><td>Manual and Exploratory Testing (XT) – Show requirements based suites (RBS) on Kanban and enable Basic XT users to provide feedback</td><td>TBD</td><td>Test</td></tr>
        <tr><td>2017 Q3</td><td>Manual and XT – XT support for Edge</td><td>TBD</td><td>Test</td></tr>
        <tr><td>2017 Q3</td><td>[Improved user management – bulk editing](https://blogs.msdn.microsoft.com/visualstudioalm/2017/04/04/team-services-large-account-user-management-roadmap-april-2017/)</td><td>TBD</td><td>Shared</td></tr>
        <tr><td>2017 Q3</td><td>[Licensing users and extensions using AAD groups](https://blogs.msdn.microsoft.com/visualstudioalm/2017/04/04/team-services-large-account-user-management-roadmap-april-2017/)</td><td>TBD</td><td>Shared</td></tr>
        <tr><td>2017 Q3</td><td>[Support for Cloud Solution Providers in managing VSTS accounts and purchases](https://blogs.msdn.microsoft.com/visualstudioalm/2017/05/09/cloud-solution-provider-purchase-from-visual-studio-marketplace-roadmap/)</td><td>TBD</td><td>Shared</td></tr>
        <tr><td>2017 Q3</td><td>[Multiple accounts per “organization”](http://blogs.msdn.com/b/visualstudioalm/archive/2016/01/11/how-we-plan-to-enable-creating-multiple-collections-per-account.aspx)</td><td>--</td><td>Shared</td></tr>
        <tr><td>2017 Q3</td><td>[Administration – Improved Alternate Authentication experience](https://blogs.msdn.microsoft.com/devops/2017/07/14/improved-alternate-authentication-experience/)</td><td>TBD</td><td>Shared</td></tr>
        <tr><td>2017 Q3</td><td>Notifications – CC/BCC (carbon copy) recipient support for email notifications</td><td>TBD</td><td>Shared</td></tr>
        <tr><td>2017 Q3</td><td>Simplified experience to more easily acquire VSTS extensions and Visual Studio subscriptions</td><td>--</td><td>Marketplace</td></tr>
        <tr><td>2017 Q4</td><td>Work Items – Markdown support</td><td>TBD</td><td>Work</td></tr>
        <tr><td>2017 Q4</td><td>Updated Windows shell extension for TFVC</td><td>--</td><td>Code</td></tr>
        <tr><td>2017 Q4</td><td>CI/CD – Private Azure agent pools for Build and RM – provide your own image, we manage the lifetime</td><td>--</td><td>Build</td></tr>
        <tr><td>2017 Q4</td><td>CI – YAML builds (config as code)</td><td>TFS vNext</td><td>Build</td></tr>
        <tr><td>2017 Q4</td><td>VSTS Symbol Server public preview</td><td>TBD</td><td>Build</td></tr>
        <tr><td>2017 Q4</td><td>Build – Bring your own subscription</td><td> </td><td>Build</td></tr>
        <tr><td>2017 Q4</td><td>Greenlighting – Azure monitoring integration for automated deployments</td><td> </td><td>Release</td></tr>
        <tr><td>2017 Q4</td><td>Package Management – CI/CD improvements including release views automation and CI versioning for packages</td><td>TBD</td><td>Package</td></tr>
        <tr><td>2017 Q4</td><td>Package Management – Retention policies and package statistics</td><td>TBD</td><td>Package</td></tr>
        <tr><td>2017 Q4</td><td>Automated Testing – Support for .NET Core</td><td>TFS vNext</td><td>Test</td></tr>
        <tr><td>2017 Q4</td><td>Cloud Load Testing – Integration with Application insights (any subscription)</td><td>--</td><td>Test</td></tr>
        <tr><td>2017 Q4</td><td>Public preview for cloud reporting experience</td><td>--</td><td>Insights</td></tr>
        <tr><td>2017 Q4</td><td>[TFS Data Import Service for VSTS](https://www.visualstudio.com/articles/migration-overview) general availability</td><td>--</td><td>Shared</td></tr>
        <tr><td>2017 Q4</td><td>Encryption at rest for disks used by code and work item search</td><td>--</td><td>Shared</td></tr>
        <tr><td>2017 Q4</td><td>Publisher certification process</td><td>--</td><td>Marketplace</td></tr>
    </tbody>
</table>

## Current features

The features timeline lists significant features delivered to VSTS and the corresponding version of Team Foundation Server.
Versions in the server column are linked to the appropriate download location. You can also [view the build numbers for each version](#build_numbers).

<table>
    <thead>
        <tr>
            <th>Service</th>
            <th>Feature</th>
            <th>Server</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="25">[15 Sep 2017](/vsts/release-notes/2017/sep-15-team-services)</td>
            <td>New Queries experience</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts in the work item form</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Contextual actions in the Work Items hub</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>HTML tags stripped in work item grids</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Filtering to the Process and Fields pages in the Process admin</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Create a folder in a repository using web</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Get a permanent link to code</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Filter text highlighting</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Wiki page deep linking</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Move page in Wiki using keyboard</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Preview content as you edit Wiki pages</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Paste rich content as HTML</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Multi-phase builds</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Personalized notifications for releases</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Manage variables using the List and Grid views in the new release definition editor</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Branch filters in environment triggers</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Improved Deployment Groups UI</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Run webtests using the VSTest task</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Chart widget for test plans and test suites</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Preview improvements and support for different log types generated by Visual Studio Test task</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Gulp, Yarn, and more authenticated feed support</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Package feed default permissions now include Project Administrators</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Burndown and Burnup widgets</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Refreshed error page and seamless tenant switching hint</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Marketplace moves to new markdown-it parser</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="29">[28 Aug 2017](/articles/news/2017/aug-28-team-services)</td>
            <td>Work Items hub</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Customizable work item rules</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Mentioned support for the My work items page</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Custom Fields and Tags in Notifications</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Inline add on Delivery Plans</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Forks</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>File minimap</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Bracket matching</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Toggle white space</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Updated email templates for push notification</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Complete Work Items settings</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Find lost commits due to a Force Push</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Update default repo permissions for admins</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>CI builds for Bitbucket repositories</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Pause build definitions</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Task input validations support</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>New Release Definition Editor general availability</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Enhancements in new Release Definition editor</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Release Template Extensibility</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Conditional release tasks and phases</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Approve multiple environments</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Requests history for service endpoints</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Upload attachments to test runs and test results</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Test batching</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>JMeter 3.2 for load testing</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Streamlined user management general availability</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Adding User to Projects and Teams</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Graph REST APIs in Public Preview</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Profile Card</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td rowspan="30">[4 Aug 2017](/articles/news/2017/aug-04-team-services)</td>
            <td>Copy work item processes</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Updated order of the last column in the Kanban board</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>See the projects using a process</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Filtering on Kanban board</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Wiki in Public Preview</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Improvements in Wiki edit experience</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Revert a Wiki revision</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Create a Wiki page from a broken link</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Setting to turn off web editing for TFVC repos</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Identify stale branches</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Search for a deleted branch and re-create it</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Branch updates page is now Pushes</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Retain filename when moving from Files to Commits</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Pull Request Status Extensibility in Public Preview</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Let contributed build sections control section visibility</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Variable group support</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>dotnet task supports authenticated feeds, web projects</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Ansible Extension on Marketplace</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Variable groups, Retention, and Options tab now available in the new Release Definition Editor</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Release status badge in Code hub</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Enhancements to Build definition menu when adding artifacts</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Revert your release definition to older version</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>		
		<tr>
            <td>Exploratory testing traceability improvements for work item links, iterations, and area paths</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Screenshot and annotation support for desktop apps with Chrome browser for manual tests</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Filters for Test Case work items in Test Plans and Suites in Test Hub</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Test trend charts for Release Environments and Test Runs</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Markdown formatting support for Test Run and Test Result comments</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Add link to existing bug for a failing test</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Re-order favorite groups</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Enable Visual Studio Code direct install option in Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
	    <tr>
            <td rowspan="20">[14 Jul 2017](/articles/news/2017/jul-14-team-services)</td>
            <td>Migrate team projects between two inherited processes with the same parent</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Filtering on Backlogs, Sprints, and Queries</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Expand to show empty fields on a Kanban card</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Automatically complete work items when completing pull requests</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Policies: Reset votes on push/new iteration</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Notifications: Great email templates for pull request workflows</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Pull request details: View original diff for code comments</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Task lists in pull request descriptions and comments</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Ability to "Like" comments in pull requests</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Pull request build variables</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Faster publishing of artifacts from Windows agents to file shares</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Code information in Release with Jenkins CI</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Task group References</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Task group versioning</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Multi Configuration support in Server Side (Agentless) tasks</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Task group import and export</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>New Release Definition Editor (Preview)</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Velocity Widget for the Analytics Extension</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Notifications: Give team admins control over the delivery of notifications targeting the team</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Constraints on SVG images, screenshots and badges</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="24">[22 Jun 2017](/articles/news/2017/jun-22-team-services)</td>
            <td>Fields can be shared across processes</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Work item type icons</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Show/hide work item field borders</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Allow extensions to block work item save</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Collapsible pull request comments</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Improved workflow when approving with suggestions</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
			<td>Filter pull request tree by file name</td>
			<td style="background:rgb(232, 232, 232);">Future</td>
		</tr>
        <tr>
            <td>Pull request callout on commit details page becomes richer</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Filter tree view in Code</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Git tags web view</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Export and import build definitions</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Visual Studio latest and hosted agent pools</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Build definition menu on build summary page</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Release Triggers: Continuous deployment for changes pushed to a Git repository</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
		<tr>
            <td>Enhancements to Server tasks</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
		<tr>
            <td>Consume Secrets from an Azure Key Vault as variables</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Package Management experience updates</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Package build task updates</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Project Collection Administrators can link/make initial purchase</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Deep link to easily remove your spending limit during a Marketplace purchase</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Improvements to OAuth permissions page</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Streamlined user management (preview)</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
		        <tr>
            <td>Enhanced Publisher experience with Sales Transactions for Paid extensions</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
		        <tr>
            <td>Setup Power BI Content Pack</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>      
        <tr>
            <td rowspan="19">[1 Jun 2017](/articles/news/2017/jun-01-team-services)</td>
            <td>Mobile work item form general availability</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>New widgets for Analytics extension</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Path filtering support for Git notifications</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>More pull request comments filtering options</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Search for a commit in branches starting with a prefix</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Visual Studio Enterprise benefit for pipelines in Team Services</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Work with secure files such as Apple certificates</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Extensions with build templates</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Deprecate a task in an extension</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Task group references</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Variables Support in Manual Intervention task</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Control releases to an environment based on the source branch</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Release Triggers for Git repositories as an artifact source</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>On-demand triggering of automated tests</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Acquisition data in Extension Hub for Marketplace publishers</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Q&A for Marketplace publishers</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>GitHub and Custom Q&A support for marketplace extensions</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Retain VSTS identity when navigating to Marketplace from VSTS</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>AAD sign in address rename</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="25">[11 May 2017](/articles/news/2017/may-11-team-services)</td>
            <td>VM deployment (Public Preview)</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Azure virtual machine scale set</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Built-in tasks for building and deploying container based applications</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Azure Web App deployment updates</td>
            <<td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Install an SSH key during a build or release</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Retiring the old editor</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Tasks fail if Visual Studio 2017 is specified but not present on agent</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Automatic linking from work items to builds</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Delivery Plans general availability</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Work item search general availability</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Updated process customization experience</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Modify out of the box fields</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Files hub improvements</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Git LFS file locking</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>New branch policies configuration experience</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Share pull requests with teams</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Default notifications for PR comments</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Improved team PR notifications</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>New tree view control</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Maven for Package Management (Public Preview)</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>NuGet Restore, Command, and Tool Installer build tasks</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Combined email recipients for notifications now enabled by default</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Out of the box notifications out of preview</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Enhanced publisher experience in the Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Owner and contributor roles can purchase through the Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="19">[19 Apr 2017](/articles/news/2017/apr-19-team-services)</td>
            <td>Delivery timeline markers</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Visualize your git repository</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Git commit comments use the new discussion control</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Improved package list</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Build tool installers</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>SSH deployment improvements</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Deploy to Azure Government Cloud</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Timeout enhancements for the Manual Intervention task</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Release Logs Page Improvements</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Azure App Service task enhancements and templates for Python and PHP applications</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Deploy Java to Azure Web Apps</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Java code coverage enhancements</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Maven and SonarQube improvements</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Improved Jenkins integration</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Google Play extension enhancements</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>iOS DevOps enhancements</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Contact extension customers</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Marketplace feedback excluded from ratings</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Reports for Marketplace Publishers</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="17">[29 Mar 2017](/articles/news/2017/mar-29-team-services)</td>
            <td>Work item search for discussions</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Pull Request filtering by people</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Reason required when bypassing pull request policies</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Add and view Git tags</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Updated Changeset and Shelveset pages</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Import repositories from TFVC to Git</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Multiple recipients included on the same email (preview)</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Conditional build tasks</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Package Management adds npm READMEs and download button</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Updated Package Management experience available to all accounts</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Override template parameters in Azure resource group deployments</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Continuous Delivery in the Azure portal supports any Git repo</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Separation of duties for deployment requester and approvers</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Set maximum number of parallel deployments</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Q&A support for Marketplace extensions</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Enhancements to display publisher’s terms, license, and privacy policy in Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Improved sign-out</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="14">[8 Mar 2017](/articles/news/2017/mar-08-team-services)</td>
            <td>Delivery Plans field criteria</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>New mobile discussion experience</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Optimized mobile identity picker</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Customized backlog levels</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Custom work item identity fields</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Pull Request improvements for teams</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>New policy for no active comments</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Build agent upgrade status</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Github pull request builds</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Keep track of your free hosted agent minutes</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Out of the box notifications enabled by default</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Getting notified when extensions are installed, require attention, and more</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Release level approvals</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>.NET Core tasks support project files</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td rowspan="13">[15 Feb 2017](/articles/news/2017/feb-15-team-services)</td>
            <td>Improved support for team PR notifications</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Improved CTAs for PR author and reviewers</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Actionable comments</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Updates view shows rebase and force push</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Improved commit filtering</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Maintenance for working directories</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Agent selection improvement</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Run tests using Agent Phases</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Multiple versions of Extension tasks</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Extension management permissions and new email notifications</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Updated Package Management experience</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Support for AAD conditional access</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Pipelines queue</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td rowspan="17">[25 Jan 2017](/articles/news/2017/jan-25-team-services)</td>
            <td>Delivery Plans</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Mobile work item form preview</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Build editor preview</td>
           <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Repo admin permission changes</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Branch policy improvements</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>PR comment improvements</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Discussion control toolbar</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>View PRs for a commit</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Release views in Package Management</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>npmjs.com upstream now caches packages</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Run tests built using Visual Studio 2017</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Track changes to test steps</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Sorting on work item search results</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td>Linking to changelog on the Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Release action in Build summary</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Security for variable groups</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Web app deployment history in Azure portal</td>
            <td style="background:rgb(155, 192, 230);">2017.2</td>
        </tr>
        <tr>
            <td rowspan="21">[5 Jan 2017](/articles/news/2017/jan-05-team-services)</td>
            <td>New account and project home pages</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Attachments in PR discussions</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Support file exclusions in the required reviewer policy</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Highlight the PRs that have updates</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Branch policy for PR merge strategy</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Expose merge conflict information</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Team Room Deprecation Annoucement</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>New notification settings experience</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>New delivery options for team subscriptions</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Out of the box notifications (preview)</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Updated hosted build image</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Firefox support for Test & Feedback extension</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Favorites for Test Plans</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Test Impact Analysis for managed automated tests</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>SonarQube MSBuild tasks</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Improved experience for Search results</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Release Management parallel execution</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Inline service endpoints</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Multiple release triggers with branch and tag filters</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Set defaults for artifact sources in RM</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Variable groups support in RM</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="14">[23 Nov 2016](/articles/news/2016/nov-23-team-services)</td>
            <td>Search for commits in branches</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Search for a file or folder in commit history</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Follow a pull request</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Restart pull request merge</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Completion blocked on rejected pull requests</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Markdown in pull request description</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Task versioning for Build and Release definitions</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Hosted Linux pool preview</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Build and deploy Docker apps to Azure more easily</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>New licensing model for Build and Release Management</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>NuGet + Credential Provider Bundle updated</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Delete test artifacts</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Inline service connections in Build and Release</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Link build artifacts from another team project</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="4">[16 Nov 2016](/articles/news/2016/nov-16-team-services)</td>
            <td>Package Management General Availability</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Release Management General Availability</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>TFS Database Import Service</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Work Item Search public preview</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td rowspan="13">[2 Nov 2016](/articles/news/2016/nov-02-team-services)</td>
            <td>Package Management in India and Brazil</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Microsoft Teams integration</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Repo Favorites</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Rollback build definitions</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Disable the sync and checkout of sources in a build</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Docker extension enhancements</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>.NET Core build task</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Build and release management templates</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>ASP.NET Core and NodeJs deployments</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Azure Web App Service manage task</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Release Management available in multiple regions</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>REST client helpers for Test Step operations</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Test case description in Web runner</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="15">[12 Oct 2016](/articles/news/2016/oct-12-team-services)</td>
            <td>New navigation on by default</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Cherry-pick and revert</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Commit page improvements</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Configurable compare branch</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Find a file or folder</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Suggested value in work item pick lists</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Xcode 8 Signing and Exporting Packages in the Xcode Build Task</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>FindBugs in the Gradle build task</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Email support for AAD groups</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Multiple schedules in releases</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Azure resource group improvements</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Azure CLI task</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Simplified Azure endpoint creation</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Test & Feedback extension general availability</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Visual Studio subscribers automatically use their free license</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="13">[21 Sep 2016](/articles/news/2016/sep-21-team-services)</td>
            <td>Attachments live preview</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Work item type layout improvements</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Disable work item types</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Import Repository</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Markdown preview button</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Confirmation for deleting repos</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Add .gitignore during repo creation</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Verify bugs from work item</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Xcode Build task xcpretty formatting</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Publish Jenkins test and code coverage results</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Build summary for Maven and Gradle tasks</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>FindBugs and CheckStyle in Maven build tasks</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td>Deployment status widget</td>
            <td style="background:rgb(189, 214, 238);">[2017.1](https://go.microsoft.com/fwlink/?LinkId=839593)</td>
        </tr>
        <tr>
            <td rowspan="14">[2 Sep 2016](/articles/news/2016/sep-02-team-services)</td>
            <td>Custom work item types</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Work item history tab</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Managing a NuGet package’s lifecycle</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build queue tab</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Hosted build pool build agent migration</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Xamarin license step removed</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Jenkins with untrusted SSL certificates</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Apple App Store extension</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Request Feedback</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Checkstyle static analysis</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Deployment manual intervention</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Service endpoint improvements</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>SQL database deployment task</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>User lifecycle management improvements</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="22">[17 Aug 2016](/articles/news/2016/aug-17-team-services)</td>
            <td>Pull Request improvements: <br />
                Redesigned UI <br />
                Overview <br />
                Files <br />
                Updates <br />
                Comments, now with markdown and emoji <br />
                Auto-complete pull requests waiting on policies</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Clone Git repositories from your browser using Tower</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Download packages without NuGet</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Packages: Get started quickly</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Queue Jenkins jobs from builds and releases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Jenkins service hook enhancements</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Run SSH commands on remote machines from builds and releases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Create archives from builds and releases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Copy files over SSH from builds and releases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Download Jenkins artifacts to builds and releases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Use FTP or FTPS to upload files from builds and releases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Google Play Extension improvements</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Maven and Gradle tasks produce a build summary when running a SonarQube analysis</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Work item templates</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Quickly “Unfollow” work item</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Drag and drop attachments</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Assigned to Me widget</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboard permissions</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Configure test outcomes for tests across different test suites</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test Run and Test Result summary – traceability to Releases and manual test artifacts</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Unpublish extension – Removing a public extension from the Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Rate Limits – Delaying user requests to avoid outages</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="9">[29 Jul 2016](/articles/news/2016/jul-29-team-services) </td>
            <td>Git and TFVC – History view and diff view updates</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Restrict Package Management feed creation</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release management improvements – Azure deployments, release policies: <br />
                Agent queue management <br />
                Azure deployments <br />
                Policies – Soft delete releases <br />
                Policies – Retention of releases and builds <br />
                Release definition authoring improvements – linked artifacts improvements <br />
                Release – redeploy after success</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test traceability and release environments support in Test History</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory testing improvements – view unexplored work items, capture web page load data</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboard improvements</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Java PMD analysis in Gradle build task</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>User management – export users and licenses</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Backlog extension points</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="18">[7 Jul 2016](/articles/news/2016/jul-07-team-services)  </td>
            <td>Resizable WIT charts on dashboards</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Filter boards to a parent work item</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Links front and center</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test settings configuration for Kanban board</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Comment tracking for pull requests</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Browse Code Coverage reports in the web</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Maven and Gradle tasks produce a build summary when running a SonarQube analysis</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Agent queue role-based security</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Task-level time-outs</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Import/Export/Clone release definition</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Web app deployment using ARM</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Partially successful deployments</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>View and download attachments associated with releases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Github artifacts for RM</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>.NET SQL Extension</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Image action log in Web Test runner</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Order tests in Test hub</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Pick a build to test with</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="22">[17 Jun 2016](/articles/news/2016/jun-17-team-services)</td>
            <td>Git &amp; TFVC – Browsing branches</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – Ahead/behind</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – Branch picker includes “Mine”</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – Path control</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git &amp; TFVC – File type icons</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Work Items – An improved header</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Work Items – Custom states</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory Testing – Insights</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory Testing – Auto stop screen recordings</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Screen recording support in Web runner (for Chrome) </td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Bugs filed as children – Web runner / Exploratory testing extension</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test – History across branches</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test – Automated testing for SCVMM and VMWare</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release – Test status visibility</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release – Support Java PMD analysis in Maven build task</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release – Passing oauth tokens to scripts</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build – Enable path filters for Git CI triggers</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build – Updated hosted pool software</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboards – Resizable query results widget</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Third-party plugins – Jenkins plug-in to RM</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Marketplace – Publisher review responses</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Team Rooms – Build vNext support</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="1">[6 Jun 2016](https://blogs.msdn.microsoft.com/visualstudioalm/2016/06/06/visual-studio-team-services-is-in-brazil/)</td>
            <td>Brazil region for Visual Studio Team Services</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="15">[1 Jun 2016](/articles/news/2016/jun-01-team-services)</td>
            <td>Filtering in Kanban board</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Process configuration REST APIs</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboards REST APIs</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>SSH clients can connect to Git repos</td>
            <td style="background:rgb(177, 232, 179);">2015.3</td>
        </tr>
        <tr>
            <td>Redesigned Branches page</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Create and send links to specific sections of code</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>API updates for package management</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Screenshot and system info support in Chrome Web runner</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Ordering of tests in Test Hub</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Docker integration for build and release management</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>SonarQube results in pull request view</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test results trend for build</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Service hooks for release management</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>TeamCity artifacts for release management</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management Client SDK</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="19">[6 May 2016](/articles/news/2016/may-06-team-services)</td>
            <td>Email improvements</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Checkbox control</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Work Item page management</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Turning board annotations on/off</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Clear Formatting command</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Dashboard updates</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Adding attachments during manual testing</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Test plan/suite columns</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build and release summary updates</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management repository linking</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Copy, Export, and Import release definitions</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Schedule based deployments</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management REST APIs</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Simplified Release definition wizard</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>New Release Management job execution variables</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Improved build and pull request traceability</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Team Project rename permission</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Admin settings Work hub</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>UX improvements</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="17">[13 Apr 2016](/articles/news/2016/apr-13-team-services)</td>
            <td>Follow a work item</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Change work item type</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Work Item move (single or bulk)</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Kanban board live updates</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Pick lists for work Items</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Checklist improvements</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build to Line number</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Build log view supports much larger logs</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Java Build templates</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Xamarin Build Tasks</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Widget SDK: Reusable CSS and DOM templates</td>
            <td style="background:rgb(177, 232, 179);">2015.3</td>
        </tr>
        <tr>
            <td>Adding users from the team members widget</td>
            <td style="background:rgb(177, 232, 179);">2015.3</td>
        </tr>
        <tr>
            <td>Collection in the domain</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Release Management – Email release summary</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management – Dashboard widget for release definition summary</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management – Deploy based on conditions in multiple environments</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Release Management – Provision VMs or run a PS script using SCVMM extension</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="11">[24 Mar 2016](/articles/news/2016/mar-24-team-services)</td>
            <td>Commit traceability</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>View Git LFS files in the web</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Git for Windows now includes Team Services authentication by default</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Custom multiline text fields</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Test progress from your cards</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Capture screen recordings</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Queue a Run by specifying your test suite</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Configuration management in the Test Hub</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Enable build result extensions to specify order and column</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Configure status API reporting for a build definition</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Tab contribution point</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="13">[3 Mar 2016](/articles/news/2016/mar-03-team-services)</td>
            <td>View test results for each release environment</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Triggers: Deploy based on completion in multiple environments (join)</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Epic and Feature board drill-down</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Exploratory testing directly from a work item</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Data collection: Image action log</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Create test cases based on Image action log data</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Assigning configurations to test plans, test suites and test cases</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Squash merge pull requests</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Clone in IntelliJ, Android Studio, etc.</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Gated builds for Team Foundation Version Control (TFVC)</td>
            <td style="background:rgb(198, 239, 200);">2015.2</td>
        </tr>
        <tr>
            <td>Automated testing on Azure environments</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>NuGet package delist</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Office connector</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="13">[16 Feb 2016](/articles/news/2016/feb-16-team-services)</td>
            <td>Package management is now available in Europe and Australia</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Search for extensions on Visual Studio Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Work item query charts in the dashboard catalog</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Cumulative flow diagram widget</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Flexible build policy for Git</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>SonarQube Quality Gates in Build</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>RM: UI extensibility</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>SCVMM support</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Exploratory Testing improvements</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Azure SQL Database Deployment task</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Delete Test Plan</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>#mention</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts for Kanban board</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td rowspan="17">[25 Jan 2016](/articles/news/2016/jan-25-team-services)</td>
            <td>Public preview of the dashboard widget SDK</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Create branch and links to related artifacts</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Build widgets in the catalog</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Markdown widget with file from repository</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Auto-refresh dashboards</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Richer visualizations in the build summary page</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>View passed test results and file bugs in build summary page</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Test summary in build status notification email</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Support for editing tags in the bulk edit dialog</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Deleting a custom field</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Test plan improvements</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Exploratory testing improvements</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Release orchestration improvements</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>UI extensibility for release management</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Search scope selector</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Search across Git and TFVC projects</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="8">[10 Dec 2015](/articles/news/2015/dec-10-team-services)</td>
            <td>Custom work item fields</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Work item discussion</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Work item history improvements</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Deleting work items</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Dashboards edit mode</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Keyboard shortcuts</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>On-Premises support for Exploratory Testing extension:</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Scope code search using path filters</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td rowspan="7">[24 Nov 2015](/articles/news/2015/nov-24-team-services)</td>
            <td>Git and TFVC in the same team project</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Package Management build tasks</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Implement a task once for multiple platforms</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Pull Request Widget for Dashboards</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>@mention and #ID in code</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Reordering cards on boards</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Global shortcut keys</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td rowspan="7">[18 Nov 2015](/articles/news/2015/nov-18-team-services)</td>
            <td>Extensions and Marketplace</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Release Management public preview</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Package Management public preview</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Code Search public preview</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Test Results in Build</td>
            <td style="background:rgb(198, 239, 200);">[2015.2](http://go.microsoft.com/fwlink/?LinkId=615439)</td>
        </tr>
        <tr>
            <td>Exploratory Testing extension</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Test Manager extension</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="6">[30 Oct 2015](/articles/news/2015/oct-30-team-services)</td>
            <td>Dashboards</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Improved pull request experience</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Manual test iteration results</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Retention policy for test results</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reorder and re-parent tasks from the Kanban board</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>PREVIEW: New Work Item form</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="5">[8 Oct 2015](/articles/news/2015/oct-08-team-services)</td>
            <td>Azure Active Directory Group support</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>Starting with Git, made easy</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Improved commit details</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>SonarQube analysis from a Maven build task</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>PREVIEW: New Work Item form</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td rowspan="7">[18 Sep 2015](/articles/news/2015/sep-18-team-services)</td>
            <td>Inline tasks on the Kanban board</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Query and display of Kanban fields</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Multi-select items on the backlog</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Branch policy to require linked work items</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Export test outcomes</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Work item trend and rollup reporting in Power BI</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td>Support for publishing xUnit results</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="4">[26 Aug 2015](/articles/news/2015/aug-26-team-services)</td>
            <td>Rename columns in place</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Choosing users for capacity planning</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Burndown with available capacity</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>SonarQube analysis build tasks</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="4">[7 Aug 2015](/articles/news/2015/aug-07-team-services)</td>
            <td>Multi-select items on the product backlog</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reorder cards when changing columns</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Color tags and titles on your cards</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Libraries for integrating with VSTS now available at nuget.org</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="1">[22 Jul 2015](http://blogs.msdn.com/b/visualstudioalm/archive/2015/07/22/reporting-on-work-items-with-power-bi.aspx)</td>
            <td>Power BI reporting on Work Item data</td>
            <td style="background:rgb(232, 232, 232);">Future</td>
        </tr>
        <tr>
            <td rowspan="7">[17 Jul 2015](/articles/news/2015/jul-17-team-services)</td>
            <td>Multiple activities per team member</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Configure settings directly from backlogs/boards</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Hide empty fields on cards</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Card coloring on Taskboard</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Drag any item to an iteration from anywhere</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Build your projects hosted in GitHub</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td>New VSTS integrations</td>
            <td style="background:rgb(232, 232, 232);">--</td>
        </tr>
        <tr>
            <td rowspan="3">[7 Jul 2015](/articles/news/2015/jul-07-team-services)</td>
            <td>Card coloring on Kanban board</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Personal access tokens</td>
            <td style="background:rgb(240, 245, 251);">[2017](http://go.microsoft.com/fwlink/?LinkId=831912)</td>
        </tr>
        <tr>
            <td>Adding work directly to a sprint</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="4">[3 Jun 2015](/articles/news/2015/jun-03-team-services)</td>
            <td>Kanban swim lanes</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>#Mention work items</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Automated testing in Build vNext</td>
            <td style="background:rgb(217, 247, 219);">[2015.1](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Team settings API</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="7">[15 May 2015](/articles/news/2015/may-15-team-services)</td>
            <td>Build vNext</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Backlog navigation update</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Opt-in to portfolio backlogs</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Improved SAFe support</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban collapsed columns</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Git branch policies</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Power BI &amp; VSO</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[11 May 2015](/articles/news/2015/may-11-team-services)</td>
            <td>Application Insights: <br />
                iOS and Android support <br />
                Performance counters for Java applications <br />
                Unhandled exceptions in Java apps <br />
                Drag-across to select a time range</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[8 May 2015](http://blogs.msdn.com/b/bharry/archive/2015/05/10/vs-online-hosted-in-australia.aspx)</td>
            <td>Australia region for Visual Studio Team Services</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[29 April 2015](http://azure.microsoft.com/blog/2015/04/29/announcing-application-insights-public-preview-2/)</td>
            <td>Application Insights Public Commercial Preview</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[29 April 2015](https://www.visualstudio.com/integrate/extensions/overview)</td>
            <td>Extensions</td>
            <td style="background:rgb(198, 239, 200);">2015.2</td>
        </tr>
        <tr>
            <td rowspan="4">[27 Apr 2015](/articles/news/2015/apr-27-team-services)</td>
            <td>Adding fields to cards</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban board filtering</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Card options on the Taskboard</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Account restore</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[24 Apr 2015](/articles/news/2015/apr-24-team-services)</td>
            <td>Team Project Rename</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[22 Apr 2015](/articles/news/2015/apr-22-team-services)</td>
            <td>Application Insights: <br />
                Synthetic data filtering <br />
                New usage experience for ASP.NET, Java and other applications <br />
                Daily Active User calculations</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[17 Apr 2015](http://blogs.msdn.com/b/visualstudioalm/archive/2015/04/17/general-availability-of-codelens-in-visual-studio-online.aspx)</td>
            <td>CodeLens General Availability on Visual Studio Team Services</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="4">[10 Apr 2015](/articles/news/2015/apr-10-team-services)</td>
            <td>Configure cards</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Markdown editing for definition of done</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>CFD options</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Web history view for Git projects</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[27 Mar 2015](/articles/news/2015/mar-27-team-services)</td>
            <td>Application Insights: Save search page, pause export and export on alert fail</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="7">[10 Mar 2015](/articles/news/2015/mar-10-team-services)</td>
            <td>Current iteration query token</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reordering on the Kanban board</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban definition of done</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Responsive card sizes</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Bugs on the Taskboard</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Syntax highlight for XML, Sass, Objective-C, R</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>CodeLens for accounts in West Europe</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[9 Mar 2015](http://azure.microsoft.com/en-us/documentation/articles/app-insights-java-get-started/)</td>
            <td>Application Insights support for Java</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="4">[18 Feb 2015](/articles/news/2015/feb-18-team-services)</td>
            <td>Adding and editing directly from the board</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Split columns on the Kanban board</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Assign multiple people to test suites</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Application Insights in the Azure Preview Portal</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[13 Feb 2015](http://blogs.msdn.com/b/visualstudioalm/archive/2015/02/13/announcing-limited-preview-for-visual-studio-online-code-search.aspx)</td>
            <td>Limited preview for Code Search</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[29 Jan 2015](http://azure.microsoft.com/en-us/updates/application-insights-support-for-windows-phone-and-windows-store/)</td>
            <td>Application Insights support for Windows Phone and Windows Store Applications</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="4">[27 Jan 2015](/articles/news/2015/jan-27-team-services)</td>
            <td>Basic license upgraded</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Reordering on the Taskboard</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Unparented Tasks on the Taskboard</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Inline editing on the Kanban board</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[15 Jan 2015](http://blogs.msdn.com/b/bharry/archive/2015/01/15/visual-studio-online-iso-27001-certification-and-european-model-clauses.aspx)</td>
            <td>VS Online ISO 27001 Certification</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="6">[17 Dec 2014](/articles/news/2014/dec-17-team-services)</td>
            <td>Quick code editing</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Filtering on backlogs and queries</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Sprint backlog and task board improvements</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>New integrations: Slack and Azuqua</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Preview APIs for adding and updating files in source control</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>CodeLens for Visual Studio Team Services</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="2">11 Dec 2014</td>
            <td>[Application Insights Status Monitor and SDK updates](http://azure.microsoft.com/en-us/updates/application-insights-status-monitor-and-sdk-updated/)</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[Application Insights includes telemetry export and segmentation editing](http://azure.microsoft.com/en-us/updates/application-insights-adds-telemetry-export-and-segmentation-chart-editing/)</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="5">[2 Dec 2014](/articles/news/2014/dec-02-team-services)</td>
            <td>Identity control and avatars</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Pull Request improvements</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Taskboard changes</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Kanban board persisted column headers</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Sharing personal queries</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>[12 Nov 2014](/articles/news/2014/dec-02-team-services#nov12)</td>
            <td>Release Management Preview as VSTS service</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="7">[4 Nov 2014](/articles/news/2014/nov-04-team-services)</td>
            <td>Bugs on the backlog</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Test execution charts</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Recent test results</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Preview Markdown and HTML files in Code Explorer</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Browse link dialog</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>REST batch support</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Third-party OAuth scopes</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td rowspan="3">[28 Oct 2014](/articles/news/2014/oct-28-team-services)</td>
            <td>European Datacenter</td>
            <td>--</td>
        </tr>
        <tr>
            <td>VSTS REST API version 1.0 is here</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Service hooks is out of preview</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="2">[14 Oct 2014](/articles/news/2014/oct-14-team-services)</td>
            <td>Test artifacts as work items</td>
            <td style="background:rgb(216, 194, 239);">[2013.3](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Copy and paste query results</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="3">[23 Sep 2014](/articles/news/2014/sep-23-team-services)</td>
            <td>Maximizing text area fields</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Navigating to links</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Work item performance improvements</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="6">[4 Sep 2014](/articles/news/2014/sep-04-team-services)</td>
            <td>Work Item query improvements</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Quick search through tree controls</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Longer trend charts</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Test Cases related to Test Suites</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>WIT REST API v1.2</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Event and resource versioning within service hooks</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[27 Aug 2014](/articles/news/2014/aug-27-team-services)</td>
            <td>A license for Stakeholders</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="2">[18 Aug 2014](/articles/news/2014/aug-18-team-services)</td>
            <td>Project Welcome pages</td>
            <td style="background:rgb(232, 255, 234);">[2015](http://go.microsoft.com/fwlink/?LinkId=533008)</td>
        </tr>
        <tr>
            <td>Tagging support in the Test Hub</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="5">[21 Jul 2014](/articles/news/2014/jul-21-team-services)</td>
            <td>Using corporate identities with existing accounts</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Viewing existing projects in the Azure Preview Portal</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Trend charts + aggregation</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Test Hub added to the Advanced License</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Deleting your account</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="3">[1 Jul 2014](/articles/news/2014/jul-01-team-services)</td>
            <td>Hiding work in progress on the backlog</td>
            <td style="background:rgb(216, 194, 239);">[2013.3](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Full Screen on the backlog and boards</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>Move to position on the backlog</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td>[10 Jun 2014](/articles/news/2014/jun-10-team-services)</td>
            <td>Pull Requests</td>
            <td style="background:rgb(231, 179, 249);">[2013.4](http://go.microsoft.com/fwlink/?LinkId=510319)</td>
        </tr>
        <tr>
            <td rowspan="3">[20 May 2014](/articles/news/2014/may-20-team-services)</td>
            <td>Using corporate identities</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Copy/Paste shared parameter data between VS Online and Excel</td>
            <td style="background:rgb(216, 194, 239);">[2013.3](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>End of data export period</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="2">[12 May 2014](/articles/news/2014/may-12-team-services)</td>
            <td>Integrate with Visual Studio Team Services</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Service Migration with OpsHub</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="3">[3 Apr 2014](/articles/news/2014/apr-03-team-services)</td>
            <td>General Availability of Visual Studio Team Services</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Application Insights Limited Preview</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Shared Parameters for Test Cases</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="2">[18 Mar 2014](/articles/news/2014/mar-18-team-services)</td>
            <td>Getting started with Application Insights</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Search across your application trace logs</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="3">[28 Feb 2014](/articles/news/2014/feb-28-team-services)</td>
            <td>Build support for Java code managed in Git</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Java JDK, Ant, and Maven libraries preinstalled in hosted build</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Maven support for TF version control projects</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="2">[10 Feb 2014](/articles/news/2014/feb-10-team-services)</td>
            <td>Exporting test artifacts</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>New “create tags” permission</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="3">[22 Jan 2014](/articles/news/2014/jan-22-team-services)</td>
            <td>Querying tags</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Removing weekends from the Burndown</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Configurable CFD dates</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="3">[11 Dec 2013](/articles/news/2013/dec-11-team-services)</td>
            <td>Application Insights – Response Stacked Distribution</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Application Insights – Windows Store App support</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Asynchronous backlogs</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="3">[13 Nov 2013](/articles/news/2013/nov-13-team-services)</td>
            <td>Commercial preview</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Application Insights limited preview</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Live editing of Windows Azure sites</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[8 Nov 2013](/articles/news/2013/nov-08-team-services)</td>
            <td>Work item chart pinning</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>[21 Oct 2013](/articles/news/2013/oct-21-team-services)</td>
            <td>New account and project pages</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>[17 Oct 2013](/articles/news/2013/oct-17-team-services)</td>
            <td>Build images updated to VS 2013</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="3">[30 Sep 2013](/articles/news/2013/sep-30-team-services)</td>
            <td>New languages supported for code syntax highlighting</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Color picking in charts</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td>Column options for the test case grid view</td>
            <td style="background:rgb(229, 212, 247);">[2013.2](http://go.microsoft.com/fwlink/?LinkId=392762)</td>
        </tr>
        <tr>
            <td rowspan="4">[9 Sep 2013](/articles/news/2013/sep-09-team-services)</td>
            <td>Work item charts</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Bulk edit of test cases</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Delete a team project</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Work items from code discussion</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>[19 Aug 2013](/articles/news/2013/aug-19-team-services)</td>
            <td>Improved code commenting</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="3">[29 Jul 2013](/articles/news/2013/jul-29-team-services)</td>
            <td>Improved permission management for Git repos</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Team room Git push events</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Deleting team rooms</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="2" style="text-align:left;">[10 Jul 2013](/articles/news/2013/jul-10-team-services)</td>
            <td>Backlog mapping</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Team permission changes</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="3">[26 Jun 2013](/articles/news/2013/jun-26-team-services)</td>
            <td>Windows 8.1 support in hosted build</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Paste images into work items in the web</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Open Microsoft Test Runner from web</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="3">[19 Jun 2013](/articles/news/2013/jun-19-team-services)</td>
            <td>Agile Portfolio Management updates – view filter and quick decompose</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Open MTM from web</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Admin panel color change</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="5">[3 Jun 2013](/articles/news/2013/jun-03-team-services)</td>
            <td>Agile Portfolio Management</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Lightweight code commenting</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Team Room</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Create/modify test plans through Web UI</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Cloud load testing</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="3">[28 May 2013](/articles/news/2013/may-28-team-services)</td>
            <td>Build IaaS</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Git alerts</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Backlog updates – name changed to "backlogs" and now backlogs show all items until they reach the completed state</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="4">[13 May 2013](/articles/news/2013/may-13-team-services)</td>
            <td>Work item colors based on process template settings</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Usability updates – icon updates and sentence casing</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Navigation updates in Web UI, including ability to view past iterations</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Git multi-repo support</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="2">[22 Mar 2013](/articles/news/2013/mar-22-team-services)</td>
            <td>Branches view for Git</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>TCM Improvements – bulk edit test step pass/fail, double click test step reorder, hover over inline images</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="4">[4 Mar 2013](/articles/news/2013/mar-04-team-services)</td>
            <td>Customizable Kanban columns</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>TCM improvements – edit test steps when running tests</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Annotate/Blame for version control</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Scheduled builds for Git-based projects</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td rowspan="4">[11 Feb 2013](/articles/news/2013/feb-11-team-services)</td>
            <td>Continuous Integration for Git</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>TCM improvements – view test step attachments when running tests, add attachments when running tests, pause and resume tests in Test Runner</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>WIT tagging cleanup for unused tags</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Download as Zip for version control</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="3">[30 Jan 2013](/articles/news/2013/jan-30-team-services)</td>
            <td>Work item tagging</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Git support</td>
            <td style="background:rgb(243, 232, 255);">[2013](http://go.microsoft.com/fwlink/p/?LinkId=306566)</td>
        </tr>
        <tr>
            <td>Test Hub in Web UI</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>[21 Jan 2013](/articles/news/2013/jan-21-team-services)</td>
            <td>Changeset context menu in Web UI</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>[9 Jan 2013](/articles/news/2013/jan-09-team-services)</td>
            <td>Account rename of Team Foundation Service account</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="5">[7 Jan 2013](/articles/news/2013/jan-07-team-services)</td>
            <td>Email work items from backlog</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Search for changesets by ID in Web UI</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Full screen mode for code viewing</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Inline diff of images in version control</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Collapsible left pane in all left panels in Web UI</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="3">[10 Dec 2012](/articles/news/2012/dec-10-team-services)</td>
            <td>Renamed Source to Code in Web UI hub</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Code Explorer updates in Web UI</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Hosted build updates for Azure SDK 1.8, TypeScript 0.8.1, and VS 2012 Update 1</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="2">[19 Nov 2012](/articles/news/2012/nov-19-team-services)</td>
            <td>Send work items in email from TFS web access</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Build file counts and sizes in summary reports</td>
            <td style="background:rgb(189, 214, 238);">[2012.2](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>[31 Oct 2012](/articles/news/2012/oct-31-team-services)</td>
            <td>General availability of Team Foundation Service</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[29 Oct 2012](/articles/news/2012/oct-29-team-services)</td>
            <td>Build drops</td>
            <td>--</td>
        </tr>
        <tr>
            <td>[8 Oct 2012](/articles/news/2012/oct-08-team-services)</td>
            <td>400 character server paths for version control</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="3">[17 Sep 2012](/articles/news/2012/sep-17-team-services)</td>
            <td>Drag/drop in sprint planning to assign to person or activity</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Web usability improvements (tabs and UX modified, collapse left pane in work items)</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Process template updates to Agile 6.1 and Scrum 2.1</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="4">[27 Aug 2012](/articles/news/2012/aug-27-team-services)</td>
            <td>Improved source browsing, viewing, and searching</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Improved source "diff"</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Hosted builds of SharePoint components</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Basic authentication support</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="3">[13 Aug 2012](/articles/news/2012/aug-13-team-services)</td>
            <td>Kanban board</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Cumulative Flow Diagram</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>WIP Limits</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td rowspan="2">[6 Aug 2012](/articles/news/2012/aug-06-team-services)</td>
            <td>Drag/drop in task board to move tasks between people and stories</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
        <tr>
            <td>Azure continuous deployment summary report</td>
            <td>[2012.1](https://www.microsoft.com/en-us/download/details.aspx?id=39305)</td>
        </tr>
    </tbody>
</table>

###Server Build Numbers

<table>
<thead>
        <tr>
          <th>Release</th>
          <th>Build</th>
        </tr>
</thead>
<tbody>
		<tr>
		  <td style="background:rgb(155, 192, 230);">2017.2</td>
		  <td>--</td>
		</tr>
        <tr>
          <td style="background:rgb(189, 214, 238);">2017.1</td>
          <td>15.112.26307.00</td>
        </tr>
        <tr>
          <td style="background:rgb(240, 245, 251);">2017 RTM</td>
          <td>15.105.25910.00</td>
        </tr>
        <tr>
          <td style="background:rgb(177, 232, 179);">2015.3</td>
          <td>14.102.25423.00</td>
        </tr>
        <tr>
          <td style="background:rgb(198, 239, 200);">2015.2</td>
          <td>14.95.25122.00</td>
        </tr>
        <tr />
        <tr>
          <td style="background:rgb(217, 247, 219);">2015.1</td>
          <td>14.0.24720.00</td>
        </tr>
        <tr>
          <td style="background:rgb(232, 255, 234);">2015 RTM</td>
          <td>14.0.23128.00*</td>
        </tr>
        <tr>
          <td style="background:rgb(231, 179, 249);">2013.4</td>
          <td>12.0.31101.00</td>
        </tr>
        <tr>
          <td style="background:rgb(216, 194, 239);">2013.3</td>
          <td>12.0.30723.00</td>
        </tr>
        <tr>
          <td style="background:rgb(229, 212, 247);">2013.2</td>
          <td>12.0.30324.00</td>
        </tr>
        <tr>
          <td style="background:rgb(243, 232, 255);">2013 RTM</td>
          <td>12.0.21005.01</td>
        </tr>
        <tr>
          <td style="background:rgb(155, 192, 230);">2012.3</td>
          <td>11.0.60610.01</td>
        </tr>
        <tr>
          <td style="background:rgb(189, 214, 238);">2012.2</td>
          <td>11.0.60315.01</td>
        </tr>
        <tr>
          <td>2012.1</td>
          <td>11.0.51106.01</td>
        </tr>
        <tr>
          <td style="background:rgb(240, 245, 251);">2012 RTM</td>
          <td>11.0.50727.01</td>
        </tr>
      </tbody>
    </table>
* TFS 2015 RTM has multiple build numbers, due to the componentized nature of its build and packaging process. The number of the installer, which will show up in Add/Remove Programs, is 14.0.23129.01. The number of the majority of the assemblies, which will show up in the TFS Administration Console, is 14.0.23128.00.