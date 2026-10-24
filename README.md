# Cisco Enterprise Infrastructure: Network Telemetry & Incident Command Dashboard
<div align="center">
  
[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit?style=for-the-badge&logo=googlechrome&logoColor=white)](https://public.tableau.com/views/Book1_17925810876030/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
[![GitHub Repo](https://img.shields.io/badge/GitHub-sanskar00--debug-black?style=for-the-badge&logo=github)](https://github.com/sanskar00-debug)
  
</div>

## 📌 Project Overview
This project delivers real-time situational awareness across distributed corporate environments by unifying network capacity diagnostics with actionable security indicators. It processes multi-server application logs, syslog feeds, and NetFlow metrics to expose infrastructure vulnerabilities and performance bottlenecks before failures occur.

## 🚀 Key Engineering & Analytics Highlights
* **Traffic Velocity & Integrity Tracking:** Monitored metrics across 6,400+ simulated network transactions, enabling immediate root-cause diagnostics of peak demand windows and outlier packet drop spikes.
* **Regional Threat Distribution Analytics:** Modeled a security baseline categorization mechanism to isolate high-risk anomaly segments and prioritize threat vectors across global cloud availability regions.
* **Asset Lifecycle & Health Mapping:** Implemented a unified inventory monitoring system across active hardware tiers (Firewalls, Core Routers, Edge Switches) to streamline proactive maintenance and structural patching.

## 🛠️ Data Infrastructure & Architecture Spec
To simulate a real-world enterprise pipeline, the theoretical architecture underlying this analysis relies on:
1. **Data Ingestion:** High-volume logging streamed efficiently via an **Apache Kafka** event-driven architecture.
2. **Storage Layer:** Unstructured network metrics parsed cleanly into a normalized relational database engine (**MySQL/Oracle SQL**).
3. **Analytics Tier:** Advanced python filtering utilities used to classify traffic anomalies and profile typical corporate behavior baselines.
4. **Visualization Layer:** Fully interactive, containerized business intelligence monitoring deployed via **Tableau Public**.

## 📊 Dashboard Views Included
* **Timeline Engine:** Tracks bandwidth speeds and consecutive packet drop counts over a continuous granular timescale.
* **Geographical Risk Map:** Flags localized infrastructure segments showing exceptional concentrations of high-priority security exceptions.
* **Hardware Matrix:** Aggregates overall health profiles for operational router, switch, and gateway configurations.

## 🗂️ Repository Structure
* `/Cisco_Network_Telemetry.xlsx` - Cleaned source telemetry data used to drive calculations.
* `/Cisco_Enterprise_Telemetry_Dashboard.twbx` - Packed Tableau workbook with operational calculations and filters.
* `/dashboard_preview.png` - Dashboard Preview image of Cisco Network Telemetry.
