# SyncField Scientific Paper

## Title
**SyncField: Design and Evaluation of an Offline-First Mobile Data Collection and Synchronization System for Low-Connectivity Environments**

## Authors
- Mohamed Tariq Abdel Farraj
- Mohammed Sharif
- Ghaidaa Al-Sir
- Dua al-Mahdi

**Supervisor:** Yahya Othman, MSc

## Abstract
SyncField is an offline-first mobile data collection and synchronization system designed for environments where Internet connectivity is weak, intermittent, or unavailable. The system uses a Flutter/Dart Android client with SQLite local persistence and secure session storage, a Node.js/Express.js REST backend, and PostgreSQL central storage.

The system supports local data collection, rule-based validation, visible pending responses, role- and form-based authorization, supervisor scope, user-initiated synchronization, stable identifiers for idempotency, a durable mutation queue for update/soft-delete/restore operations, and optimistic versioning with explicit conflict resolution.

The documented prototype evaluation contained 92 functional and integration test cases, all of which achieved their expected outcomes within the verified Android 13 and trusted local-network test environment.

## Main Technologies
- Flutter / Dart
- SQLite / sqflite
- flutter_secure_storage
- Node.js / Express.js
- PostgreSQL
- REST / JSON
- Android

## Research Focus
- Offline-first mobile architecture
- Reliable field-data collection
- Manual synchronization
- Idempotent retry handling
- Role-based and form-based authorization
- Supervisor scope
- Record lifecycle management
- Optimistic version conflict handling
- Arabic-English localization

## Paper Files
- [View the scientific paper (PDF)](./SyncField_Scientific_Paper.pdf)
- [Download the editable Word document](./SyncField_Scientific_Paper.docx)

## Evaluation Summary
The final documented test matrix contained **92 functional and integration test cases**, and all **92/92** achieved their expected outcomes in the verified prototype environment.

The reported result should be interpreted as completion of the documented prototype test matrix, not as production certification or a statistical estimate of reliability under all field conditions.

## Current Limitations
The current evaluation is limited by:
- Testing focused on one Android device and a debug APK.
- Manual, user-initiated synchronization rather than background synchronization.
- Backend deployment on a trusted local network.
- No broad performance, concurrency, or long-duration reliability study.
- No formal participant-based usability study.

## Repository Status
This repository is currently maintained as a private research repository while the manuscript is being prepared for journal submission.

## Citation
A formal citation will be added after journal submission/publication details are available.

---
© SyncField Research Team
