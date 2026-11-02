# Pharmacovigilance – Task 1
## ICSR Case Intake and Validation

**Project objective:** Convert the supplied fictional, de-identified adverse-event records into structured Individual Case Safety Reports (ICSRs), establish the event chronology, separate reported facts from assumptions, and validate completeness.

> Training-only notice: The supplied product, cases and events are fictional. This document is not medical advice and must not be used for real safety reporting.

## 1. Supplied Reference: Velunex

| Adverse reaction | Expectedness |
|---|---|
| Transient headache | Expected |
| Nausea | Expected |
| Dizziness | Expected |
| Mild self-limiting rash | Expected |
| Other events | Not listed as expected |

Expectedness describes consistency with the supplied reference. It does not establish causality.

## 2. Structured Individual Case Safety Reports

### Case PV-101

| Field | Information |
|---|---|
| Case ID | PV-101 |
| Reporter country | India (IN) |
| Patient age | 34 years |
| Patient sex | Female |
| Suspect product | Velunex |
| Adverse event | Nausea |
| Onset after use | 3 hours |
| Outcome | Recovered |
| Seriousness | Non-serious |
| Concomitant information | None reported |
| Expectedness | Expected |

**Case assessment:**

Nausea was reported 3 hours after use of Velunex. The patient recovered. Nausea is listed as an expected adverse reaction in the supplied fictional reference.

**Missing information:**
- Reporter identity and contact details.
- Product dose, dosage form and route.
- Treatment start and stop dates.
- Patient medical history.
- Action taken with the product.
- Exact event and recovery dates.

**Validation:** Partially complete. Reporter identity and additional medication information require follow-up.

### Case PV-102

| Field | Information |
|---|---|
| Case ID | PV-102 |
| Reporter country | India (IN) |
| Patient age | 61 years |
| Patient sex | Male |
| Suspect product | Velunex |
| Adverse event | Loss of consciousness |
| Onset after use | 2 days |
| Outcome | Recovering |
| Seriousness | Serious |
| Seriousness criterion | Emergency hospital admission |
| Concomitant information | Unknown |
| Expectedness | Unexpected |

**Case assessment:**

Loss of consciousness was reported 2 days after using Velunex. Emergency hospital admission was reported, and the patient was recovering at the time of reporting.

Loss of consciousness is not listed among the expected reactions in the supplied reference.

**Missing information:**
- Reporter identity and contact details.
- Exact event onset and admission/discharge dates.
- Product dose and route.
- Concomitant medications.
- Patient medical history.
- Clinical findings and treatment.
- Action taken with the product.

**Validation:** Serious case requiring priority follow-up.

### Case PV-103

| Field | Information |
|---|---|
| Case ID | PV-103 |
| Reporter country | United Kingdom (GB) |
| Patient age | 27 years |
| Patient sex | Female |
| Suspect product | Velunex |
| Adverse event | Mild rash |
| Onset after use | 4 days |
| Outcome | Recovered |
| Seriousness | Non-serious |
| Concomitant information | No rechallenge |
| Expectedness | Expected |

**Case assessment:**

A mild rash was reported 4 days after using Velunex. The patient recovered. Mild self-limiting rash is listed as an expected reaction.

No rechallenge was reported.

**Missing information:**
- Reporter identity and contact details.
- Product dose and route.
- Medication start and stop dates.
- Exact rash onset and recovery dates.
- Rash description and duration.
- Treatment, if any.
- Patient medical history.
- Action taken with the product.

**Validation:** Partially complete. Additional information is required.

### Case PV-104

| Field | Information |
|---|---|
| Case ID | PV-104 |
| Reporter country | India (IN) |
| Patient age | Not reported |
| Patient sex | Unknown |
| Suspect product | Velunex |
| Adverse event | Appendicitis |
| Onset after use | 3 weeks |
| Outcome | Recovered |
| Seriousness | Serious |
| Seriousness criterion | Hospitalisation |
| Concomitant information | Medical history incomplete |
| Expectedness | Unexpected |

**Case assessment:**

Appendicitis was reported 3 weeks after using Velunex. Hospitalisation was reported, and the patient recovered.

Appendicitis is not listed among the expected reactions in the supplied reference.

**Missing information:**
- Reporter identity and contact details.
- Patient age and further identification details.
- Exact event onset and hospitalisation dates.
- Product dose and route.
- Medical and surgical history.
- Concomitant medications.
- Treatment and clinical findings.
- Action taken with the product.

**Validation:** Incomplete case requiring substantial follow-up.

## 3. Medication and Adverse-Event Chronology

| Case ID | Suspect product | Onset after use | Adverse event | Outcome |
|---|---|---|---|---|
| PV-101 | Velunex | 3 hours | Nausea | Recovered |
| PV-102 | Velunex | 2 days | Loss of consciousness | Recovering |
| PV-103 | Velunex | 4 days | Mild rash | Recovered |
| PV-104 | Velunex | 3 weeks | Appendicitis | Recovered |

