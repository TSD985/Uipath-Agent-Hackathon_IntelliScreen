## 🤖 IntelliScreen – Automated Resume Screening System
### 📘 Overview
IntelliScreen is an AI + RPA-powered recruitment automation system built using UiPath Studio Web.
It streamlines the hiring process by automatically scanning resumes received via email, analyzing candidate profiles, classifying applicants, and generating personalized communication workflows.

The system reduces manual screening effort, improves consistency in candidate evaluation, and enhances recruitment efficiency through intelligent automation.

### 🧩 Problem Statement
Recruiters often receive hundreds of resumes for a single role, making manual screening slow, repetitive, and error-prone.

Traditional recruitment workflows can:
1. Consume significant HR time
2. Delay candidate responses
3. Cause inconsistent evaluations
4. Overlook qualified talent
5. Reduce overall hiring efficiency

IntelliScreen addresses these challenges using AI-powered resume analysis combined with UiPath RPA automation.

### 🚀 Key Features
1. Smart Email Monitoring
- Automatically scans incoming emails and identifies resume attachments using subject-based filtering.
2. AI Resume Classification
Analyzes resumes and categorizes candidates into:
- Suitable
- Borderline
- Not Suitable
3. Context-Aware AI Agents
Agents are trained using:
- Job descriptions
- Expected skills
- Resume format examples
- Hiring criteria
This improves classification accuracy and decision consistency.
4. Candidate Information Extraction
Extracts candidate details such as:
- Name
- Email
- Resume summary
- ATS insights
5. Personalized Automated Communication
- Suitable/Borderline candidates receive confirmation emails and interviewer forwarding.
- Not Suitable candidates receive rejection reasons, ATS feedback, and improvement suggestions.
6. Flexible Automation Triggers
Supports:
- Manual execution
- Event/email-triggered execution

---

⚙️ Workflow Architecture
Monitor inbox for incoming resumes
Download and process attachments
Extract resume content using Document Understanding
Send extracted data to AI agents
Generate candidate classification and summary
Extract applicant information
Send automated personalized responses
Forward shortlisted candidates to recruiters/interviewers
🛠️ Tech Stack
UiPath Studio Web
UiPath Orchestrator
UiPath Mail Activities
UiPath PDF Activities
UiPath Document Understanding
UiPath Integration Service
UiPath Context-Grounded Agents
💼 Use Cases
Recruitment Automation
Campus Placement Drives
HR Resume Screening
Staffing Agencies
Internal Hiring Processes
Bulk Candidate Evaluation
🎯 Project Highlights

✅ AI + RPA integrated workflow
✅ Personalized candidate communication
✅ Automated ATS-style evaluation
✅ Context-grounded intelligent agents
✅ Multiple resume format support
✅ Reduced manual HR effort
✅ Consistent candidate screening process

📚 Learning Outcomes

This project helped in gaining practical experience with:

AI-powered recruitment workflows
UiPath Studio Web automation design
Document Understanding pipelines
Email automation systems
Context-grounded AI agents
Orchestrator-based automation management
Real-world HR automation use cases
🔮 Future Improvements
Integration with HRMS platforms
Resume ranking dashboard
Multi-role job matching
Analytics & hiring insights
Candidate tracking portal
Interview scheduling automation
📂 Repository Contents
.uis workflow files
Resume samples
Agent configurations
Workflow diagrams
Supporting JSON/context files
