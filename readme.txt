HowTo: UniS Thesis LaTeX template

The UniS Thesis LaTeX template was developed initially by Bill Christmas [1] as a package defining some characteristics of the book class. It has been updated by Konstantinos Katsaros to provide some structure and organization of the files. This template can also be used for the Transfer report.

You can edit those characteristics by accessing the UniSThesis.sty file and following the comments provided.

Some of the information that you have to update in the UniSThesis.sty file includes:
• UniS logo/crest image 
• Your personal website
• The subtitle of your thesis/report to match the accreditation 
• Your Faculty
The rest can be left as it is. 

 The structure of the template contains different folders for each chapter, appendix and other material that will be used, one ‘master’ TeX file (thesis.tex) and the package .sty file introduced before. 

Starting from the thesis.tex file you can control your thesis in the following attributes (for more information refer to a LaTeX tutorial):
• General font size of the text
• Single-sided or double-sided 
• The depth of the numbering sections and how it will be presented in the Table of Contents (they are created automatically)
• The title of your Thesis/Transfer Report
• Your name 
• The centre you belong
• The type of the logo/crest you want to use
• The month and year you write your thesis/report
• Keywords associated with your thesis/report
• Your email
• The style of your bibliography

Then you are ready to add text in your thesis/report. The dedication, abstract, acknowledgment, each chapter and each appendix, all live in individual folders with their respective TeX file. This makes management more convenient. In addition, you can control which parts (chapters) of your thesis you want to include when you build it. This can be useful during the writing and review process. For your convenience, each chapter has individual folder for its figures.



[1] Accessible only on campus or with remote access http://info.ee.surrey.ac.uk/Research/Internal/thesis/

