# FUTURE_PE_03 — AI SEO Blog & Content Cluster Generator

**Internship:** Future Interns — Prompt Engineering Track
**Task:** Task 3 — AI SEO Blog & Content Cluster Generator for Business Websites
**Tool Used:** Claude (claude.ai)
**Business Chosen:** Smile Care Dental Clinic, Pune
**Track Code:** PE

---

## 📌 Business Profile

| Field | Details |
|---|---|
| Business Name | Smile Care Dental Clinic |
| Type | Dental Clinic |
| Location | Pune, Maharashtra, India |
| Target Audience | Local residents searching for dental services in Pune |
| Primary Goal | Rank on Google for dental-related local searches and build trust before the first visit |

---

## My Approach

I chose a dental clinic because healthcare businesses rely heavily on trust-building content, and local SEO matters a lot for them — most patients search "near me" or "[service] in [city]" before booking. I structured this as a content cluster: one pillar blog covering the clinic broadly, and 4 supporting blogs targeting specific searches (cost, safety, comparison, and a how-to/checklist style query). This mirrors how real SEO agencies plan content instead of writing random posts.

---

## 🧠 Prompt Logic

| Step | Purpose |
|---|---|
| 1. Define the topic cluster | Decide 1 pillar topic + 4 supporting topics around it |
| 2. Pillar blog prompt | Generate a long-form, authority-building article |
| 3. Supporting blog prompts | Generate shorter, intent-specific articles that link back to the pillar |
| 4. Local SEO prompt | Adapt language to include city + service naturally |
| 5. Linking structure | Map how each blog links to the pillar and to each other |

---

## 📁 Repository Structure

```
FUTURE_PE_03/
│
├── README.md
├── prompts/
│   └── seo_prompts.md          ← All structured prompts used
│
├── outputs/
│   └── dental_clinic_seo_pack.md   ← Pillar blog + 4 supporting blogs
│
└── screenshots/
    └── (screenshots of prompts run on Claude)
```

---

## ✅ What Was Built

1. **Pillar Blog:** "Best Dental Clinic in Pune – Services, Cost & What to Expect"
2. **Supporting Blog 1:** "Dental Implant Cost in Pune"
3. **Supporting Blog 2:** "Teeth Whitening – Is It Safe?"
4. **Supporting Blog 3:** "How to Choose the Right Dentist in Pune"
5. **Supporting Blog 4:** "Root Canal Treatment: What to Expect (Pune Patients' Guide)"
6. Internal linking map connecting all blogs
7. Keyword + search intent explanation for each blog

---

## My Observations

- The pillar blog needed the most rework — my first version was too generic, so I added explicit instructions for H1–H3 structure and word count
- Local SEO worked best when I asked the AI to weave "Pune" naturally into headings and intro paragraphs, instead of just repeating the city name everywhere
- Supporting blogs targeting specific, narrow questions (like "is teeth whitening safe") felt much more natural and search-friendly than broad topics
- This prompt system is reusable — I could swap "dental clinic" + "Pune" for any local service business and city

---

## 🔧 How to Reuse This Prompt System

1. Change the **business type** (e.g., clinic → salon → coaching institute)
2. Change the **city/location**
3. Update the **pillar topic** and **4 supporting topics**
4. Run the same prompt structure — outputs adapt automatically

---

*Submitted as part of Future Interns Prompt Engineering Internship.*
