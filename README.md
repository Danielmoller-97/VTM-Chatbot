# VTM-Chatbot


# Project Overview

This project automates the process of capturing visitor data, generating unique codes, and responding via WhatsApp. It integrates Google Sheets, Google Apps Script, Zapier, and WATI to replace manual data entry with a streamlined workflow.

The goal was to reduce human error, save time, and provide a smoother experience for both staff and visitors.

# Tools & Technologies

Google Apps Script (JavaScript) – for custom automation logic

Zapier – for connecting Google Sheets and WATI via webhooks

WATI – WhatsApp Business API integration for automated messaging

Google Sheets – data logging, validation, and storage

# Workflow

Visitor Interaction

A visitor scans a QR code and initiates a WhatsApp message.

# Data Capture

WATI captures user input and sends the data to a connected Google Sheet.

Unique Code Generation

Google Apps Script automatically assigns a unique code to the new entry in Sheets.

Automated Response

Zapier reads the updated sheet and triggers a webhook.

WATI sends the visitor their unique code back via WhatsApp.

# Results

Reduced manual data entry and improved accuracy.

Response time decreased from minutes/hours to seconds.

Scalable process: works automatically for every new visitor without staff intervention.

# Workflow Diagram

QR Code → WATI → Google Sheets → Apps Script → Zapier → WATI WhatsApp Reply

https://app.diagrams.net/?splash=0#G13JNE7jI-4NBBpdyPjC41O3OTfam2OhAy#%7B"pageId"%3A"k_AqtTDA6T2ZbBNLh1TI"%7D

# Notes

All data shown in this demo uses dummy/test values to protect user privacy.

API keys, webhook URLs, and confidential details have been removed.

# Future Improvements

Add payment integration (e.g., Payfast) before code generation.

Build a front-end dashboard for staff to view and manage codes.

Expand to a full-stack application for greater customization and scalability.
