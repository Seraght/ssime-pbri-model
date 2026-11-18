# SSIME PBRI Model: Stroke Integration AI Project
**AI Foundations for Digital Health · University of Waikato / Capstone**  
*Presentation Date: 20 November 2026*

---

### Slide 1: Title
**SSIME PBRI Model: Stroke Integration AI Project**  
*An AI tool to screen, support and follow up working-age adults (35–70) with hypertension or diabetes who are at risk of stroke.*  
⚪ 🟢 🟢 🟡 🟠 🔴 ⚫ (7-Colour Life Traffic-Light System)

---

### Slide 2: The Problem
**Who we serve, and what goes wrong**
* **Target Users:** 35–70 years old. Working-age adults with hypertension (HT) and/or diabetes (DM), who are at risk of stroke.
* **K · Knowledge:** They don’t know what their own test results mean.
* **A · Attitude:** They don’t yet see self-care as important.
* **Missed Medication:** Irregular medicine leaves blood pressure and sugar uncontrolled.
* **Risk Behaviours:** No exercise, smoking, drinking.
*(Source: SSIME PBRI Model Team)*

---

### Slide 3: SSIME Framework
**One five-step cycle that loops back to screening**
* **S · Screening:** BEFAST, CV Risk and the 7-colour ping-pong.
* **S · Stroke:** Prevent stroke, and catch it early.
* **I · Intervention:** 3R3E and a chatbot that answers from a set handbook.
* **M · Monitoring:** Follow-up at 3, 6 and 12 months.
* **E · Evaluation:** KAP, quality of life (QoL) and SROI.
* **↻ Continuous Loop:** After evaluation, people are screened again to see whether their colour and risk have changed.

> **SSIME** = Screening · Stroke · Intervention · Monitoring · Evaluation

---

### Slide 4: PBRI Model
**Three objectives, three phases**

* **Phase I · Year 1: AI Screening Tool for Stroke**
  * *KPI:* 1 AI-Screening Module
  * Literature review: BEFAST, CV Risk, 7 colours
  * Prototype the screening tool
  * Prepare training data
  * Reach an acceptable tool
* **Phase II · Year 2: AI Intervention**
  * *KPI:* AI + 3R3E Module
  * 3R3E → Chatbot → AI-Learning
  * Implement the intervention in communities
* **Phase III · Years 3–5: Monitoring & Evaluation AI**
  * *KPI:* Monitoring & Evaluation Module
  * Monitoring reports at 3, 6 and 12 months
  * 5-year cohort study
*(Source: SSIME PBRI Model Team)*

---

### Slide 5: Phase I · AI Screening Tool
**Two parts, each measured its own way**

#### Part 1 · AI: BEFAST Detection
* AI reads the face and listens to speech to catch a stroke as it happens.
* Abnormal → Call 1669 immediately.
* Inputs: Photo (face), Speech (voice).
* **KPI:** Precision 50%.

#### Part 2 · Rules, No AI: Risk Rules
* **Thai CV Risk Score:** Gives the 10-year risk of heart disease or stroke.
* **7-Colour Ping-Pong:** Shows today’s blood pressure and sugar control.
* **KPI:** 100% match vs. nurse’s calculation.

#### Order of Use:
1. ① **BEFAST abnormal** → 1669 now
2. ② **7 colours** set care and the next visit
3. ③ **CV Risk** explains the risk
*(CV Risk source: Thai CV Risk Score calculator, Ramathibodi Hospital)*

---

### Slide 6: Life Traffic-Light Ping-Pong · 7 Colours
**One colour says what to do today**

| Colour | Category | BP Criteria | Sugar Criteria | Action |
| :---: | :--- | :---: | :---: | :--- |
| ⚪ **White** | Normal | BP < 120 / 80 | Sugar < 100 | Check yearly |
| 🟢 **Light green** | At risk | BP 120–139 / 80–89 | Sugar 100–125 | 3R3E + chatbot |
| 🟢 **Dark green** | Ill, controlled | BP < 139 / 89 | Sugar < 125 | 3R3E + medicine |
| 🟡 **Yellow** | Watch | BP 140–159 / 90–99 | Sugar 126–154 | Closer follow-up |
| 🟠 **Orange** | Danger | BP 160–179 / 100–109 | Sugar 155–182 | See a doctor |
| 🔴 **Red** | Critical | BP ≥ 180 / 110 | Sugar ≥ 183 | Hospital now (1669) |
| ⚫ **Black** | Complication: Stroke | Stroke signs (BEFAST) | — | Hospital within 4.5 hours (golden period) |

*(Source: Promsawan et al., 2568 BE, citing Asanee Wanchai et al., 2566 BE · app actions: SSIME PBRI Model Team)*

---

### Slide 7: Phase II · AI Intervention
**3R3E and the Nong Ping-Pong chatbot**

#### 3R · Reduce three foods:
* Less sugar
* Less fat
* Less salt

#### 3E · Cut three risks:
* Less smoking
* Less alcohol
* Less weight

#### Chatbot & Prototype v2:
* **Workflow:** `3R3E → Chatbot → AI-Learning`
* The chatbot answers **only from the set handbook**, explicitly names the topic used, and refers any out-of-scope query to the local primary care unit (health station).
* **Mobile Ping-Pong Booklet features:**
  * Home · latest colour
  * Measure today
  * Today's result · why
  * 3R3E missions
  * Nong Ping-Pong · chat
  * My colours · history
  * Red emergency button: *"Something’s wrong now"* opens the BEFAST checklist and dials 1669 immediately.
*(Note: Department of Health's official frame is 3อ. 2ส.; 3R3E is the team's designated naming)*

---

### Slide 8: Phase III · Monitoring & Evaluation
**Three levels of results, from person to community**

* **Output (% Colour Change):**
  * Share of people whose colour improves, and how long it takes.
  * Paired with the drop in CV Risk (percentage points).
* **Outcome (95% Screened & Treated):**
  * 95% of the target group screened and provided with intervention (Ministry of Public Health KPI).
  * KAP evaluated at baseline (pre-test), and repeated at 3, 6, and 12 months.
* **Impact (QoL & SROI):**
  * Quality of Life (QoL) and Social Return on Investment (SROI).
  * 5-year cohort study.

---

### Slide 9: Five-Year Plan and Budget
* **Year 1 · Build:**
  * Target: PBRI DB · development team
  * Output: AI-Screening Module
  * Budget: AI server · outsourced developer · experts = **4,000,000 THB**
* **Year 2 · Roll out:**
  * Target: People aged 35–70
  * Outcome: 95% screened and treated · KAP at 3, 6, 12 months
  * Budget: Training · implementation = **300,000 THB** per health station · M/A **500,000 THB**
* **Years 3–5 · Scale up:**
  * Target: 40 communities · health stations
  * Impact: QoL · SROI · 5-year cohort

---

### Slide 10: Conclusion
**SSIME PBRI Model: Stroke Integration AI Project**
> *"Detect early. Support continuously. Measure what changes."*
* AI catches a stroke as it happens.
* Explainable rules show the risk.
* The ping-pong booklet brings people back to measure again.
