# module_1_challenge

## Description
This repository takes code for a website and refactors it to add comments to the HTML and CSS code. Semantic notation of HTML tags is taken into account and attributes are added to a and img tags to increase accessibility of the code. CSS selectors are consolodated for selectors that repeated. The end result is the same look of the website, but the code is more accessible to the end user. 

## Website Screenshot


## Deployed Website



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

## Alterations to the code
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


## Grading
Technical Acceptance Criteria: 40%
Satisfies all of the preceding acceptance criteria plus the following code improvements:DONE

Application's links all function correctly.: DONE

Application's CSS selectors and properties are consolidated and organized to follow semantic structure.: DONE

Application's CSS file is properly commented.: DONE

Deployment: 32%
Application deployed at live URL.: DONE

Application loads with no errors.: DONE

Application GitHub URL submitted.: DONE

GitHub repository that contains application code.: DONE

Application Quality: 15%
Application resembles (at least 90%) screenshots provided in challenge instructions.: DONE
Repository Quality: 13%
Repository has a unique name.: DONE

Repository follows best practices for file structure and naming conventions.: DONE

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.: DONE

Repository contains multiple descriptive commit messages.: DONE

Repository contains a quality README file with description, screenshot, and link to deployed application.: DONE