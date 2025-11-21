# GitHub Profile Analytics - Power BI Dashboard

This repository contains a simple and fully automated Power BI dashboard designed to display dynamic analytics from my GitHub profile. The goal of this project was to build a cloud-based solution that updates itself without any manual intervention.

---

## 📊 Dashboard Overview

The dashboard presents:

- **Profile summary** (name, bio, location, links)
- **Account creation date**
- **Followers and following**
- **Repository statistics** (total repositories, forks)
- **Latest commit date**
- **Recent pull request info**
- **Programming languages distribution**
- **Latest repositories table**, including:
  - Size  
  - Creation date  
  - Fork count  
  - Open issues  

A **mobile version** of the report is also included to ensure a smooth experience across devices.

The layout intentionally includes some empty space for future expansion.

---

## 🔌 Technologies & Integrations

- **GitHub REST API**
- **Fine-grained Personal Access Token (PAT)**
- **Power BI Desktop & Power BI Service**
- **Automatic Scheduled Refresh in the Cloud**
- **Custom JSON Theme**
- **Custom PNG Background**

All fields are **dynamic**, fed directly by the API.

---

## ⚙️ How It Works

- Connects to the GitHub API using a fine-grained PAT  
- Retrieves live profile and repository data  
- Loads data into the Power BI service  
- Performs **automatic scheduled refreshes**  
- The semantic model is fully managed inside Power BI Service

No local machine interaction is required after publishing.

---

## 🚧 Work in Progress

This dashboard is a **WIP**.  
Planned enhancements include:

- Additional metrics (after deeper review of API endpoints)
- Time-intelligent analysis (if historical data becomes available)
- Automations via **n8n** or similar, to notify me of refresh status
- More detailed repository insights

---

## 📁 Included in this Repository

- `.pbix` file of the current dashboard  
- JSON theme file  
- PNG custom background  
- This README  

Feel free to explore, fork, or contribute.