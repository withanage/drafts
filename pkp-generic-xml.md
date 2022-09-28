## Status (12.9.2022)
- differente plugins for XML creation, editing and dissemination
- Lots of duplicate code in plugins jatsTemplate, docx2jats and texture plugins.



## Proposal
- Establish a recomenneded way to 
- XML creation can be standardized and lots of  element creation can be re-used
- An Abstract Class / Interface can be defind to generatate a  Generic XML Functionality
   - This Interface can be  implemented or abstact class can be extended by different JATS schemas.
  - Context, Submission, Issue and Publication can be either dependancy injected or the implmented classes can be attached to a publication
- Each instantiation should have a schema and a version.  e.g. JATS 1.3 can be a subclass of JATS 1.2 
-  
