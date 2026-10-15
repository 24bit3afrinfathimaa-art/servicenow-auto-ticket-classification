# ServiceNow Auto Ticket Classification Flow

## Overview
Automated flow built in ServiceNow Flow Designer to evaluate incoming Incident records and update category details dynamically based on short description triggers.

## Key Features
- **Trigger:** Incident Created
- **Condition:** Short Description contains Network/VPN keywords
- **Action:** Update Incident Record Category to `Network`

## How to Import
1. Download the `sys_remote_update_set_...xml` file from this repository.
2. In ServiceNow, navigate to **Retrieved Update Sets**.
3. Click **Import Update Set from XML** and upload the file.
4. Preview and Commit the Update Set.
