# HAQMS Engineering Evaluation Assignment

## Overview

This project was improved and debugged as part of the Figital Labs Full Stack Internship Assignment.

## Issues Identified

### Frontend Issues

* React Hooks order issue in Dashboard component
* Application crash caused by nullable medicalHistory field
* Missing imports and routing inconsistencies
* Excessive re-renders caused by search filtering

### Backend Issues

* SQL injection vulnerability in doctors search endpoint
* Unsafe raw query execution using queryRawUnsafe
* Sequential database calls causing performance bottlenecks
* Error message leakage from backend responses

### Project Issues

* Missing .gitignore
* node_modules and build files being tracked
* Environment configuration cleanup required

---

## Fixes Implemented

### Frontend Fixes

* Fixed React Hooks order violation
* Added optional chaining / null safety checks
* Improved dashboard stability
* Cleaned conditional rendering flow

### Backend Fixes

* Removed unsafe SQL query logging
* Improved API stability
* Cleaned development configuration

### Project Setup Improvements

* Added proper .gitignore
* Removed unnecessary tracked files
* Cleaned repository structure

---

## Optimizations Performed

* Reduced frontend crashes
* Improved rendering consistency
* Improved repository cleanliness
* Better development workflow setup

---

## Remaining Known Issues

* Some backend endpoints still require optimization
* Queue system may still have concurrency edge cases
* Additional security hardening can be implemented
* Deployment environment variables must be configured properly

---

## Approach & Reasoning

The main focus was prioritizing:

1. Application stability
2. Critical frontend bug fixes
3. Security-related cleanup
4. Repository and environment management

Priority was given to issues that directly affected application usability and runtime stability.

- **Resolve styled 404 error**: Clicking "View Diagnostic Reports Details (Legacy App)" on a patient profile triggers a 404 page. Your final task is to build out that missing page (`src/app/patients/[id]/history-records/page.js`) to fetch and render the patient clinical record.

---

Good luck! You will be evaluated based on the cleanliness, correctness, efficiency, and safety of your refactoring.
