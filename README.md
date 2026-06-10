# 🔄 Matrix CE: Backend Services & Sync

## 📋 Overview
Background services focused on external synchronization, data harvesting, and project maintenance.

## 🏗️ Services
- **Gmail Me-to-Me Harvester**: `gmail_harvester.py` - Extracting tasks and axioms from user-sent emails.
- **GitHub Sync**: `github_sync.py` - Automated repo synchronization and README maintenance.
- **Log Hygiene**: `prune_logs.py` - Maintaining system performance via automated log cleanup.

## 📮 The Postmaster
- **Logic**: `kqml_router.py` (Integration) - Orchestrating high-latency data transfers between agents.
