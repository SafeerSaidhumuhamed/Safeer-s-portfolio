# 📝 Impact of Paraphrasing Tools on Plagiarism Detection Systems

## 🎯 Project Overview

This project is the code and analysis behind my MSc Data Analytics dissertation:

**“Impact of Paraphrasing Tools on Plagiarism Detection Systems: Helping Universities and Industries Strengthen Academic Integrity”**

The goal isn’t to *trick* plagiarism detectors, but to **evaluate their effectiveness** against modern paraphrasing tools — and provide actionable insights to improve them.

---

## 🌍 Why This Matters

Plagiarism detection systems are a cornerstone of academic integrity in universities and content authenticity in industries.  
With AI-powered paraphrasing tools becoming more sophisticated, understanding their impact on detection accuracy is essential for:

- **Educators** — designing better assessment strategies  
- **Detection platform developers** — closing loopholes and enhancing algorithms  
- **Industry professionals** — safeguarding intellectual property

This research acts as a **benchmark** to show where detection systems excel and where they need upgrades.

---

## 🧠 Research Goals

- Compare plagiarism detection performance across multiple paraphrasing tools.
- Identify gaps where paraphrased content bypasses detection.
- Recommend improvements based on statistical and visual analysis.

---

## 🛠 Tools & Technologies

| Category | Tools |
|----------|-------|
| **Languages** | Python, SAS |
| **Python Libraries** | Pandas, NumPy, Matplotlib, Seaborn |
| **Paraphrasing Tools** | QuillBot, Scribbr, Paraphraser.io, ChatGPT |
| **Detection Tools** | Grammarly, Check-Plagiarism |
| **Other** | Jupyter Notebook |

---

## 📊 Methodology

1. **Data Collection** — Extracted original text samples from Wikipedia.  
2. **Paraphrasing** — Rewrote samples using multiple AI/web-based paraphrasers.  
3. **Plagiarism Testing** — Measured similarity scores via Grammarly and Check-Plagiarism.  
4. **Data Recording** — Logged results in structured datasets.  
5. **Analysis** —  
   - Visual comparisons of similarity scores.  
   - Statistical validation (t-tests, F-tests) using SAS.  

---

## 🏆 Key Insights

- Grammarly generally produced **higher and more consistent similarity scores**, especially for Scribbr-generated paraphrases.
- Check-Plagiarism sometimes returned **zero similarity** for AI-generated paraphrases, showing potential blind spots.
- Statistical tests revealed **no significant difference** between the two detection systems — suggesting the need for algorithmic refinement.
- Visualizations uncovered trends in detection strength and weakness by paraphrasing method.

---
