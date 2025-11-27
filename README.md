# Metadata Starter Kit

This repository contains a lightweight template for project metadata.
It includes:
- reusable YAML templates  
- matching human-readable descriptors  
- inline coding schemes (e.g., for sex, handedness, flags)  
- guidelines on how to adapt templates or create new ones  

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
my-project/
└── metadata/
    ├── project.yaml
    ├── study.yaml
    ├── device.yaml
    ├── participant.yaml
    └── dataset.yaml

3. Fill in fields in plain language

4. Refer to the descriptor files for help
   Every template includes a link at the top to its descriptor.

6. Adapt templates freely
   Add/remove fields as needed.

7. Where should descriptors live?
   - If your metadata file is project-specific, keep its descriptor inside your project.
   - If it’s reusable, put the descriptor in a template repository like this one.

## Contributing
Pull requests, suggestions, and extension templates are welcome.

## License
This Metadata Starter Kit is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
