# Resume

This repository contains a professional LaTeX resume/CV template designed for clean and efficient presentation of your qualifications, skills, and experience.

## Preview

The template generates a well-structured PDF resume with sections for:
- Personal information and contact details
- Education
- Skills
- Projects with detailed descriptions
- Certifications

## Features

- Clean and professional layout
- Hyperlinked contact information (email, phone, GitHub, LinkedIn)
- Custom section formatting
- Project listings with descriptions
- Responsive design for proper A4 paper formatting
- Integration with bibliography management

## Requirements

To compile this LaTeX template, you'll need:
- A LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- The following packages:
  - url
  - parskip
  - color
  - graphicx
  - xcolor
  - geometry
  - tabularx
  - enumitem
  - supertabular
  - titlesec
  - multicol
  - multirow
  - biblatex
  - hyperref
  - fontawesome5

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/Resume.git
```

2. Edit the `cv.tex` file with your personal information, education, skills, projects and certifications.

3. Use a tool like latexmk to compile and create a PDF file of the resume

```bash 
latexmk -pdf cv.tex
```

## Customization

- Modify the sections in `cv.tex` to match your experience
- Adjust colors by changing the `\definecolor{linkcolour}` command
- Customize the header format by editing the `\titleformat` and `\titlespacing` commands

## Acknowledgments

This template uses several LaTeX packages to achieve its design and functionality. Feel free to customize and add
your own twists to the template to make your resume standout.