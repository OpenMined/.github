Follow CRAN's <a href = 'https://cran.r-project.org/doc/manuals/r-release/R-exts.html'>guide to extending R</a> for package design.

Follow the <a href ='https://style.tidyverse.org'>tidyverse style guide</a> for everything else.

This is as close to "generic R style" as possible given the fractured nature of the userbase, however some areas that are relatively likely to be different from what you're used to are:
* Use snake case for both function and variable names
* Use pipes instead of nested function calls e.g. mean(x) %>% print() rather than print(mean(x))
* Avoid explict return staments when possible
* Use double quotes " to quote text unless the text contains double quotes and no single quotes
