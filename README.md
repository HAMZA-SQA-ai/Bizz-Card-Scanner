# Biz Card Scanner QA Report

<div align="center">

<h1>📇 Biz Card Scanner App</h1>

<p>
AI-powered business card scanning application for saving and managing contact information digitally.
</p>

<img src="https://img.shields.io/badge/Platform-Mobile-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Testing-QA%20Automation-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-orange?style=for-the-badge" />

</div>

---

# 📌 Project Overview

Biz Card Scanner is a mobile application designed to scan business cards using AI-powered recognition technology. The application extracts contact details from scanned cards and stores them directly on the user's device.

The QA process focused on:

* Functional Testing
* UI/UX Testing
* Validation Testing
* Screen Verification
* Bug Reporting
* Test Case Execution
* Checklist Validation

---

# 🚀 Application Features

<table>
<tr>
<th>Feature</th>
<th>Description</th>
</tr>
<tr>
<td>AI Card Scanner</td>
<td>Scans business cards and extracts user information automatically</td>
</tr>
<tr>
<td>Contact Saving</td>
<td>Saves scanned data directly into the device</td>
</tr>
<tr>
<td>Authentication</td>
<td>Sign Up, Sign In and OTP verification system</td>
</tr>
<tr>
<td>Search & Explore</td>
<td>Search saved contacts and manage records</td>
</tr>
<tr>
<td>Profile Management</td>
<td>Manage personal profile and settings</td>
</tr>
</table>

---

# 🧪 QA Testing Scope

<div align="center">

<table>
<tr>
<th>Testing Area</th>
<th>Status</th>
</tr>
<tr>
<td>Screen Checker</td>
<td>✅ Completed</td>
</tr>
<tr>
<td>Checklist Execution</td>
<td>✅ Completed</td>
</tr>
<tr>
<td>Test Case Execution</td>
<td>✅ Completed</td>
</tr>
<tr>
<td>Bug Reporting</td>
<td>✅ Completed</td>
</tr>
</table>

</div>

---

# 📱 Screen Verification

<table>
<tr>
<th>Screen Name</th>
<th>Status</th>
</tr>
<tr>
<td>Sign In</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Sign Up</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Verification OTP</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Home</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Explore</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Search</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Profile</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Card Scanner</td>
<td>✅ Pass</td>
</tr>
</table>

---

# 📋 Test Checklist Summary

<table>
<tr>
<th>Module</th>
<th>Validation Area</th>
<th>Status</th>
</tr>
<tr>
<td>Authentication</td>
<td>Sign Up validation and input checks</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>OTP Verification</td>
<td>OTP verification flow testing</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Scanner Module</td>
<td>Business card scanning functionality</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Contact Management</td>
<td>Save and manage scanned contacts</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Navigation</td>
<td>Page navigation and transitions</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>Search Functionality</td>
<td>Search and filter operations</td>
<td>✅ Pass</td>
</tr>
</table>

---

# 🧾 Executed Test Cases

<table>
<tr>
<th>Test Case ID</th>
<th>Title</th>
<th>Expected Result</th>
<th>Status</th>
</tr>
<tr>
<td>TC_BS_001</td>
<td>Successful Sign Up</td>
<td>Account created and OTP sent</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>TC_BS_002</td>
<td>Invalid Email Sign Up</td>
<td>Error message displayed</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>TC_BS_003</td>
<td>OTP Verification</td>
<td>Account verified successfully</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>TC_BS_004</td>
<td>Wrong OTP</td>
<td>Invalid OTP error displayed</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>TC_BS_005</td>
<td>Login Validation</td>
<td>User logged in successfully</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>TC_BS_006</td>
<td>Business Card Scan</td>
<td>Card data extracted correctly</td>
<td>✅ Pass</td>
</tr>
<tr>
<td>TC_BS_007</td>
<td>Save Contact</td>
<td>Contact stored successfully</td>
<td>✅ Pass</td>
</tr>
</table>

---

# 🐞 Reported Bugs

<table>
<tr>
<th>Bug ID</th>
<th>Module</th>
<th>Issue Type</th>
<th>Priority</th>
<th>Status</th>
</tr>
<tr>
<td>BS_001</td>
<td>Sign Up</td>
<td>Validation</td>
<td>High</td>
<td>To Do</td>
</tr>
<tr>
<td>BS_002</td>
<td>OTP</td>
<td>Functional</td>
<td>High</td>
<td>To Do</td>
</tr>
<tr>
<td>BS_003</td>
<td>Google Login</td>
<td>UI/UX</td>
<td>Low</td>
<td>To Do</td>
</tr>
<tr>
<td>BS_004</td>
<td>Home Search</td>
<td>Functional</td>
<td>Medium</td>
<td>To Do</td>
</tr>
</table>

---

# 🔍 Key Issues Identified

## 1. Phone Number Validation

* Invalid phone numbers accepted
* No validation message displayed
* Form submits incorrect data

## 2. Missing Resend OTP Option

* OTP resend option unavailable
* Users unable to request new OTP
* Verification process blocked

## 3. Google Button UI Misalignment

* Google icon alignment issue
* Poor visual spacing
* UI inconsistency detected

## 4. Incorrect Search Navigation

* Search redirects to Explore page
* Home page context lost
* Navigation behavior inconsistent

---

# 📊 QA Execution Summary

<div align="center">

<table>
<tr>
<th>Total Areas Tested</th>
<th>Completed</th>
<th>Critical Issues</th>
<th>Overall Result</th>
</tr>
<tr>
<td>4</td>
<td>100%</td>
<td>2 High Priority</td>
<td>⚠️ Needs Fixes Before Production</td>
</tr>
</table>

</div>

---

# 🛠 Testing Types Performed

* Manual Testing
* Functional Testing
* UI Testing
* Validation Testing
* Navigation Testing
* Smoke Testing
* Regression Testing

---

# 💻 Tools Used

<table>
<tr>
<th>Tool</th>
<th>Purpose</th>
</tr>
<tr>
<td>Excel Sheet</td>
<td>Test documentation</td>
</tr>
<tr>
<td>Mobile Device</td>
<td>Application testing</td>
</tr>
<tr>
<td>Vysor</td>
<td>Screen recording and bug capture</td>
</tr>
<tr>
<td>GitHub</td>
<td>Project repository management</td>
</tr>
</table>

---

# 📁 Repository 

```bash
Biz-Card-Scanner-QA/
│
├── Screen Checker
├── Checklist
├── Test Cases
├── Bugs Report
└── README.md
```

---

# 🎯 Final QA Status

The Biz Card Scanner application was tested successfully across authentication, navigation, scanning, and contact management modules.

Several functional and UI-related issues were identified during testing. The application requires fixes for validation handling, OTP resend functionality, and navigation consistency before production deployment.

---

<div align="center">

</div>
