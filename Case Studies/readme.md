# Case Study – AI‑Detection Bias Against English‑Language Learners (ELL)  
*Based on the article by Tara García Mathewson (The Markup)*  

---

## Author  

**Tara García Mathewson** – technology writer for *The Markup* (online publication).  

---

## Topic  

How AI‑detection tools show significant bias against **English‑Language Learners (ELL)**, producing false plagiarism/AI accusations at disproportionate rates.  

---

## Summary  

AI detectors disproportionately return false positives for ELL students.  
The primary cause is the way these algorithms are trained—largely on native‑speaker data.  

- **Stanford study** (Myers 2023) found a **false‑positive rate > 61 %** for essays written by ELLs.  
- Another study reported that essays by ELLs were **more than twice as likely** to be flagged as AI‑generated compared with native‑speaker essays (Blog 2024).  

A real‑world incident at **Johns Hopkins University** illustrates the problem: an international student was wrongly accused of using AI by Turnitin’s detector. Professor **Taylor Hahn** intervened, and the student had to prove the work was original. A second student, also an ELL, experienced the same outcome after receiving help with outlines and drafts.  

Many companies have **paused or removed** their AI detectors pending further research, most notably **OpenAI** (Carter 2023; Coldewey 2023; Epstein‑Gross 2023; Forlini 2023; Mathewson 2023; Northwestern University 2025; Quill.org 2025; Rifalixa 2023).  

Turnitin introduced a feature allowing institutions to **disable** its AI detector; as of July 2023, only **2 %** of Turnitin‑using institutions had activated it (Mathewson 2023). In May 2024, the **top 20 U.S. universities** advised against using AI detectors (Rumi 2024).  

Some educators (e.g., University of Pittsburgh) have declared that AI detectors “could do more harm than good” (Furze 2024; Mathewson 2023, 2025).  

The case shows how biased detection tools can **jeopardize students’ legal status** and **erode trust** in academic institutions.

---

## Stakeholders  

1. **International students / English‑language learners** – primary victims; false positives can lead to **deportation** (Castellanos‑Canales 2025; University of Rochester 2025).  
2. **Prof. Taylor Hahn** (Johns Hopkins) – observed Turnitin’s bias and highlighted the problem.  
3. **Turnitin** – provider of the AI detector; claims its tool “does not make a determination of misconduct” but supplies data for educators (Walters 2023).  

   > *“Crucially, Turnitin Originality does not make a determination of misconduct through our AI writing detection (or similarity checking) technology… we provide data for educators to make an informed decision based on their academic and institutional policies.”*  

4. **Administrative personnel at Johns Hopkins** – supervise faculty, must understand detector impacts and devise solutions.  
5. **National, state, and local governments** – responsible for training and regulating AI‑detector use; must understand effectiveness and policies, including “AI humanizers.”  

---

## Broader Issues  

- **Algorithmic efficiency vs. equity** – false positives for ELL raise civil‑rights concerns, risk of discipline or deportation, and legitimate AI uses.  
- **Training data bias** – detectors were trained mainly on native‑speaker writing, leading to misclassification of ELL essays.  
- **Underlying questions** – why do false positives occur (SkylineAcademic 2025)? Why do some instructors assume heavy AI use and thus deploy detectors? If students do use AI, why do they feel compelled?  

Other technologies show similar bias patterns:  
- **Automated scoring** has **much less bias** against ELL (Guo et al., 2025).  
- **Facial‑recognition** is known to be unreliable for people of color, women, and non‑binary individuals (Fergus 2024).  

---

## Importance  

Bias against ELL can stem from training data or algorithm design. Fixing it for this group is feasible and can spark broader discussions on **ethical AI development** (Williams 2025).  

The issue aligns with the **AI Bill of Rights** (White House 2022) – see the *Human Alternatives, Consideration, and Fallback* section. The EU’s *Ethics Guidelines for Trustworthy AI* warn that marginalising vulnerable groups **exacerbates prejudice and discrimination** (European Union 2019).  

A false positive could **revoke a student’s visa** and lead to deportation (Castellanos‑Canales 2025; University of North Carolina Charlotte 2025; University of Minnesota 2025; University of Rochester 2025; VnExpress 2025). Therefore, AI detectors **must never be the sole proof** of AI use.

---

## Appendix I – AI Usage  

*Portions copied from a previous policy paper.*

