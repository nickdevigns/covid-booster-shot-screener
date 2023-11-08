---
### CONTENT ###

# The question you want to ask
text: Have you received a COVID-19 vaccine in the last two months?

# The answer options and page name of destination associated with each answer
# Add as many as you need.
answers:
  - text: "Yes"
    path: q3-exit
  - text: "No"
    path: success

# Whether this question includes related resources (yes or no)
# To add resources, create a content page in the "_resources" folder and add this question's filename to the "related-page-name" setting, for example, who.md.
resources: yes

# =============================================================================

### NAVIGATION ###

# The name of this page used for the URL, for example, who.html
slug: when

# The name of the page where the back button goes from this question
back: question-2

# =============================================================================

### SETTINGS ###

# The name of the layout template this question uses
layout: question

# The title of this page for display purposes, if needed
title: Question 3

# The number of this question that may be used for ordering or sorting
number: 3

# The input type for this question, currently radio only
type: radio
---
