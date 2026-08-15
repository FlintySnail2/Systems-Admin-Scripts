# Systems Administration Scripts

A collection of PowerShell and Windows automation scripts developed for common systems administration, endpoint management and Microsoft 365 administration tasks.

The repository contains small, focused utilities rather than a single deployment framework.

## Areas Covered

### Active Directory

Scripts for querying and managing Active Directory objects.

- Query and remove security group memberships for users

### Endpoint Management

Scripts for common endpoint administration and maintenance tasks.

- Adobe configuration
- Windows component store cleanup
- N-able cache cleanup

### Exchange Online

PowerShell utilities for querying Microsoft 365 / Exchange Online objects.

- Query mail-enabled groups for a user
- Query mailboxes associated with a user

### Utilities

Small Windows administration utilities.

- Microsoft 365 / Office administration helpers

### Windows Repair

Scripts for troubleshooting and repairing Windows Update and related Windows issues.

Some scripts are retained for legacy Windows versions and are clearly identified where applicable.

## Requirements

Requirements vary by script.

Common requirements include:

- Windows PowerShell or PowerShell 7
- Administrative privileges
- Appropriate Microsoft 365 / Exchange Online permissions
- Active Directory RSAT tools where applicable
- Network connectivity to required services

Review each script before execution to determine its specific requirements.

## Usage

Scripts are intentionally kept independent and focused on specific administrative tasks.

Example:

```powershell
.\QueryMailboxesForUser.ps1
