## Best Practices

- **Course directories:** Each course should have its own folder (`course-1-beginner`, `course-2-intermediate`, etc.)
- **Images:** Store all lesson images inside an `images/` folder within each course folder.
- **File formats:** Provide lessons in both `.pdf` and `.txt` formats for accessibility.
- **Quizzes & Exercises:** Keep quizzes in `.md` or `.txt` format, and place exercises in an `assets/` folder.
- **Branding:** Use a `branding/` folder for logos, slide templates, and other visual assets.
- **Extras:** Place investor materials, media kits, and LMS exports under an `extras/` folder.


# Recommended Folder Structure for CTP-Sci-Courses

This document outlines the recommended organization of files and folders within the `ctp-sci-courses` repository to keep content clean, maintainable, and easy to navigate.

---

## Folder Structure Overview

```plaintext
ctp-sci-courses/
│
├── README.md
├── LICENSE
│
├── course-1-beginner/
│   ├── images/
│   │   ├── lesson1-diagram.png
│   │   └── slide-preview.png
│   ├── lesson1.pdf
│   ├── lesson1.txt
│   ├── quiz1.md
│   └── assets/
│       └── exercise1-template.docx
│
├── course-2-intermediate/
│   ├── images/
│   ├── lesson1.pdf
│   └── ...
│
├── course-3-advanced/
│   ├── images/
│   └── ...
│
├── branding/
│   ├── logo.png
│   ├── slide-template.pptx
│   └── header-banner.svg
│
└── extras/
    ├── investor-pitch/
    ├── media-kit/
    └── lms-export/
```
---

## Naming Conventions

- Use clear, descriptive filenames:
  - Lessons: `lesson1-intro.pdf`, `lesson2-advanced-concepts.txt`
  - Quizzes: `quiz1-basics.md`, `quiz2-extras.txt`
  - Images: `diagram1.png`, `figure2.jpg`

---

## Compatibility

This structure supports:

- GitHub Pages for hosting course websites
- Learning Management Systems (LMS) like Moodle or Canvas
- Static site generators such as MkDocs or Jekyll

---

## Contribution Guidelines

- Add new materials to the appropriate course folder
- Include images inside the corresponding `images/` folder
- Follow the established naming conventions
- Update course README files if you add significant new content

---

*Document last updated: May 2025*
