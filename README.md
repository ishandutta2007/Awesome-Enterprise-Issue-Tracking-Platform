# Awesome-Enterprise-Issue-Tracking-Platform

# Awesome Enterprise Issue Tracking Platform

> A curated list of top Enterprise Issue Tracking platforms — both SaaS/Hosted commercial solutions and open-source alternatives for self-hosted bug tracking, project management, and agile delivery.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Jira Data Center](#jira-data-center)
  - [Azure DevOps Server](#azure-devops-server)
  - [GitLab Self-Managed](#gitlab-self-managed)
  - [GitHub Enterprise Server](#github-enterprise-server)
  - [Broadcom Rally](#broadcom-rally)
  - [ServiceNow ITBM (SPM)](#servicenow-itbm-spm)
  - [Planview](#planview)
- [Open-Source Software](#-open-source-software)
  - [OpenProject](#openproject)
  - [Redmine](#redmine)
  - [Bugzilla](#bugzilla)
  - [MantisBT](#mantisbt)
  - [Taiga](#taiga)
  - [Plane](#plane)
  - [Request Tracker (RT)](#request-tracker-rt)
  - [Zammad](#zammad)
  - [Phorge](#phorge)
  - [Trac](#trac)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, enterprise-grade Issue Tracking platforms. These are not open-source but are included as reference points for feature comparison.

### Jira Data Center
**Type:** Enterprise agile issue tracking  
Atlassian's self-managed enterprise offering for issue tracking, agile planning, and software delivery. Data Center adds high availability clustering, SAML/OIDC SSO, zero-downtime upgrades, CDN support, and Kubernetes deployment options over the Server edition [citation:1][citation:10]. Core features include customizable workflows, Scrum/Kanban boards, Advanced Roadmaps for cross-team planning, and Automation for Jira natively included [citation:1]. Designed for organizations that require on-premises control and scale beyond what Cloud offers.  
**Best for:** Large enterprises requiring self-managed deployment, high availability, and deep agile planning capabilities at scale.

### Azure DevOps Server
**Type:** On-premises DevOps and work item tracking  
Microsoft's self-hosted platform for the full DevOps lifecycle, including Azure Boards for work item tracking. Supports Agile, Scrum, CMMI, and Basic processes with customizable work item types (User Stories, Bugs, Tasks, Features, Epics) [citation:2][citation:11]. Work items support area/iteration paths, tags, templates, and hierarchical linking. Integrates natively with Azure Repos, Pipelines, and Test Plans. Query-based reporting and dashboards provide progress visibility [citation:11].  
**Best for:** Microsoft-centric organizations needing on-premises DevOps with integrated work tracking, source control, and CI/CD.

### GitLab Self-Managed
**Type:** Integrated DevSecOps with issue tracking  
GitLab's self-hosted edition includes Issues as a core feature, tightly integrated with merge requests, CI/CD, and security scanning. Issues support assignees, due dates, health status, labels, epics, boards with WIP limits, and threaded discussions [citation:3][citation:12]. Issue boards allow drag-and-drop workflow management with configurable WIP limits by item count or weight [citation:12]. Integrates with external tools including Jira, Zoom, and email [citation:3].  
**Best for:** Teams wanting issue tracking natively integrated with a complete DevSecOps platform in a single self-managed application.

### GitHub Enterprise Server
**Type:** Self-hosted GitHub with Issues and Projects  
GitHub's self-managed enterprise offering includes Issues and GitHub Projects for work tracking. Version 3.21 added a hierarchy view for GitHub Projects, enabling full issue hierarchy visibility in table views [citation:4]. Supports organization custom properties for targeting enterprise rulesets. Issues integrate with pull requests, Actions, and security features including secret scanning and code scanning [citation:4].  
**Best for:** Organizations standardized on GitHub wanting self-hosted issue tracking integrated with their existing repository and CI/CD workflows.

### Broadcom Rally
**Type:** Enterprise agile planning and portfolio management  
Broadcom's enterprise agile platform for scaling agile across teams and portfolios. Supports project and portfolio management, issue tracking, and value stream management. Integrates bidirectionally with requirements management, ALM, ITSM/CRM, and build/version control tools through ValueOps ConnectALL [citation:14]. Provides real-time visibility across product management, development, and QA teams.  
**Best for:** Large enterprises practicing scaled agile needing portfolio-level planning and cross-tool integration.

### ServiceNow ITBM (SPM)
**Type:** Strategic portfolio management  
ServiceNow's Strategic Portfolio Management (formerly ITBM) provides project and portfolio management, demand management, and resource planning. Enables task assignment aligned with priorities, integrated project/resource management, and faster issue resolution through strategic portfolio oversight [citation:6]. Supports demand tasks, effort/cost tracking, and portfolio-level rollups.  
**Best for:** Organizations already on ServiceNow wanting issue and project tracking integrated with ITSM and strategic planning.

### Planview
**Type:** Portfolio and work management  
Planview provides portfolio management and work management capabilities including Logbook for risk and issue tracking. Logbook offers customizable attributes, OData integration for reporting, REST APIs, and configurable workflows (roadmap) [citation:7]. Integrates with Planview Portfolios and ProjectPlace. Supports import/export of RAID items.  
**Best for:** Enterprises needing portfolio-level governance with issue/risk tracking integrated into strategic planning.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Issue Tracking platforms. All listed projects offer source code you can deploy on your own infrastructure.

### OpenProject
**Stack:** Ruby on Rails / PostgreSQL | **License:** GPL-3.0  
A full-featured open-source project management suite with issue tracking, Gantt charts, agile boards, and wiki. Rated 9.3 by LinuxLinks among open-source issue trackers [citation:8]. Supports work packages (issues), customizable workflows, role-based permissions, and project timelines. Includes meeting management, budgeting, and documentation modules.  
**Best for:** Organizations wanting a comprehensive project management suite with issue tracking, Gantt planning, and agile boards in one platform.

### Redmine
**Stack:** Ruby on Rails / MySQL/PostgreSQL/SQLite | **License:** GPL-2.0  
One of the most established open-source issue trackers, with a two-decade ecosystem of plugins. Supports issue tracking, subprojects, roles and permissions, time tracking, wikis, forums, and Gantt charts [citation:9]. Battle-tested and endlessly extensible, though the interface is dated compared to modern alternatives. Kanban boards, OIDC login, and most modern conveniences come from third-party plugins [citation:9].  
**Best for:** Teams comfortable assembling and maintaining a plugin stack, or organizations already running Redmine.

### Bugzilla
**Stack:** Perl / MySQL/PostgreSQL/Oracle | **License:** MPL-2.0  
A mature, web-based bug tracking system used by Mozilla and many open-source projects. Provides advanced search capabilities, customizable workflows, and fine-grained permissions. Rated 7.5 by LinuxLinks [citation:8]. Focused specifically on defect tracking rather than broader project management.  
**Best for:** Software projects needing a dedicated, proven bug tracking system with advanced querying.

### MantisBT
**Stack:** PHP / MySQL | **License:** GPL-2.0  
A PHP-based issue tracker with a straightforward interface and core features: issue creation, assignment, status tracking, and reporting. Rated 8.2 by LinuxLinks [citation:8]. Simpler than enterprise tools but reliable and easy to deploy on standard LAMP hosting.  
**Best for:** Small to mid-sized teams wanting a no-frills, PHP-based issue tracker.

### Taiga
**Stack:** Python / Django | **License:** MPL-2.0  
An agile-focused project management tool organized around Scrum and Kanban. Supports sprints, story points, burndown charts, epics, and issue tracking [citation:9]. Self-hostable under MPL-2.0. The methodology is baked in—if you run Scrum properly, it supports that better than general-purpose tools [citation:9].  
**Best for:** Teams committed to Scrum wanting sprint mechanics as first-class features alongside issue tracking.

### Plane
**Stack:** (Check repository) | **License:** Open Source  
A modern project management tool for issues, cycles, and roadmaps. Rated 8.6 by LinuxLinks among open-source issue trackers [citation:8]. Positioned as a contemporary alternative with a cleaner interface than legacy tools.  
**Best for:** Teams wanting a modern, visually clean issue tracking and project management experience.

### Request Tracker (RT)
**Stack:** Perl / MySQL/PostgreSQL/Oracle/SQLite | **License:** GPL-2.0  
A mature, enterprise-grade issue tracking system with email-driven workflows and granular queue-level permissions. Rated 8.2 by LinuxLinks [citation:8]. Used by universities, ISPs, and IT operations teams requiring detailed rights management and full change history.  
**Best for:** Organizations needing email-centric ticketing with fine-grained queue permissions and audit trails.

### Zammad
**Stack:** Ruby on Rails / PostgreSQL | **License:** AGPL-3.0  
A web-based open-source helpdesk and customer support system with ticketing, knowledge base, and multi-channel intake. Rated 9.2 by LinuxLinks among issue trackers [citation:8]. While oriented toward customer support rather than software issue tracking, its ticketing capabilities suit help desk and service workflows.  
**Best for:** Teams needing customer support ticketing rather than software defect tracking.

### Phorge
**Stack:** PHP | **License:** Open Source  
A community-maintained fork of Phabricator, offering issue tracking alongside code review, repository browsing, and wiki capabilities. Rated 5.6 by LinuxLinks [citation:8]. Suited for teams wanting an integrated development toolkit.  
**Best for:** Teams wanting a Phabricator-style integrated development environment with issue tracking and code review.

### Trac
**Stack:** Python | **License:** BSD  
An enhanced wiki and issue tracking system for software development projects. Rated 7.0 by LinuxLinks [citation:8]. Tightly integrates with version control systems (Subversion, Git) to link issues to commits. Simpler and lighter than modern alternatives.  
**Best for:** Small software teams wanting lightweight issue tracking tightly coupled to version control.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Self-Hosted | Agile Boards | Best For |
|----------|---------|-------|-------------|--------------|----------|
| **Jira Data Center** | Proprietary | Java | ✅ | ✅ Scrum/Kanban | Enterprise agile at scale |
| **Azure DevOps Server** | Proprietary | .NET | ✅ | ✅ Boards | Microsoft DevOps stack |
| **GitLab Self-Managed** | Proprietary | Ruby | ✅ | ✅ Issue Boards | Integrated DevSecOps |
| **GitHub Enterprise Server** | Proprietary | Ruby/Go | ✅ | ✅ Projects | GitHub-centric orgs |
| **Broadcom Rally** | Proprietary | Cloud | ❌ | ✅ | Scaled agile portfolios |
| **ServiceNow ITBM** | Proprietary | Cloud | ❌ | Limited | ServiceNow + SPM |
| **Planview** | Proprietary | Cloud | ❌ | Limited | Portfolio governance |
| **OpenProject** | GPL-3.0 | Ruby/Rails | ✅ | ✅ | Full PM suite + issues |
| **Redmine** | GPL-2.0 | Ruby/Rails | ✅ | Via plugins | Plugin ecosystem |
| **Bugzilla** | MPL-2.0 | Perl | ✅ | ❌ | Dedicated bug tracking |
| **MantisBT** | GPL-2.0 | PHP | ✅ | ❌ | Simple PHP tracker |
| **Taiga** | MPL-2.0 | Python/Django | ✅ | ✅ Scrum/Kanban | Scrum-first teams |
| **Plane** | Open Source | (Check) | ✅ | ✅ | Modern issue tracking |
| **Request Tracker** | GPL-2.0 | Perl | ✅ | ❌ | Email-centric ticketing |
| **Zammad** | AGPL-3.0 | Ruby/Rails | ✅ | ❌ | Customer support ticketing |
| **Phorge** | Open Source | PHP | ✅ | ❌ | Integrated dev toolkit |
| **Trac** | BSD | Python | ✅ | ❌ | Lightweight + VCS-linked |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Enterprise Issue Tracking platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
