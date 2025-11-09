## 📋 Submission Information

**Name:** Mert ACAR  

**Email:** mertacareee@gmail.com

**LinkedIn:** [[linkedin.com/in/yourprofile]   ](https://www.linkedin.com/in/mert-acar-293781234/)

**Submission Date:** [2025-11-09]

---

## ✅ Deliverables Checklist

Please confirm you've included all required items:

- [x] **Report** (PDF, max 5 pages)
  - [x] Section 1: Incident Analysis
  - [x] Section 2: Architecture Review
  - [x] Section 3: Response & Remediation
  
- [x] **Video Presentation** (10-15 minutes)
  - [x] Link provided in `video_link.md`
  - [x] Video is accessible (tested in incognito)
  - [x] Duration is within guidelines

- [x] **File Structure**
```
  submissions/firstname-lastname/
  ├── report.pdf
  ├── video_link.md
  └── notes.md (optional)
```

---

## 📊 Self-Assessment

**Time spent on this lab:** Approximately 9 hours

**Tools used:**
- Log analysis: Google Sheets
- Diagrams: Draw.io
- Video recording: OBS

**Confidence level:**
- [x] Very confident in my analysis
- [ ] Confident but some uncertainties
- [ ] Attempted my best with available knowledge

---

## 🎯 Brief Summary (2-3 sentences)

On October 15, 2024, multiple security events were observed across email, API, WAF, and web
application logs, initially flagged as potential compromise. Subsequent correlation with the Q4

2024 Scheduled Security Testing document revealed these activities to be unscheduled pene-
tration testing conducted by CyberSec Partners using the approved IP range 203.0.113.0/24.

Despite written approval of the IP block, no 48-hour pre-confirmation was provided, violating
procedural controls.

---

## 🔍 Key Findings Highlight

**Main attack vectors identified:**
1. IDOR in API
2. SQL Injection in Web APP
3. Phishing in Emails

**Most critical vulnerability:**
SQL Injection in WEB APP

**Top recommendation:**
Migrate all database interactions to ORM with prepared statements.

---

## 💭 Challenges & Learnings

**What was most challenging?**

It was challenging to find the attacker's initial point of entry and to determine how the three separate attacks were connected.

**What did you learn?**

I learned that an email, which appears to be innocent, can steal user information, and that when a vulnerability in the system combines with other flaws, it can snowball. To prevent this, the entire system needs to be equally secure across all areas.

**What would you do differently?**

If I had read the documents provided in the Materials section more carefully, I could have completed my work in a shorter time.

---

## 📝 Additional Notes _(optional)_

Any context, assumptions, or additional information you'd like evaluators to know:

[Write here]

---

## ⚖️ Declaration

I declare that:
- [x] This work is entirely my own
- [x] I have not copied from other submissions or answer keys
- [x] I have not modified the provided log files
- [x] All sources and tools are properly attributed
- [x] I understand plagiarism results in disqualification

**Signature:** Mert ACAR 
**Date:** 2025-11-09

---

## 🚀 Ready for Review

By submitting this PR, I confirm that my work is complete and ready for evaluation.

---

_Thank you for your submission! Our team will review it within 1 week._
