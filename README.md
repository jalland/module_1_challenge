# module_1_challenge

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

##Alterations to the code
```
HTML semantics
•	Changed div to header
•	Replaced all other div tags with section tags
•	Changed the title to “Horiseon Social Solution Services Website” to be concise and descriptive.
•	Did not change span, as I did not know an equivalent semantic tag to use. 
•	Added comments throughout HTML document. 
•	All a tags (links) have a title attribute.
•	All img tags have an alternative description.
•	The elements have a logical structure and are indented for child elements.
•	Heading attributes fall in sequential order. 


CSS semantics
•	Replaced all div with section.
•	CSS comments added throughout the document. 
•	Consolidation of CSS selectors with semantic structure:
	    Added benefit-lead-brand-cost selector to consolidate multiple selectors with the same information.
	    Added content-subsections class to consolidate multiple selectors with the same information.

```


##Grading
Technical Acceptance Criteria: 40%
Satisfies all of the preceding acceptance criteria plus the following code improvements:

Application's links all function correctly.

Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

Application's CSS file is properly commented.

Deployment: 32%
Application deployed at live URL.

Application loads with no errors.

Application GitHub URL submitted.

GitHub repository that contains application code.

Application Quality: 15%
Application resembles (at least 90%) screenshots provided in challenge instructions.
Repository Quality: 13%
Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains a quality README file with description, screenshot, and link to deployed application.