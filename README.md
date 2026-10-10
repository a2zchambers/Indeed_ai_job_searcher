# Indeed_ai_job_searcher


Here is a complete, structured overview and description of all **8 Phases and Core Features** built into your repository.

You can copy and paste this directly into your GitHub repository's `README.md` file to give anyone viewing your project a clear, professional breakdown of what your Autonomous Job Agent achieves:

---

# 🎯 Autonomous Resume-Driven Job Agent & Career Command Center (`raw-features`)

An intelligent, end-to-end Python & Streamlit application that transforms a master resume into a multi-stream automated job search, tracking, entity verification, and interview-prep powerhouse.

---

## 🛠️ The 8-Phase Architectural Suite

### Phase 1: Resume DNA & Core Competency Extraction Engine

* **What it does:** Parses uploaded master resumes (`.pdf` or `.docx`) to decode your core professional skills (e.g., Python, SQL, Financial Modeling, Credit Underwriting).
* **Key Capability:** Automatically checks for elite institutional pedigree (e.g., Bulge Bracket banks) and maps out functional search streams tailored explicitly to your background.

### Phase 2: Autonomous Multi-Stream Scraper & Match Scoring

* **What it does:** Automatically constructs target search URLs based on your extracted resume DNA and launches a headless browser automation driver (Selenium + BeautifulSoup) to scan multiple job streams simultaneously.
* **Key Capability:** Evaluates custom guardrails (stripping senior executive noise or missing professional licenses) and calculates an algorithmic match score (0–98% fit) for every discovered listing.

### Phase 3: Entity Precision & Geo-Location Parser

* **What it does:** Deploys targeted DOM attributes and regular expression fallback logic to cleanly isolate precise data fields directly from chaotic job card blocks.
* **Key Capability:** Separates and cleans exact **Company Names**, **City/State locations**, and **Street Addresses** while avoiding generalized landing pages.

### Phase 4: Advanced Filtering, Sorting & Freshness Alerts

* **What it does:** Provides a comprehensive control panel right inside your tracking dashboard.
* **Key Capability:** Allows multi-criteria sorting (by match score, salary, date saved, or alphabetical order), workplace-type filtering (Remote, Hybrid, On-site), threshold score sliders, and automated **Freshness Alerts** warning you of stale applications (>14 days without movement).

### Phase 5: Auto-Apply & Outreach Hub

* **What it does:** Unlocks specialized generation tools the moment you shift a job's status to **Applied** or **Interviewing**.
* **Key Capability:** Instantly compiles tailored cover letters, recruiter outreach scripts for LinkedIn or email, and structured post-interview follow-up templates.

### Phase 6: AI Salary Estimator & Analytics Suite

* **What it does:** Supercharges your tracking dashboard with high-level intelligence and export capabilities.
* **Key Capability:** Automatically benchmarks and assigns estimated NYC market pay rates if a listing lacks explicit salary data, provides a top-line metrics analytics banner, offers persistent private notes/interview logs per card, and features a **One-Click CSV/Excel Export Center**.

### Phase 7: Hiring Manager Intelligence & Strategic Positioning

* **What it does:** Transforms your tracking tool into an executive networking command center.
* **Key Capability:** Maintains a dedicated dossier for Hiring Manager contact points (Name, Email, Phone, LinkedIn) alongside personal rapport hooks (Hobbies, Trips, Favorite Foods). It also decodes corporate missions and builds an interview solution blueprint positioning you as the company's ideal fix.

### Phase 8: AI Interview Simulator & STAR Coach

* **What it does:** Acts as your personal mock interview coach before you step into a conversation.
* **Key Capability:** Generates role-specific technical and behavioral Q&A pairs tailored to the company description, complete with suggested **STAR-method talking points** pulled directly from your resume history.

---

## 🚀 Core Technical Features Summary

* **Strict Entity Verification & Sanitization Guardrails:** Stops hallucinations and data mix-ups (ensuring company names never get confused with job titles or salaries).
* **Anti-About Page URL Validator:** Intentionally filters out generalized corporate directory hubs or review pages, ensuring links point directly to active, unique job postings.
* **Secure Local Database Architecture:** Utilizes SQLite (`autonomous_jobs_v2.db`) with automatic schema migration to keep all your notes, pipeline statuses, and dossiers safely stored locally.
