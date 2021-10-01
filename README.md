# standards-kenya
Data repository for the controlled vocabularies and curriculum standards for the Kenya educational system.

**WIP**: Note this is a work-in-progress repository and doesn't contain standards data yet, only terms data.



Jurisdiction info
-----------------
Kenya Institute of Curriculum Development https://kicd.ac.ke/ is responsible for curriculum standards in Kenya.

See here for new CBC framework: https://kicd.ac.ke/curriculum-reform/basic-education-curriculum-framework/



Contents
--------
- [`sourcedocuments/`](./sourcedocuments): source documents (PDFs and scans)
- [`sourcedata/`](./sourcedata): machine-readable source documents (spreadsheets)
- [`terms/`](./terms): controlled vocabularies used in the digitized standards:
  - [`CurriculumElements.yml`](./terms/CurriculumElements.yml): terms describing
    the different "types" of elements within the curriculum standards
  - [`Subjects.yml`](./terms/Subjects.yml): terms for the academic subjects within the jurisdiction
  - [`GradeLevels.yml`](./terms/GradeLevels.yml): localized grade levels
- [`standards/`](./standards): curriculum standards ROCdata


Digitization notes
------------------
- Previous work (2019) using scanning, OCR, and computer vision techniques allows the
  structured data extraction of the "KICD Secondary Curriculum Vol II" book, see
  https://docs.google.com/spreadsheets/d/1nqv6CoT0ORtdrfOmhePiGmkNz4cDbu_HFPfpzfwQu4E/edit#gid=358017084 .
- The structure of new CBC curriculum PDF documents is different so requires new approach


License
-------
All documents and are under copyright © Kenya Institute of Curriculum Development.
The digital representations of terms and standards data in this repository are
for illustrative purposes part of the [ROC data project](https://rocdata.global/)
and should not be considered endorsed or approved by the KICD in any way.
