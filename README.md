# PreCheck_Form.pdf
Pre-Check Form Workflow – Google Form + PDF workflow to streamline pre-registration advising. Uses conditional logic to shorten forms, reduce email back-and-forth, and speed up hold clearance.
# Pre-Check Form Workflow

A structured intake form that students complete before registration advising.  
This workflow standardizes information collection, speeds up hold clearance, and reduces unnecessary email back-and-forth.

## Problem

Advisors often spend multiple emails collecting missing details like Banner IDs, planned courses, and transfer credit information.  
This slows down advising, delays hold clearance, and creates frustration for students.

## Solution

The Pre-Check Form ensures students provide all critical information upfront in one place.  
It uses **conditional logic** so most students only answer a few questions, while those with more complex needs are prompted for details.

## Features

- Collects Banner ID, major/minor, and planned courses
- Captures transfer credit information if relevant
- Conditional logic:
  - **Q: Do you plan to take transfer courses at another institution?**
    - If **No** → form ends
    - If **Yes** → two follow-up questions appear:
      1. Which course(s) and institution?
      2. Have you submitted the Form 7 for approval?
- Short for most students, detailed for those who need it
- Exportable results in Google Sheets for easy review

## Live Demo

- [View Google Form (live)](https://forms.gle/tRqTpG7wUiRfEDVX6)  
- [Static PDF Copy](PreCheck_Form.pdf)

## Impact

- Reduced average advising email chain from 3+ replies → 1  
- Faster hold clearance (often same-day instead of multi-day)  
- Improved student experience: clear, professional, structured  

## Future Enhancements

- Integrate with Google Sheets for automatic student tracking
- Link directly to DegreeWorks audits
- Export as PDF for advising records
- Add auto-email confirmation when form is submitted

## License

MIT
