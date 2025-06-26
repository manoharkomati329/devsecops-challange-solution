
# Product Requirement Document - Container Image Vulnerability Scanner

## Overview
A dashboard-based product to scan container images for vulnerabilities, identify their severity, and provide actionable insights.

## User Stories
- As a user, I want to view the number of container images with vulnerabilities.
- As a user, I want to identify images with critical or high vulnerabilities quickly.
- As a user, I want to drill down into image vulnerability details and take action.

## Features
- Dashboard with summary statistics
- Searchable & filterable image list with vulnerability details
- Detailed CVE breakdown per image
- Export options (JSON/PDF)
- Rescan & alert triggers

## Non-functional Requirements
- Scalable for thousands of images
- Role-based access control
- Near real-time scan updates

## Dev Tasks
- API integration with vulnerability scanner (e.g., Trivy)
- UI components for dashboard, filtering, sorting
- CVE detail component and export logic
- User authentication & RBAC
