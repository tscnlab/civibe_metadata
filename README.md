# Metadata Starter Kit

This repository contains a lightweight template for project metadata.
It includes:
- reusable YAML templates  
- matching human-readable descriptors  
- inline coding schemes (e.g., for sex, handedness, flags)  

The goal: make metadata **easy**, **consistent**, and **reusable** across lab projects.

---

## Repository structure

```text
metadata-starter-kit/
├── templates/
│   ├── project.yaml
│   ├── study.yaml
│   ├── device.yaml
│   ├── participant.yaml
│   └── dataset.yaml
└── descriptors/
    ├── project.md
    ├── study.md
    ├── device.md
    ├── participant.md
    └── dataset.md
```

## How to use this kit
1. Copy templates into your project

2. Place them in a folder such as:
```text
my-project/
└── metadata/
    ├── project.yaml
    ├── study.yaml
    ├── device.yaml
    ├── participant.yaml
    └── dataset.yaml
```
4. Fill in fields in plain language

5. Refer to the descriptor files for help
   - Every template includes a link at the top to its descriptor.

7. Adapt templates freely
   - Add/remove fields as needed.

9. Where should descriptors live?
   - If your metadata file is project-specific, keep its descriptor inside your project.
   - If it’s reusable, put the descriptor in a template repository like this one.

## Contributing
Pull requests, suggestions, and extension templates are welcome.

## License
This Metadata Starter Kit is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
