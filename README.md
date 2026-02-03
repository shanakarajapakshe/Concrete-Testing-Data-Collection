# 🏗️ Multi-Site Concrete Testing Data Management System

[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg)]()
[![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?logo=google&logoColor=white)](https://developers.google.com/apps-script)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)

---

## 🎯 What Is This System?

A **complete web-based solution** for managing concrete testing data across multiple construction sites with real-time Google Sheets integration.

This system enables construction site engineers to collect, manage, and analyze concrete testing data from a centralized platform with site-specific access control.

---

## ✨ Key Features

### 🔐 Secure Multi-Site Access
- Individual login credentials for each construction site
- Site-based data isolation and access control
- Secure authentication system

### 📝 Comprehensive Data Collection
Record all essential concrete testing information:
- **Material Properties**: Cement type & quantity, water content, fine & coarse aggregates, admixtures
- **Performance Metrics**: Compressive strength, slump test, flow test, test age
- **Additional Properties**: Shrinkage percentage, elastic modulus, curing conditions
- **Documentation**: Sample ID, mix design, tested by, observations

### 📊 Data Management & Analysis
- **Real-time Synchronization**: All data stored in Google Sheets
- **Advanced Search**: Find specific tests by sample ID, mix design, or tester
- **Smart Filtering**: Filter by test age (7, 14, 28 days) or mix design type
- **Statistics Dashboard**: View total tests, average strength, and latest test dates
- **Data Export**: Download data as CSV for external analysis
- **Color-Coded Display**: Visual indicators for strength levels (low/medium/high)

### 🏢 Multi-Site Architecture
- Separate data sheets for each construction site
- Centralized data storage in a single spreadsheet
- Scalable design - easily add new sites
- No data mixing between sites

---

## 💼 Use Cases

### For Construction Companies
- Manage multiple project sites from one system
- Ensure data consistency across all locations
- Track quality control across projects
- Generate compliance reports

### For Site Engineers
- Quick and easy data entry
- Access historical test data instantly
- Monitor concrete strength development
- Share data with project managers

### For Quality Control Teams
- Real-time visibility of all testing
- Identify trends and patterns
- Ensure compliance with specifications
- Generate performance analytics

---

## 🎬 System Workflow

```
1. LOGIN
   └─ Engineer selects their site and enters password

2. DASHBOARD
   ├─ Option A: Enter New Test Data
   │   └─ Fill comprehensive testing form
   │       └─ Data automatically saved to Google Sheets
   │
   └─ Option B: View Historical Data
       ├─ Search and filter past tests
       ├─ View statistics and trends
       └─ Export data for analysis
```

---

## 🏗️ Technical Architecture

```
┌─────────────────────────────────────────┐
│         Web Browser Interface            │
│  (Login → Dashboard → Data Entry/View)   │
└──────────────────┬──────────────────────┘
                   │ HTTPS
                   ▼
┌─────────────────────────────────────────┐
│     Google Apps Script (Backend)         │
│  • Authentication                        │
│  • Data Submission                       │
│  • Data Retrieval                        │
└──────────────────┬──────────────────────┘
                   │
                   ▼
┌─────────────────────────────────────────┐
│         Google Sheets Database           │
│  Site-A | Site-B | Site-C | Site-D ...  │
└─────────────────────────────────────────┘
```

---

## 📊 Data Collected

| Category | Information |
|----------|-------------|
| **Identification** | Sample ID, Mix Design, Test Date, Tested By |
| **Materials** | Cement (Type & Quantity), Water, Aggregates, Admixtures |
| **Performance** | Compressive Strength (MPa), Test Age (days), Slump (mm), Flow (mm) |
| **Properties** | Shrinkage (%), Elastic Modulus (GPa), Curing Method |
| **Notes** | Observations, Special Conditions, Remarks |

---

## 🖥️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Google Apps Script
- **Database**: Google Sheets
- **Authentication**: Password-based site access
- **Deployment**: Static web hosting (No server required)

---

## 📱 Platform Support

- ✅ **Desktop**: Windows, macOS, Linux
- ✅ **Mobile**: iOS, Android (Responsive design)
- ✅ **Browsers**: Chrome, Firefox, Safari, Edge
- ✅ **Offline**: Can be deployed on internal networks

---

## 🌟 Why This System?

### ✅ No Database Setup Required
Uses Google Sheets - familiar and easy to manage

### ✅ Real-Time Collaboration
Multiple engineers can submit data simultaneously

### ✅ Zero Infrastructure Cost
No servers, no hosting fees - runs on Google's infrastructure

### ✅ Easy Backup & Recovery
Google Sheets automatic backup and version history

### ✅ Instant Deployment
Deploy in minutes - no complex installation

### ✅ Scalable
Add unlimited sites without system changes

### ✅ Secure
Site-based authentication and data isolation

### ✅ Exportable Data
Download to Excel/CSV anytime for offline analysis

---

## 📸 Screenshots

### Login Screen
Secure site-based authentication with password protection
<img width="768" height="774" alt="image" src="https://github.com/user-attachments/assets/205b1af1-2e1d-44e0-99f0-de9aac710c9d" />


### Dashboard
Quick access to data entry and historical data viewing
<img width="783" height="598" alt="image" src="https://github.com/user-attachments/assets/69cb06b8-2696-42a6-bf4d-f44115acfe3c" />


### Data Entry Form
Comprehensive form for all concrete testing parameters
<img width="1904" height="759" alt="image" src="https://github.com/user-attachments/assets/4f12776c-fb53-4cb5-8aca-c3ec97eb305e" />
<img width="1905" height="676" alt="image" src="https://github.com/user-attachments/assets/a65ea326-04a2-499b-8b73-dcb4c4fbbc80" />


### Data Viewer
Search, filter, and analyze historical test data with statistics
<img width="1899" height="1031" alt="image" src="https://github.com/user-attachments/assets/9133fdff-87a5-4994-8764-e7c8414d0e4b" />

---

## 🎯 Target Users

- **Construction Site Engineers**
- **Quality Control Managers**
- **Project Managers**
- **Lab Technicians**
- **Construction Companies**
- **Concrete Suppliers**
- **Testing Laboratories**

---

## 🔒 Data Security

- Site-specific password protection
- Data isolation between sites
- Secure HTTPS communication
- Google's enterprise-grade security
- Access logging and audit trails
- Regular backup via Google Sheets

---

## 📈 Benefits

### For Management
- Centralized oversight of all sites
- Real-time quality monitoring
- Compliance documentation
- Performance analytics

### For Engineers
- Fast data entry
- Mobile-friendly interface
- Historical data access
- No training required

### For Organization
- Reduced paperwork
- Data standardization
- Cost-effective solution
- Scalable infrastructure

---

## 📞 Licensing & Contact

**© 2026 [Shanaka Rajapakse]. All Rights Reserved.**

This is **proprietary software**. For licensing information, pricing, or demo:

📧 **Email**: rajapaksheshanaka@gmail.com
🔗 **LinkdIn**: www.linkedin.com/in/shanaka-rajapakse

---

## ⚖️ Legal Notice

This software is proprietary and confidential. Unauthorized use, copying, modification, or distribution is strictly prohibited and may result in legal action.

All intellectual property rights are reserved by the copyright holder.

---

**Made for the Construction Industry | Professional Quality Control Solution**
