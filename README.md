# AI Lead Scoring CRM Automation

## Overview

This project automates lead capture, qualification and notification workflows using Make.com, Google Forms, Google Sheets and Airtable.

## Features

- Lead Capture via Google Forms
- Data Storage in Google Sheets
- Automated Lead Qualification
- Hot / Warm / Cold Routing
- Airtable CRM Integration
- Automatic Score Assignment
- Dynamic Lead Notes Generation
- Gmail Notifications for Hot Leads

## Workflow

Google Form
↓
Google Sheets
↓
Make.com Router
├── Hot Lead
├── Warm Lead
└── Cold Lead
↓
Airtable CRM
↓
Gmail Notification

## Tech Stack

- Make.com
- Google Forms
- Google Sheets
- Airtable
- Gmail

## Lead Scoring Logic

### Hot Lead
- Budget > €3000
- Score = 9
- Status = Hot

### Warm Lead
- Budget €1000–€3000
- Score = 6
- Status = Qualified

### Cold Lead
- Budget < €1000
- Score = 2
- Status = Cold

## Project Goal

Build a no-code automation workflow that captures leads, qualifies them automatically and stores them in a CRM while notifying the sales team about high-priority opportunities.
