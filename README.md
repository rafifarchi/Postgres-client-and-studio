# Postgres-client-and-studio
Postgres client and studio for android
# Postgres Studio for Android

[![Get it on Google Play](https://img.shields.io/badge/Google_Play-Download_App-green?style=for-the-badge&logo=googleplay)](https://play.google.com/store/apps/details?id=com.storage.postgres_studio)
[![Status](https://img.shields.io/badge/Status-Production-brightgreen?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-Non--Profit%20%2F%20Free-blue?style=for-the-badge)](#)
![Visitors](https://api.visitorbadge.io/api/visitors?path=rafifarchi%2FPostgres-client-and-studio&countColor=%232ccce4)

A powerful, high-performance, **100% free and ad-free** PostgreSQL client and server monitoring companion for Android. 

Built as a **community-first, non-profit tool**, Postgres Studio aims to enrich the PostgreSQL ecosystem by giving DBAs, DevOps engineers, and software developers a complete database toolkit directly from their mobile devices.

---

## 📱 Why a Mobile Client for PostgreSQL? (Use Case)

Modern databases run 24/7 in the cloud (Aiven, Supabase, AWS RDS, GCP), but infrastructure emergencies don't wait until you're at your desk. 

**Postgres Studio is built for mobile-first workflows and field tasks:**
* **Emergency On-Call Diagnostics:** Instantly check server health, active connections, and long-running queries when an alert hits your phone.
* **On-the-Go Inspection & Triage:** Inspect tables, view execution plans (`EXPLAIN`), and run quick queries from anywhere without booting up a laptop.
* **Offline Script Preparation:** Draft SQL scripts, write complex data migrations, or study schema structures while offline, ready to execute upon connection.
* **Lightweight & Fast:** Immediate startup with zero clutter, external tracking, or invasive ads.

---

## ✨ Key Features Currently Available

### 🔐 Connection & Profile Management
* **Unlimited Saved Connections:** Securely store and manage multiple PostgreSQL connection profiles.
* **Import & Export Configs:** Easily backup or transfer connection definitions across devices.

### 🗂️ Database Object Browser & DDL
* **Hierarchical Schema Navigation:** Browse database structures cleanly separated by schemas, tables, views, functions, and sequences.
* **Reverse DDL Generation:** View accurate SQL `CREATE` statements for tables and views on the fly.
* **Data Inspection & Editing:** View table contents, execute inline data edits, and share/export query result sets.

### 📊 Instant ERD Generation
* **Automatic ERD Diagrams:** Draw Schema ERD visual models directly from the database DDL without any manual mapping or external setup.

### 📝 Offline Workspace & SQL Runner
* **Offline SQL Studio:** Prepare, organize, and save scripts in a local workspace prior to executing against a live database.
* **Interactive SQL Console:** Run custom queries directly or load saved scripts from your workspace.
* **Query Performance Analysis:** View detailed `EXPLAIN` and `EXPLAIN ANALYZE` execution plans to optimize slow SQL.

### ⚡ Live Server Health & Monitoring
* **Real-time `pg_stat_activity` Dashboard:** Monitor total open connections, idle sessions, and currently active queries.
* **Process Inspection:** Identify running backend jobs, view full active query text, check client IPs, and execute query cancellations (`pg_cancel_backend`).

### 📚 Embedded PostgreSQL Pocket Guide
* **Quick Reference Guide:** Built-in PostgreSQL syntax reference for fast offline access to DDL, DML, and utility functions.

---

## 🚀 Future Roadmap & Vision

Postgres Studio is actively evolving to become a comprehensive mobile DBA studio:

1. **Advanced Server Health Analytics:** Expanding server monitoring with metrics for lock contention, buffer cache hit ratios, transaction throughput, and replication delay tracking.
2. **Abstract DDL & Entity Definition Layer:** Introducing a higher-level visual abstraction layer to define, edit, and export database entities, relationships, and constraints seamlessly on mobile.
3. **Enhanced Security & Connection Protocols:** Additional SSH tunneling options and biometric locking.

---

## 🛡️ Security & Privacy Statement

Postgres Studio is distributed **exclusively via Google Play** to guarantee maximum user security, verified production builds, and safe automatic updates via **Google Play Protect**.

* **Zero Ads / Zero Trackers:** We do not collect, monetize, or transmit your database credentials or data.
* **Direct Connections:** All database connections are established directly from your device to your server.

👉 **[Download Postgres Studio on Google Play Store](https://play.google.com/store/apps/details?id=com.storage.postgres_studio)**

---

## 💬 Feedback & Community Support

Since this project is built for the community, your feedback is invaluable! Feel free to open a **GitHub Issue** for feature requests, UI improvements, or bug reports.
