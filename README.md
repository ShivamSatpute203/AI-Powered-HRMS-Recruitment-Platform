# 🤖 AI-Powered HRMS & Recruitment Platform

## 📖 Overview

The **AI-Powered HRMS & Recruitment Platform** is an enterprise recruitment and employee onboarding solution developed using **OutSystems ODC**.

The platform leverages **AI-based resume parsing** to automate candidate screening and profile creation, significantly reducing manual recruitment effort. It manages the complete employee lifecycle—from hiring requests and candidate applications to onboarding, employee creation, and workforce access management.

The solution consists of two integrated applications:

### 🏢 HRMS Portal (Internal Application)
Access Link - https://personal-bjoeimiy-dev.outsystems.app/HRMS_APP/JobPostings

Used by HR teams, recruiters, interviewers, account managers, and employees to manage recruitment, onboarding, and workforce processes.

### 🌐 Jobs Portal (Public Application)
Access Link - https://personal-bjoeimiy-dev.outsystems.app/JOBS/JobPostings

A public recruitment portal where candidates can browse jobs, submit applications, upload resumes, and complete onboarding activities.

---

# 🚀 Key Feature – AI Resume Parsing

The primary feature of the platform is its **AI-powered resume parsing engine**.

Instead of manually reviewing resumes, recruiters receive structured candidate profiles automatically generated through an external AI Resume Parsing API.

## AI Processing Flow

```text
Candidate Applies
       │
       ▼
Resume Uploaded
       │
       ▼
AI Resume Parsing API
       │
       ▼
Information Extraction
       │
       ▼
Candidate Profile Creation
       │
       ▼
Recruiter Review Dashboard
```

### Information Extracted

- Personal Details
- Contact Information
- Skills
- Work Experience
- Education
- Certifications
- Previous Employers

### Benefits

- ⚡ Faster candidate screening
- 📄 Reduced manual effort
- 🎯 Improved shortlisting process
- ✅ Consistent candidate evaluation

---

# 📋 Recruitment Management

## Hiring Requests & Job Postings

- Account Managers create hiring requests.
- HR creates and manages job postings.
- Job postings can include links to LinkedIn, Glassdoor, and other recruitment platforms.

## Candidate Evaluation

Recruiters can:

- Review parsed candidate information
- Preview resumes
- Shortlist candidates
- Reject candidates

---

# 🎤 Interview Management

Shortlisted candidates can be invited for interviews.

### Features

- Interview scheduling
- Interview rescheduling
- Automated email notifications
- Meeting link distribution
- Interview evaluation submission

Interviewers can provide recommendations:

- ✅ Hire
- ⏳ Hold
- ❌ Reject

---

# 📄 Offer Management

Selected candidates move into the offer stage.

### Features

- Offer generation
- Offer letter attachment
- Offer acceptance workflow
- Offer rejection workflow

Candidates receive offer details and can accept or reject directly through email links.

---

# 👨‍💼 Employee Onboarding

After offer acceptance, an automated onboarding process begins.

## Process

- Document submission reminders
- HR document verification
- Manager approval workflow
- Pre-boarding completion

Candidates upload required documents, which are automatically routed for verification and approval.

---

# 👥 Employee Creation & Access Provisioning

A scheduled background process runs daily and automatically:

- Creates employee records
- Generates Employee IDs
- Creates portal accounts
- Sends activation emails

Employees can then access the HRMS Portal using their Employee ID and password.

---

# ⚙️ Automation & Background Processing

The platform includes automated background jobs for:

- Resume processing
- Document submission reminders
- Employee account provisioning
- Email notifications

These processes reduce manual intervention and improve operational efficiency.

---

# 🔐 Security

The application implements **custom role-based access control (RBAC)**.

### Supported Roles

- HR Administrator
- Recruiter
- Account Manager
- Interviewer
- Employee
- Guest Recruiter

Authentication is performed using **Employee ID** and **Password**.

---

# 🛠️ Technical Highlights

- OutSystems ODC Development
- AI Resume Parsing Integration
- Automated Candidate Profiling
- Public Recruitment Portal
- Interview Management
- Offer Management
- Employee Onboarding Automation
- Scheduled Background Jobs
- Email Notification Framework
- Custom Role-Based Security
- Modular Enterprise Architecture

---

# 🔄 Recruitment Lifecycle

```text
Hiring Request
      │
      ▼
Job Posting
      │
      ▼
Candidate Application
      │
      ▼
AI Resume Parsing
      │
      ▼
Shortlisting
      │
      ▼
Interview
      │
      ▼
Offer Generation
      │
      ▼
Offer Acceptance
      │
      ▼
Onboarding
      │
      ▼
Employee Creation
      │
      ▼
Portal Access
```

---

# 📈 Project Impact

This solution demonstrates how AI can be integrated into enterprise recruitment processes to automate candidate screening, accelerate hiring decisions, and streamline onboarding while maintaining a scalable, secure, and enterprise-ready HRMS architecture.
