# 🎯 Mentor Session Performance & Optimization Tracker  
### *AI-Augmented Insights for Scaler Mentorship Program*  
---

## 📘 Overview  
This project analyzes **120+ Scaler mentorship sessions** to identify inefficiencies and improve mentor performance, learner satisfaction, and program management.  

Using **Python, NLP, and visualization dashboards**, it integrates AI to automate session summaries, detect sentiment in learner feedback, and flag early warnings — helping Program Managers proactively improve session quality.

---

## 🧩 Problem Statement  
Unstructured mentorship sessions and missing feedback led to:
- Inconsistent learner satisfaction  
- Low follow-up completion  
- Weak documentation and limited data insights  

> **Key Stats:**
> - Session Completion Rate: 55.8%  
> - Average Rating: 3.64 / 5  
> - Missing Feedback: 58.3%  
> - Follow-up Scheduled: Only 41.7%  
> - Negative Feedback: 5.8% of total  

---

## 🚀 Solution Design – Structured Mentorship Framework  
A **3-phase mentorship model** was proposed to improve accountability and engagement:

### 🟦 1. Pre-Session (Preparation)
- AI-generated agendas using learner data.  
- Mentor & learner checklists.  
- Smart topic recommendations from prior feedback.  
✅ *Expected Impact: Improved mentor preparedness & reduced cancellations.*

### 🟩 2. In-Session (Engagement)
- Real-time tracking of engagement and attendance.  
- AI-powered note-taking (speech-to-text + summarization).  
- Structured conversation flow.  
✅ *Expected Impact: Better engagement & documentation.*

### 🟧 3. Post-Session (Follow-Up)
- Automated session summaries emailed to mentors and learners.  
- Follow-up scheduling triggers for low sentiment or unresolved goals.  
✅ *Expected Impact: Continuity, accountability, and improved retention.*

---

## 🤖 AI Integration & Automation

### 🧠 Prototype 1: Feedback Sentiment Analyzer
**Objective:** Detect negative learner experiences automatically.  
**Tech:** `TextBlob`, `Seaborn`, `Pandas`  

**Outputs:**
- Classifies feedback as *Positive / Neutral / Negative*  
- Visual correlation between sentiment and ratings  

**Results:**
| Sentiment | % Feedback | Avg Rating |
|------------|-------------|-------------|
| Neutral | 65.8% | 3.84 |
| Positive | 28.3% | 3.59 |
| Negative | 5.8% | 3.14 |

> 🪄 *Enables early intervention by flagging “Negative” sessions within 24 hours.*

---

### 🤖 Prototype 2: Smart Session Summary Generator
**Objective:** Automate session documentation for mentors & PMs.  
**Tech:** `KeyBERT`, `NLP`, `Python`  

**Functionality:**
- Extracts key terms from learner feedback.  
- Auto-generates structured summaries in CSV for dashboards.  

**Example Output:**
> - Sneha Reddy conducted a Resume Review session. Limited learner feedback available.  
> - Session on Career Guidance by Vikram Singh highlighted “motivation, clarity, roadmap.”  

✅ *Saves 5–7 minutes per session & standardizes weekly reporting.*

---

## 📊 Dashboard Insights (Power BI / Excel)
<img width="1371" height="769" alt="image" src="https://github.com/user-attachments/assets/36983ff5-30ea-4200-97b2-ddb9d4725086" />

**Dashboard Features:**
- **Average Rating by Month**  
- **Bottom 5 Mentors by Rating vs Follow-Up**  
- **Feedback Sentiment Analysis**  
- **Early Warning Flags per Mentor**  
- **Key KPIs:** Total Sessions, Avg. Rating, Prep %, Follow-up %  

**Example Metrics:**
| Metric | Value |
|--------|--------|
| Total Sessions | 120 |
| Completed Sessions | 67 |
| Avg. Rating | 3.64 |
| Mentor Prep Done | 56.67% |
| Follow-Up Scheduled | 41.67% |
| Negative Feedback Count | 7 |

---

## 🧭 Early Warning Tracker  
**Goal:** Identify risky sessions early.  

Rules used for flagging:
- Low Rating (<3)  
- No Mentor Preparation  
- No Follow-up  
- Negative Feedback  

> **Color Codes:**  
> 🟩 All Good | 🟨 Mild Attention | 🟥 Urgent Follow-Up  

✅ Enables Program Managers to act proactively using Power BI or Excel dashboard.

---

## ⚙️ Tech Stack  
| Category | Tools / Libraries |
|-----------|-------------------|
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Power BI |
| **NLP & AI** | TextBlob, KeyBERT |
| **Automation** | Python Scripts, CSV/Excel Export |
| **Deployment Ready** | Google Colab / Jupyter Notebook |

---

## 🧮 Project Workflow  
```text
Data Cleaning → Descriptive Stats → Sentiment Analysis → 
Keyword Extraction → AI Summaries → KPI Metrics → 
Early Warning Dashboard
