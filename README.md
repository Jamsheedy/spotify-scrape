# Azure Synapse Analytics Repository

This repo contains a collection of Azure Synapse pipelines, dataflows, and helper scripts—organized into four distinct sub-projects:

1. **appserver**  
2. **clash-of-clans-warehouse** _(decommissioned)_  
3. **premtracker**  
4. **spotifyscrape**  

---

## Table of Contents

1. [Projects](#projects)
---

## Projects

### 1. appserver  
A proof-of-concept that lets your Synapse Pipeline invoke Python-based applications hosted on local Flask server.  
- **Trigger & Orchestrate** calls via Web Activity  
- **Self-Hosted Integration Runtime** runs your web‐scraping scripts on-prem or in your own VM  
- Leverages Synapse monitoring & logging while keeping cloud costs minimal  

### 2. clash-of-clans-warehouse (Decommissioned)  
An initial ETL pipeline for ingesting Clash of Clans clan & player data via the [Clash of Clans API](https://developer.clashofclans.com/#/).  
> **Note:** This project has been decommissioned—kept here for reference only.

### 3. premtracker  
Daily ETL that scrapes the Premier League table from BBC Sport and tracks standings over time.  
- Source: https://www.bbc.com/sport/football/premier-league/table  
- Outputs historical standings for use in analytics & dashboards  
- Visualization created through Looker Studio:  
  https://lookerstudio.google.com/reporting/6c5173fc-bc48-44a3-85cc-f5565b87cb21

### 4. spotifyscrape  
ETL pipelines that log usage on a Spotify Family plan to help you track listening patterns and calculate quarterly billing.
