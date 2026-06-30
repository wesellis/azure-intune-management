# Azure Intune Management Scripts

A collection of PowerShell scripts for managing Azure Intune devices and policies.

[![PowerShell](https://img.shields.io/badge/PowerShell-5.1+-5391FE?style=flat-square&logo=powershell&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/wesellis/azure-intune-management?style=flat-square)](https://github.com/wesellis/azure-intune-management/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/wesellis/azure-intune-management?style=flat-square)](https://github.com/wesellis/azure-intune-management/commits)

```bash
git clone https://github.com/wesellis/azure-intune-management.git
cd azure-intune-management
```

## What is This?

Personal collection of PowerShell scripts for working with Microsoft Intune and Azure device management. Automates common tasks like device management, policy deployment, and reporting.

## What's Included

### Azure Authentication
- Single sign-on checking

### Azure Visualizations
- Resource group visualization tools
- Export tools for mapping Azure resources

### Intune Management
- **Device Management**: Scripts for device configuration and management
- **Application Management**: App deployment and category management
- **Task Management**: Scheduled task automation
- **Policy Reporting**: Generate reports on policies and assignments

### Windows Image Creation
- Hyper-V and WDS installation scripts

## Prerequisites

- PowerShell 5.1 or higher
- Azure AD PowerShell module
- Microsoft Graph Intune module (for some scripts)
- Appropriate permissions in your Azure/Intune tenant

## Installation

```powershell
Install-Module -Name Microsoft.Graph.Intune
Install-Module -Name AzureAD
```

## Usage

Each script is standalone. Review contents before running.

```powershell
.\Intune\Device-Management\Intune.GraphAPI.Modern.ps1
```

**Important**: Always test in a non-production environment first.

## Project Structure

```
.
├── Azure Authentication/     # Azure auth-related scripts
├── Azure Visualizations/     # Resource visualization tools
├── Intune/                   # Intune management scripts
│   ├── Device-Management/
│   ├── PowerShell-Scripts/
│   └── Task-Management/
└── Windows Image Creation/   # Image creation utilities
```

## Disclaimer

Scripts are provided as-is. Review and test before production use.

## License

MIT License - See [LICENSE](LICENSE) for details.

---

**Author:** Wesley Ellis
