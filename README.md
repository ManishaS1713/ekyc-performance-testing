# eKYC Application - Load Testing with Apache JMeter

This repository contains a JMeter test plan (`ekyc_Individual_DSC_LoadTest.jmx`) designed to evaluate the performance of an eKYC (electronic Know Your Customer) application under simulated user load.

## 📌 Overview

- **Tool:** Apache JMeter
- **Application:** eKYC web platform
- **Goal:** Assess system behavior and stability under concurrent user activity, such as login, document upload and download certificate.

## 🧪 What This Test Covers

The JMeter test simulates:
- Multiple virtual users performing KYC verification actions
- API or form submissions with configured parameters
- Timers and think times to mimic realistic user behavior
- Performance measurement using JMeter listeners

## 🔧 How to Use

1. Open the `.jmx` file in Apache JMeter.
2. Configure the following if needed:
   - Thread Group (users, ramp-up period)
   - Server URLs or API endpoints
   - Authentication parameters
3. Run the test.
4. Analyze performance via:
   - Summary Report
   - View Results Tree
   - Aggregate Report

This repository contains a JMeter test plan (`ekyc_Individual_DSC_LoadTest.jmx`) designed to evaluate the performance of an eKYC (electronic Know Your Customer) application under simulated user load.

## 📌 Overview

- **Tool:** Apache JMeter
- **Application:** eKYC web platform
- **Goal:** Assess system behavior and stability under concurrent user activity, such as login and document upload

## 🧪 What This Test Covers

The JMeter test simulates:
- Multiple virtual users performing KYC verification actions
- API or form submissions with configured parameters
- Timers and think times to mimic realistic user behavior
- Performance measurement using JMeter listeners

## 🔧 How to Use

1. Open the `.jmx` file in Apache JMeter.
2. Configure the following if needed:
   - Thread Group (users, ramp-up period)
   - Server URLs or API endpoints
   - Authentication parameters
3. Run the test.
4. Analyze performance via:
   - Summary Report
   - View Results Tree
   - Aggregate Report