**Chronology limitations:**
- Exact medication start and stop dates are unavailable.
- Dose, frequency and route are not provided.
- Exact adverse-event dates are unavailable.
- Dechallenge information is not supplied.
- PV-103 specifically reports no rechallenge.

## 4. Seriousness and Expectedness Assessment

| Case ID | Seriousness | Expectedness | Reason |
|---|---|---|---|
| PV-101 | Non-serious | Expected | Nausea is listed in the reference. |
| PV-102 | Serious | Unexpected | Emergency hospital admission; event not listed as expected. |
| PV-103 | Non-serious | Expected | Mild rash is listed in the reference. |
| PV-104 | Serious | Unexpected | Hospitalisation; event not listed as expected. |

**Important distinction:**

- Seriousness is based on reported clinical seriousness criteria.
- Expectedness is based on the supplied fictional reference.
- Neither classification establishes causality.
- A serious event is not necessarily severe in intensity.
- An unexpected event is not necessarily caused by the suspected product.

## 5. Reported Facts vs Assumptions vs Missing Information

| Case ID | Reported facts | Assumptions to avoid | Missing information |
|---|---|---|---|
| PV-101 | Nausea, 3 hours, recovered | Velunex caused nausea | Dose, route, reporter details, history |
| PV-102 | Loss of consciousness, 2 days, emergency admission | Product caused unconsciousness | Clinical findings, medicines, history |
| PV-103 | Mild rash, 4 days, recovered | Rash was definitely caused by Velunex | Rash description, dose, route |
| PV-104 | Appendicitis, 3 weeks, hospitalisation | Velunex caused appendicitis | Patient age, history, treatment |

No causal relationship should be concluded from timing alone.

## 6. ICSR Completeness Validation

The four minimum elements generally checked for a valid ICSR are:

1. An identifiable patient.
2. An identifiable reporter.
3. A suspect medicinal product.
4. An adverse event or reaction.

| Validation parameter | PV-101 | PV-102 | PV-103 | PV-104 |
|---|---|---|---|---|
| Patient information | Partial | Partial | Partial | Incomplete |
| Reporter identification | Missing | Missing | Missing | Missing |
| Suspect product | Available | Available | Available | Available |
| Adverse event | Available | Available | Available | Available |
| Onset information | Available | Available | Available | Available |
| Outcome | Available | Available | Available | Available |
| Seriousness | Non-serious | Serious | Non-serious | Serious |
| Follow-up required | Yes | Yes | Yes | Yes |

**Validation conclusion:**

All four records contain suspect product and adverse-event information. However, none can be confirmed as a fully valid ICSR from the supplied CSV alone because identifiable reporter information is missing.

PV-104 also has particularly limited patient information.

## 7. Follow-up Questions

### PV-101
1. What was the dose and route of Velunex?
2. When was the medication started and stopped?
3. Was any treatment given for nausea?
4. Was the medication discontinued?

### PV-102
1. What were the exact dates of hospital admission and event onset?
2. What clinical findings were recorded?
3. What other medications was the patient taking?
4. What treatment was provided?
5. Was Velunex discontinued?

### PV-103
1. What was the appearance and duration of the rash?
2. What was the dose and route of Velunex?
3. Was any treatment given?
4. Was the product discontinued?

### PV-104
1. What was the patient's age?
2. What was the patient's relevant medical and surgical history?
3. What were the dates of appendicitis onset and hospitalisation?
4. What treatment was provided?
5. What other medications were being used?

### All Cases

Obtain the reporter's identity, professional qualification (if applicable), and contact details using appropriate privacy safeguards.

## 8. Final Quality Checklist

- [x] Patient, suspect product and adverse event reviewed.
- [x] Medication and event chronology prepared.
- [x] Reported facts separated from assumptions.
- [x] Missing information identified.
- [x] Seriousness and expectedness assessed.
- [x] Completeness validation performed.
- [x] Follow-up questions prepared.
- [ ] Reporter information obtained.
- [ ] Public or view-only submission link created.

## 9. Conclusion

This pharmacovigilance exercise demonstrates the process of collecting, structuring and validating adverse-event information into an Individual Case Safety Report.

Four fictional cases involving Velunex were evaluated. Two cases were classified as serious (PV-102 and PV-104), while two were classified as non-serious (PV-101 and PV-103).

The analysis identified missing patient, reporter, medication and clinical information. Follow-up questions were prepared to improve data completeness.

The exercise highlights the importance of accurate case documentation, seriousness assessment, expectedness assessment and data validation in pharmacovigilance.

---

**Submission title:** ICSR Case Intake and Validation – Pharmacovigilance Task 1

**Suggested submission:** Upload this Markdown report and the accompanying structured CSV into the same Google Drive folder or project repository, then submit one view-only link.

*All supplied cases and the product are fictional. This training document is not intended for real patient reporting or medical decision-making.*