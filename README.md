# JanSetu — Rural Panchayat Grievance Management System

**Bridging Citizens and Governance Through Technology.**

A digital platform designed to modernize rural grievance management by connecting citizens, Panchayat administrators, supervising officers, and field workers through a transparent and structured complaint-resolution system.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

---

## About the Project

In rural communities, reporting civic issues and receiving timely resolutions can be challenging due to manual processes, limited communication channels, and the absence of effective complaint-tracking mechanisms.

**JanSetu** addresses this gap through a centralized web application that digitizes the grievance redressal process. Citizens can report public-service issues, track complaints, and provide feedback, while Panchayat officials can manage assignments, supervise fieldwork, and verify completed resolutions.

The platform aims to make rural governance more accessible, organized, and accountable.

## Key Features

**Citizen Management**
- Secure registration and login.
- Submit grievances with descriptions, categories, locations, and supporting images.
- Unique grievance reference IDs.
- Track complaint progress and view grievance history.
- Confirm resolutions and submit feedback.

**Administrative Management**
- Centralized grievance management dashboard.
- Review, categorize, and assign complaints.
- Department and personnel management.
- Monitor complaint priorities and progress.
- Publish public announcements and emergency notices.

**Field Operations & Verification**
- Dedicated worker and officer portals.
- Manage assigned field tasks.
- Submit progress updates and photographic evidence.
- Officer review and resolution verification.
- Citizen confirmation through the verification workflow.

**Monitoring & Accessibility**
- Interactive analytics and visual reports.
- Ward-wise and category-wise grievance monitoring.
- In-app notifications.
- English and Telugu language support.
- Responsive interface for desktop and mobile devices.

## How It Works

JanSetu follows a structured grievance-resolution lifecycle:

**Register → Review → Assign → Resolve → Verify → Close**

1. Citizens register complaints through the platform.
2. Administrators review and assign grievances to relevant personnel.
3. Field workers address the reported issues and upload completion evidence.
4. Supervising officers review the submitted evidence.
5. Citizens participate in the resolution confirmation process.
6. Verified grievances proceed towards final closure and feedback.

## Technology Stack

| Layer | Technologies |
|---|---|
| Backend | Python, Flask |
| Frontend | HTML5, CSS3, JavaScript |
| Database | SQLite |
| Visualization | Chart.js |
| Templating | Jinja2 |
| Security | Werkzeug, Role-Based Access Control |

## Project Architecture

The application follows a modular architecture to maintain separation of responsibilities and simplify development and maintenance.

```text
JanSetu/
│
├── agent/          # AI prompts, rules and workflows
├── core/           # Configuration, database and security
├── docs/           # Technical documentation
├── routes/         # Application routes and endpoints
├── services/       # Business logic and application services
├── scripts/        # Database utilities and test suites
├── static/         # CSS, JavaScript and assets
├── templates/      # Dynamic HTML templates
│
├── app.py          # Application entry point
├── database.py     # Database utilities
├── requirements.txt
└── run.bat
```

## Getting Started

### Prerequisites
- Python 3.10 or later
- Git
- Web browser

### Installation

**1. Clone the repository**

```bash
git clone <YOUR_REPOSITORY_URL>
cd JanaSetu
```

**2. Create and activate a virtual environment**

```bash
python -m venv venv
venv\Scripts\activate
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Configure environment variables**

Use `.env.example` as a reference and configure the required application settings.

**5. Run the application**

```bash
python app.py
```

Open your browser at:

`http://127.0.0.1:5000`

## Security & Reliability

- Password hashing and secure authentication.
- Role-based access restrictions.
- Parameterized database queries.
- Input validation and controlled file uploads.
- Protected access to grievance evidence.
- Structured grievance status management.

## Community Impact

JanSetu aims to strengthen the connection between rural citizens and local administration by introducing a more accessible and transparent grievance-handling process.

By digitizing complaint registration, assignment, monitoring, and verification, the project supports citizen participation, administrative accountability, and improved visibility into public-service issues.

## Future Enhancements

- AI-assisted grievance classification and prioritization.
- Automated complaint escalation and SLA monitoring.
- Integrated SMS and voice notifications.
- Location-based grievance visualization.
- Progressive Web App support.

---

<p align="center">
  <strong>JANSETU</strong>
  <br/>
  <em>Technology for Communities. Transparency for Everyone.</em>
  <br/><br/>
  <sub>Developed as part of the Community Service Project (CSP).</sub>
</p>
