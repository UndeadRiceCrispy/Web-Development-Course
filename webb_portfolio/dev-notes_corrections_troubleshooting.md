# Developer Notes: Programming, Corrections & Troubleshooting of code, appearence and functionality

Note: All written content for the cover letter and resume was taken from my personal resume and cover letter so no inline content needs to be referenced as it is my own.

Note: Structure of files based on the requirement example provided in the Task Overview.

Note: I use markdown files as my own professional practice to keep track of the code progress, corrections, changes and troubleshooting notes of the code until I upload to a code repository.

Code Notes:

Used standard character coding for for the web: < meta charset="UTF-8" >

Used the correct meta viewport to make the page responsive on mobile devices:  < meta name="viewport" content="width=device-width, initial-scale=1.0" > //Standard line for making a website responsive on mobile devices(thought I would do this since it was mentioned in the course content and I wanted to try it out since more people use mobile devices these days)

Debugging Notes:

Issue: Intial debugging of the code was not working as expected, some elements in the HTML were missing due to a few of the tags not being closed.
Fix: I was able to fix this by adding the missing closing tags and replaced a few of the tags that were not correctly placed and then checked with my borrowed HTML tag cheatsheet(<https://html.com/wp-content/uploads/html5_cheat_sheet_tags.png>) to verify proper use. I also updating vscode to the latest version to correct debugging issues.

Issue: In generating the button selection for AM/PM/Anytime followed an example I found in w3schools but which was fine but the issue is the radio buttons are not selected when the page loads.
Fix: I was able to fix this by adding the selected attribute to the radio button that should be selected by default.

Issue: By default the radio buttons would not deselect after a selection has been made
Fix:I was able to fix this by adding the checked attribute to the radio button that should be selected by default.
