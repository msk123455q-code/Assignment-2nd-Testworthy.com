📚 Assignment 2 – Test Plan & Test Case Writing Using Testworthy

📌 Project Overview

This repository contains Assignment 2: Test Plan and Test Case Writing Using Testworthy, completed as part of Software Quality Assurance (SQA) coursework.

The project demonstrates the complete software testing lifecycle for an Online Bookstore Application using the Testworthy Test Management Platform.

The assignment focuses on:

Creating a professional Test Plan

Designing detailed Test Cases

Organizing Test Suites and Sections

Executing Test Runs across multiple sprints

Tracking defects

Generating execution reports

Classifying tests by priority and type


The goal was to gain practical experience with industry-standard QA practices and test management workflows.


---

🎯 Objectives

The main objectives of this assignment were:

Understand professional test management processes

Learn how to write structured test cases

Create and manage test plans

Execute tests in sprint-based development

Analyze pass/fail results

Track software defects

Generate formal testing reports

Practice test organization and prioritization



---

🛠 Tool Used

Testworthy

A cloud-based test management platform used for:

Test Planning

Test Case Management

Test Suite Organization

Test Run Execution

Reporting

Defect Tracking


Website:

[Testworthy](https://testworthy.com

---

📖 Project Details

Item	Value

Project Name	Assignment2_testWriting
Application Under Test	Online Bookstore Application
Tool Used	Testworthy
Testing Approach	Manual Testing
Environment	Staging
Automation Tool Reference	Selenium WebDriver
Test Runs	3
Total Test Cases	34



---

📋 Assignment Tasks Completed

The assignment was divided into six major tasks.

Task 1 – Test Case Writing

Created detailed test cases covering all refined user stories.

Each test case included:

Title

Type

Priority

Description

Preconditions

Test Steps

Expected Results



---

Task 2 – Test Plan Creation

A centralized test plan was created to define:

Testing scope

Coverage boundaries

Sprint linkage

Overall project tracking


Test Plan

Field	Value

Plan Name	Main Plan for User Stories
Status	Active
Purpose	Covers all refined user stories
Linked Runs	Sprint 1, Sprint 2, Sprint 3



---

Task 3 – Test Execution

Executed all test cases across three sprints.

Test results were marked as:

Passed

Failed

Blocked

Skipped

Pending



---

Task 4 – Report Generation

Generated professional reports directly from Testworthy.

Reports included:

Full Project Execution Report

Sprint 1 Report

Sprint 2 Report

Sprint 3 Report



---

Task 5 – Test Suite Organization

Created hierarchical test suites and sections.

Main Suite

User Story 1: Login Module

Sprint 1 – The Basics

Account Login & Registration

Book Database & Search


Sprint 2 – The Shop & User Experience

Shopping Cart & Filtering

Secure Payment Checkout


Sprint 3 – Account Management & Post-Purchase

Profile & Order History

Smart Suggestions



---

Task 6 – Test Classification

All test cases were categorized according to:

Test Types

Type	Count

Functional	30
Security	4


Priority Levels

Priority	Purpose

Critical	Must pass before release
High	Important functionality
Medium	Standard validation
Low	Edge case testing



---

📂 Test Coverage

The Online Bookstore Application was tested across the following modules:

Authentication

Login

Registration

Password Reset

Logout


Search & Catalog

Search by Title

Genre Filtering

No Result Handling


Shopping Cart

Add to Cart

Remove from Cart

Quantity Updates

Stock Validation


Checkout

Empty Cart Validation

Shipping Information

Order Placement


User Management

Profile Dashboard

Profile Updates

Order History


Recommendation System

Smart Suggestions

Suggestion-to-Cart Flow



---

🧪 Test Case Summary

Sprint	Test Cases

Sprint 1	18
Sprint 2	9
Sprint 3	7
Total	34



---

🚀 Sprint Execution Results

Sprint 1 – The Basics

Metric	Value

Total Cases	18
Passed	15
Failed	3
Success Rate	83.3%


Failed Test Cases

TC-7 – Weak Password Validation

TC-8 – Password Confirmation Validation

TC-14 – Reset Password to Same Value



---

Sprint 2 – Shop & User Experience

Metric	Value

Total Cases	9
Passed	8
Failed	1
Success Rate	88.9%


Failed Test Case

TC-21 – Add Out-of-Stock Book to Cart


Defect Logged:

BUG-004


---

Sprint 3 – Account Management & Post-Purchase

Metric	Value

Total Cases	7
Passed	6
Failed	0
Blocked	1
Success Rate	85.7%


Blocked Test Case

TC-34 – Add Smart Suggestion Book to Cart


Defect Dependency:

BUG-005


---

📊 Overall Project Results

Metric	Value

Total Test Cases	34
Passed	29
Failed	4
Blocked	1
Dashboard Pass Rate	85%
Project Overview Rate	87.9%
Project Health	89%



---

🐞 Defects Identified

Bug ID	Description

BUG-004	Out-of-stock items can still be added to cart
BUG-005	Dependency issue affecting Smart Suggestion cart functionality



---

📈 Key Learning Outcomes

Through this assignment, the following skills were developed:

Professional Test Case Writing

Test Planning

Test Suite Management

Sprint-Based Testing

QA Documentation

Defect Tracking

Execution Reporting

Risk-Based Prioritization

Functional Testing

Security Testing



---

🏗 Repository Structure

Assignment2/
│
├── README.md
├── Assignment2_Report.pdf
├── Test_Plan/
│   └── Main_Test_Plan
│
├── Test_Cases/
│   ├── Sprint1_TestCases
│   ├── Sprint2_TestCases
│   └── Sprint3_TestCases
│
├── Reports/
│   ├── Full_Execution_Report
│   ├── Sprint1_Report
│   ├── Sprint2_Report
│   └── Sprint3_Report
│
└── Screenshots/


---

🎓 Academic Information

Student: Shahid Khan

University: Hazara University

Course: Software Quality Assurance (SQA)

Assignment: Test Plan and Test Case Writing Using Testworthy

Submission Date: June 2026


---

✅ Final Result

34 Test Cases | 29 Passed | 4 Failed | 1 Blocked | 87.9% Overall Success Rate

This project demonstrates the complete QA workflow from planning and test design to execution, defect tracking, and reporting using a professional test management platform.