| # | Tool | Purpose / Notes |
|---|------|-----------------|
| 1 | **Grammarly** (<https://app.grammarly.com/>) | Spell‑check & grammar; suggested wording changes (not always accepted). |
| 2 | **Google summaries** | Locate relevant case studies & sources. |
| 3 | **EndNote 2025‑1** (<https://endnote.com/>) | Build bibliography & in‑text citations; APA style with line‑number support. |
| 4 | **Lumo (Proton)** (<https://lumo.proton.me/>) | Evaluated the case study against the rubric. <br>**Conversation link:** <https://lumo.proton.me/u/0/c/2d757bf6-a2df-457a-a72d-fd07976bd148> <br>**Prompt:** “Evaluate the case study using the Rubric provided.” |
| 5 | **Perplexity (Comet Assistant)** | Search for additional sources. |

> *The various AI tools were used to locate sources, annotate the document (EndNote), and check spelling/grammar (Grammarly). While the paper could have been completed without AI, using AI streamlined resource discovery and error checking.*

---

## Appendix II – Data  

### Copyleaks (Blog 2024) Datasets  

| Dataset | Texts | False Positives | Accuracy |
|---------|-------|-----------------|----------|
| **FCE v2.1** | 2,116 | 4 | 0.9981 |
| **ELLs** | 3,911 | 0 | 1.0000 |
| **COREFL** | 1,455 | 8 | 0.9945 |
| **Total** | 7,482 | 12 | 0.9984 |

### Stanford (Myers 2023)  

| Sample | Source | Type | Generated by | Website |
|--------|--------|------|--------------|---------|
| 91 essays | Chinese TOEFL | Human | — | <https://arxiv.org/pdf/2304.02819.pdf> |
| 88 essays | Hewlett Foundation’s ASAP dataset (US 8th‑grade) | Human | — | <https://www.kaggle.com/competitions/asap-aes> |

*Further code and data:* <https://github.com/Weixin-Liang/ChatGPT-Detector-Bias/tree/v1.0.0> (Liang et al., 2023).  

---

## Appendix III – Complete Lumo Conversation  

*See the link in Appendix I (item 4) for the full transcript.*  

---

## Appendix IV – Bibliography  

1. **Berman, L.** (2025). *Professors shift many essay‑based assessments to in‑person exams amid AI concerns.* https://www.tuftsdaily.com/article/2025/10/professors-shift-many-essay-based-assessments-to-in-person-exams-amid-ai-concerns  
2. **Blog.** (2024). *Evaluating AI Detection Accuracy for Non‑Native English Writers.* Copyleaks. https://copyleaks.com/blog/accuracy-of-ai-detection-models-for-non-native-english-speakers  
3. **Carter, T.** (2023). *Some universities are ditching AI detection software amid fears students could be falsely accused of cheating by using ChatGPT.* Business Insider. https://www.businessinsider.com/universities-ditch-ai-detectors-over-fears-students-falsely-accused-cheating-2023-9  
4. **Castellanos‑Canales, A.** (2025). *Explainer: Revocation of Student Visas and Termination of SEVIS Records.* National Immigration Forum. https://forumtogether.org/article/explainer-revocation-of-student-visas-and-termination-of-sevis-records/  
5. **Coldewey, D.** (2023). *OpenAI scuttles AI‑written text detector over ‘low rate of accuracy’.* TechCrunch. https://techcrunch.com/2023/07/25/openai-scuttles-ai-written-text-detector-over-low-rate-of-accuracy/  
6. **Corrigan, S.** (2024). *Top 7 AI Tools for Language Teachers and Language Learners.* ATC Language Schools. https://atclanguageschools.com/top-7-ai-tools-for-language-teachers-and-language-learners/  
7. **Epstein‑Gross, C.** (2023). *OpenAI Abruptly Shuts Down ChatGPT Plagiarism Detector—and Educators Are Worried.* Observer. https://observer.com/2023/07/openai-shut-ai-classifier/  
8. **European Union.** (2019). *Ethics guidelines for trustworthy AI – Shaping Europe’s digital future.* https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai  
9. **Fergus, R.** (2024‑02‑29). *Biased Technology: The Automated Discrimination of Facial Recognition | ACLU of Minnesota.* https://www.aclu-mn.org/en/news/biased-technology-automated-discrimination-facial-recognition  
10. **Forlini, E.** (2023‑07‑25). *OpenAI Quietly Shuts Down AI Text‑Detection Tool Over Inaccuracies.* PCMag. https://www.pcmag.com/news/openai-quietly-shuts-down-ai-text-detection-tool-over-inaccuracies  
11. **Furze, L.** (2024). *AI Detection in Education is a Dead End.* Leon Furze. https://leonfurze.com/2024/04/09/ai-detection-in-education-is-a-dead-end/  
12. **Guo, S. et al.** (2025). *Artificial Intelligence Bias on English Language Learners in Automatic Scoring.* https://doi.org/10.48550/arXiv.2505.10643  
13. **Liang, W. et al.** (2023). *GPT detectors are biased against non‑native English writers.* https://doi.org/10.48550/arXiv.2304.02819  
14. **Markey, E.** (2024). *Senator Markey Introduces AI Civil Rights Act to Eliminate AI Bias…* https://www.markey.senate.gov/news/press-releases/senator-markey-introduces-ai-civil-rights-act-to-eliminate-ai-bias-enact-guardrails-on-use-of-algorithms-in-decisions-impacting-peoples-rights-civil-liberties-livelihoods  
15. **Mathewson, T. G.** (2023‑08‑14). *AI Detection Tools Falsely Accuse International Students of Cheating – The Markup.* https://themarkup.org/machine-learning/2023/08/14/ai-detection-tools-falsely-accuse-international-students-of-cheating  
16. **Mathewson, T. G.** (2025‑06‑26). *Turnitin helps colleges detect AI writing — but its cost is more than just a price tag.* CalMatters. https://laist.com/news/education/california-colleges-spend-millions-to-catch-plagiarism-and-ai-is-the-faulty-tech-worth-it  
17. **Myers, A.** (2023). *AI‑Detectors Biased Against Non‑Native English Writers | Stanford HAI.* https://hai.stanford.edu/news/ai-detectors-biased-against-non-native-english-writers  
18. **Northwestern University.** (2025). *Use of Generative Artificial Intelligence in Courses.* https://ai.northwestern.edu/education/use-of-generative-artificial-intelligence-in-courses.html  
19. **Orr, D.** (2022). *The Unintended Consequences of Algorithmic Bias.* Congressional Black Caucus Foundation.  
20. **Quill.org.** (2025). *AI Writing Check.*  
21. **Riess, K.** (2025). *OCR Weighs In On Discriminatory AI Use.* King, Spry, Herman, Freund & Faul, LLC. https://kingspry.com/ocr-weighs-in-on-discriminatory-ai-use/  
22. **Rifalixa.** (2023‑07‑25). *OpenAI quietly shuts down its AI detection tool due to poor accuracy.* Reddit. https://www.reddit.com/r/GPT3/comments/159eoqq/openai_quietly_shuts_down_its_ai_detection_tool/  
23. **Rumi.** (2024). *Top 20 US Schools Recommend Against AI Detectors.* https://www.rumidocs.com/newsroom/top-20-us-schools-recommend-against-ai-detectors  
24. **SkylineAcademic.** (2025). *Are AI Detectors Accurate? What My Tests On 1,000 Essays Revealed.* https://skylineacademic.com/are-ai-detectors-accurate-what-my-tests-on-1000-essays-revealed/  
25. **Stanford, L.** (2025‑09‑15). *Connecticut Professors Fear Dependence, Cognitive Decline Over AI Use.* GovTech. https://www.govtech.com/education/higher-ed/connecticut-professors-fear-dependence-cognitive-decline-over-ai-use  
26. **Supiano, B.** (2023‑04‑05). *Will ChatGPT Change How Professors Assess Learning?* Chronicle of Higher Education. https://www.chronicle.com/article/will-chatgpt-change-how-professors-assess-learning?utm_source=Iterable&utm_medium=email&utm_campaign=campaign_6572262_nl_Academe-Today_date_20230410&cid=at&source=&sourceid=&cid2=gen_login_refresh  
27. **University of North Carolina Charlotte.** (2025). *Dismissal, Academic Integrity, & Visa Consequences.* International Student and Scholar Office.  
28. **University of Minnesota.** (2025). *Accruing Unlawful Presence for F‑1 Students | ISSS.*  
29. **University of Rochester.** (2025). *International Students.* https://www.rochester.edu/college/honesty/students/international.html  
30. **VnExpress.** (2025). *How an alleged AI mistake nearly cost a Japanese student his US visa.* https://e.vnexpress.net/news/news/education/how-an-alleged-ai-mistake-nearly-cost-a-japanese-student-his-us-visa-4878219.html  
31. **Walters, W.** (2023). *The Effectiveness of Software Designed to Detect AI‑Generated Writing: A Comparison of 16 AI Text Detectors.* https://www.degruyterbrill.com/document/doi/10.1515/opis-2022-0158/html  
32. **Weixin Liang et al.** (2023). *AI‑Detectors Biased Against Non‑Native English Writers.* https://arxiv.org/abs/2304.02819  
33. **White House.** (2022). *Blueprint for an AI Bill of Rights | OSTP.* https://bidenwhitehouse.archives.gov/ostp/ai-bill-of-rights/  
34. **Williams, R.** (2025). *Algorithmic Justice League – Unmasking AI harms and biases.*  

4 files
