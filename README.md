# PDF Generation for GitHub DEI Badging Project

As part of the DEI Badging project, we plan on sending emails to those who request a badge of their repo telling them if they earned the badge, and some future suggestions.

After exploring several options of python libraries to use to generate pdfs dynamically, such as *ReportLab*, I decided on PDFKit and Beautiful Soup.

**PDFKit** was chosen for its ability to simply takes an HTML file and convert it to a pdf. It does have limited functionality, but works for our purposes

**Beautiful Soup** was chosen for being able to modify various elements of an HTML file, which we could use for the variable results of analyzing a repo for the DEI badge.

Overall, this is a good proof of concept for this step of the DEI Badging process.
