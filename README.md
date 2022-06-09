# Linkedin-Job-Scrapper
This tool bypasses Linkedin UI changes at different triggers and is embedded with uniform sleep time to replicate human touch. 
For scrolling we save current page height using a javascript and we iterate until we reach the end of all available jobs with specific filters this helps in continuous
scrolling even with UI change because of "show more jobs" button.

First step is to scrape all the details shown on job cards without clicking it to find more information. This information is saved in Jobs list which we iterate over
to find out more information about the job. each card is stored in "li" html object and thus we iterate over its index using Jobs list as the length of list.
Note that: It is necessary to maximise the window of the automated chrome browser otherwise the UI will adapt and eventually give out error.

