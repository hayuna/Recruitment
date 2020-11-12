# MultiStepForm

## Description:
We need a component which simulate behaviour of form with many steps.

## Requirements:
Component should be divided into 3 sections.
### ProgressBar
Depends on amount of steps, we should see the same steps here.<br>
Steps should be separated by line.<br>
Current and previous steps should be filled by some background.<br>
In case our current step is more than first, we should have possibility to click previous step and go to this. Of course values entered in form should be filled.<br>
### Form fields
Each fields should be validated and error should be displayed next to field.
Amount of fields should be various
### Action buttons
Action buttons should be affixed to edge of container with form fields.
- In case we have first step, we should see buttons: 
	- Cancel, which clear each values in form.
	- Next, which go to the next step.
- In case we have middle step, we should see buttons:
	- Back, which back to previous step.
	- Next, which go to the next step.
- In case we have last step, we should see buttons:
	- Back, which back to previous step.
	-  Submit, which send all of values (we can use console.log to show values).<br>

In case of any field with error, next/submit button should be disabled.

## Mockups
![Mockups](https://raw.githubusercontent.com/hayuna/MultiStepForm/main/Screenshot%202020-11-12%20at%2022.01.53.png)
