# Getting started 


## Install using the CLI tool
```
typst init @preview/hso-thesis-template
```

## Configuration

This template has the following arguments:
- **title**: title of the thesis
- **author**: author of the thesis
- **tutor-hso**: your tutor at Hochschule Offenburg
- **tutor-company**: your tutor at the company (optional)
- **is-master**: bachelor or master thesis (default: bachelor thesis)
- **date**: date
- **program**: your program (ex: Electrical Engineering/Information Technology)
- **company**: company where you conducted your thesis (optional)
- **lang**: "en" or "de"
- **public**: public or private thesis
- **doc**: content of your thesis

```typst
#import "@preview/hso-thesis-template:0.1.0": hso-thesis

#hso-thesis(
  title: "Creation of an autonomous impulse response measurement system for rooms and transducers with different methods",
  author: "Max Mustermann",
  company: "Unternehmen",
  date: datetime(day: 1, month: 11, year: 2003),
  tutor-hso: "Prof. Dr.-Ing. Jean Dupont",
  tutor-company: "Martina Musterfrau",
  lang: "en",
  program: "Electrical Engineering/Information Technology",
  public: false,
  is-master: false,
  doc: [
    #include "content/introduction.typ"
    #include "content/chapter1.typ"
  ]
)

```


