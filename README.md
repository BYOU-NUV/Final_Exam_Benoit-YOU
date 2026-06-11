# Final Exam Practical - ITDI204 Cloud Computing

## Student information

**Student name:** Benoit YOU

**GitHub repository URL:** https://github.com/BYOU-NUV/Final_Exam_Benoit-YOU

**Render application URL:** https://final-exam-benoit-you.onrender.com/

---

## Application information

**Application name:** Final Exam - Benoit YOU

**Render project name:** Final Exam - Benoit YOU

**Branch used for production deployment:** **main**

**Staging branch name:** **staging**

---

## Deployment configuration

**Build command:** **npm install**

**Start command:** **npm start**

**Environment variable MSG:** **Final Exam**

**Environment variable ENV:** **Production**

---

## API endpoints to test

### Presentation endpoint

**URL:** https://final-exam-benoit-you.onrender.com/presentation

**Expected result:** Final Exam - Production

### Correction endpoint

**URL:** *https://final-exam-benoit-you.onrender.com/correction*

**Error after first call:** Internal Server Error

**Expected result after correction:** Correction endpoint is working

---

## Error detection

Briefly explain what you corrected and how you moved the correction from staging to production.

**Explanation:**  
I can look directly in the Gitbub action and look where it was in error. Seing that the test on the API correction is error, I know that I have to correct it.
