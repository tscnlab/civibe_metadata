```markdown
# Device-level metadata descriptor

Explains the list of devices in `device.yaml`.

Each entry describes one device used in the study.

---

## Key fields and guidance

### `device_id`
Unique ID linking devices to datasets.

### `device_name`
Human-readable name.

### `manufacturer`, `model`
Recommended for reproducibility.

### `serial_number`
Useful for tracking calibration drift.

### `device_type`
Common values:
- light sensor  
- actigraphy  
- display  
- EEG  
- camera  
- wearable physiological monitor  

### `measurement_modalities`
List of what the device measures (e.g., `illuminance`, `accelerometry`).

### `spectral_sensitivity_description`
Short text or link to datasheet/figure.

### `calibration`
Record calibration events where relevant.

### `placement`
Typical body or environmental location.

### `config`
Technical configuration parameters.

### `documentation_links`
Manuals, datasheets, spec sheets, etc.
