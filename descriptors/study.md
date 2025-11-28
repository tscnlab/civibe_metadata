# Study-level metadata descriptor

Explains `study.yaml`.  
Study metadata describes *what was done*, *who was measured*, and *how the data were collected*.

---

## Key fields

### `study_id`
Unique ID for the study.

### `study_title`
Full descriptive title.

### `study_abstract`
One-paragraph summary of study rationale and design.

### `study_type`
Common values:
- `observational`
- `experimental`
- `simulation`
- `pilot`

### `design`
Structured description of the design, including:
- keywords  
- primary outcomes  
- secondary outcomes  

### `population`
Includes inclusion/exclusion criteria and sample size.

---

## `protocol`

Includes:
- version  
- registration URL  
- path to protocol document  
- textual summary  

---

## `sessions`

Each session gets:
- session_id  
- description  

---

## `data_capture`

Includes instruments and which devices were used.

Example:
```yaml
instruments:
  - name: "Light sensor"
    device_id: "DEV-001"
  - name: "Continuous glucose sensor"
    device_id: "DEV-002"
