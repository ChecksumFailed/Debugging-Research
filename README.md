Greetings Developer!
We are looking for some insights to how you go about debugging. This repository contains a scoped application you can install on your PDI and perform an unscripted debugging, and a more directed debugging. We ask that you record your screen and share the recording with us for analysis.

At the end of the instructions there is a short survey where you can answer a few questions and also provide a link to get to your recording. 


To record your screen:
On OSX you can use Quicktime -> File -> New Screen Recording -> Press Record
On Windows you can use the game bar -> Press the Windows button + G - and say it is a game, then start recording
You of course can use any recording method you wish.
Once your recording is done, upload it to some storage service: Youtube, box, vimeo - with at least the permissions of: Anyone with the link


Thank you for participating to improve the debugging experience in ServiceNow.

Instructions:
*Prep*
If you have never worked with Github visit the [developer site page](https://developer.servicenow.com/dev.do#!/learn/courses/newyork/app_store_learnv2_flowdesigner_newyork_flow_designer/app_store_learnv2_flowdesigner_newyork_developing_for_flow_designer/app_store_learnv2_flowdesigner_newyork_exercise_prepare_instance_for_developing_for_flow_designer) here to get more familiar with the process.
1. Fork this repository
1. Continue on from the forked version of this repo.
1. Click the code button, and copy the https link to the repository.
1. In your ServiceNow instance launch studio: System Applications -> Studio
1. Click the 'import from source control' button
1. Paste the URL you copied from github, and provide your user name and password
1. Click 'import'
1. Click 'Select Application' 
1. Choose the *debugging* application

*Getting Started*
1. In the standard platform view open the provided todo table: System Applications -> Todo -> Todos
1. Open **TASK0021233** / **Task One** from the provided records into the form view
1. Change the state of that record to *Pending* and *Save* the record
1. Notice the error message
1. Start recording
1. Debug the issue such that the record is able to be set to *Pending* without error
1. Complete the debugging or stop after 5 minutes whichever one happens first

**Second Scenario**
1. Open **TASK0021580** / **Task Two** in the form view
1. Change the Priority of that record to '4 - Low'
1. Notice the error message
1. Open the business rule: Change Priority
1. Set a breakpoint on Line 3 by clicking the line for number
1. Open the Script debugger: *System Diagnostics -> Script Debugger*
1. Open *TASK3* in the form view
1. Change the state of that record to '4 - Low'
1. Using the script debugger - proceed to debug why you are getting that error and fix it.
1. Stop when 5 minutes has elapsed or you have fixed the problem

1. Stop recording

Upload your recording to some storage service: Youtube, box, vimeo - with at least the permissions of: Anyone with the link
Fill out this very short survey and include the link to your recording. *insert surveymonkey*
