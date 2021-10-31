# Change Log

> A log summary of changes made with the repo.

---

## 10/31/21 #EP | Final review of everything. Made some minor changes during the quality review.

### README

- Built final draft
- Organized and simplified
- Fixed grammer errors and general typos

### CHANGELOG

- Final quality review for spelling 
- Added final updates and changes from today

### HTML

- For content section
  - Removed Class names that mirror'd IDs
- For benefit section
  - Updated H3s to H2 to fit proper sequential order
  - Removed Class names that mirror'd IDs
  - Changed unique Class to IDs
- For FOOTER
  - Removed CLASS name for FOOTER

### CSS

- For SECTION > benifits
  - Updated H3s to H2 to fit mirror HTML

---
## 10/30/21 #EP | Did my first review of the code. There is some more work to do, but overall things are at a good place. Everything needs final review and peer review.

### README

- Built and framed in concept
- Added relevant content and assignement requirements
- Added my personal header information including social links

### CHANGELOG

- Uploaded notes and framed in concept

### HTML

- Overall
  - Added commentes based on Sections with START and END
  - Removed extra line breaks
  - Converted DIV's to semantic element types
- In the HEAD > TITLE
  - Updated TITLE from 'website' to 'Horiseon'
- In BODY
  - Within SECTION > HEADER
    - Converted DIV to HEADER
    - Removed CLASS from HEADER
    - Changed DIV to HEADER
    - Changed DIV to NAV
  - Within SECTION > content
    - Converted DIV to SECTION
    - Converted SECTION child DIVs to ARTICLEs
    - Added ALT to images
    - Added ID to DIV 'search-engine-optimization' to fix navigation
  - Within SECTION > benifits
    - Converted DIV to SECTION
    - Changed SECTION child DIV to ARTICLEs
    - Added ALT to images
    - Within ARTICLE > benefit-cost, I removed `</img>` and updated statement with self-closing ` />`
- Within FOOTER
  - Changed DIV to FOOTER

### CSS

- Overal
  - Organized CSS to be more in alignment with HTML order
- For universal element changes, I moved them to the top
- In BODY
  - For HEADER
    - Changed header class reference to element
    - Changed DIV to NAV
  - For SECTION > benefits & content
    - Merged CLASS and related element styling
  - For FOOTER
    - Changed CLASS reference to element
