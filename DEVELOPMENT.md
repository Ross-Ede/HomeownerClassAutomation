# Program Development

## 6/19/2023

- Meeting with Dr. Bonaiti learning about the process to be automated

- developing plan/presentation as to how to automate process Dr. Bonaiti has presented to me

## 6/20/2023

- Meeting with Dr. Bonaiti discussing moving forward with the project. And advancements on his end, from website, towards automation of the project.

- Laying out Visual Basic Application Worksheet/Module program to automate process for Dr. Bonaiti. Majority of time was spent looking into efficient forms of automatize.

## 6/21/2023

- First Design of UI created

- Works In Progress:

    + Program opening and comparing daily workbook/sheet to master workbook/sheet

    + Program adding new users to master sheet

## 6/22/2023

- Stuck at major roadblocks for 3 hours: figuring an efficient way to find the last row

    + Spent so much time on this because the programs very integrity is built upon this and it is imperative to have an effective and efficient process.

- Stuck as to why some functions/methods were accepting different references

    + important as different ways of reference and use allows for more ease of use/efficiency for program and user

- Program Can Now

    + Identify the daily file in the folder of the master sheet (assuming the only file in there are excel files with the standard daily file name)

## 6/23/2023

- Stabilizing program

    + Program is unstable, especially concerning directory/file searching capabilities. The root cause being one drive sync and autosave. With these turned on the whole program falls apart because the program's directory and file searching is based on local file paths, not web paths. API/Library may be available to resolve.
              
- Program still has difficulty consistently opening daily files and updating the master log. For time being program is only capable of working if all files are 1. in the same folder 2. saved to pc and are not synced to one drive or have autosave on
              
- User Likely needs to update master log from previous day hence new UI update, user can now auto update via pressing button and program will search directory for file matching system date. Or user can manually upload file from previous days.

## 6/26/2023

Programming and Meeting

- Pre-meeting program was unstable

    + In anticipation of having a stable and helpful product to demonstrate and give at meeting, I spent many hours debugging, stress testing/testing many scenarios in which the program may break. If It broke I had to spend time to fix it. Then once fixed, fix another problem or fix a problem that arises from a fix to a previous problem.
        
    + UI improvement with charts and better layout.
        
- Meeting

    + Demonstration of product. Received feedback on how good, bad, and how to improve program in the future. 

- Completed today
    
    + Program improvements have been noted and will start being worked on in version 2.
    
    + Stable Version 1 of program is now complete 
        
        ` Meaning program can now open daily  files in same folder of master log as long as not on one drive, has autosave on, and are all macro enabled
        
        ` Program can update master log with rows of unadded enrollments from daily log

## 6/28/2023

- Program is now capable of continuing on formatting and formulas of previous cells/rows, Some cell formulas are to be filled in by program, such as name. But this can be left alone in meantime as it can added easily and is up to the user whether they'd like this feature or not.

- Program is now capable of sorting data into correct columns as set in master log. Customization and ability to rearrange rows and columns to be added. That task will likely be timely and difficult.

- Program can now semi-account for multiple enrollments. Meaning if it detects a change in an already enrolled persons data it will update if the data to add is not "not set". Once program can fully account for multiple enrollments it will be able only look at the persons most recent enrollment and change data in the master log as needed. Additionally, if data is missing, "not set", it can look at previous enrollments and try to find said missing data.

## 6/29/2023

- Program can now, in a stable bug free process, bulk update master log with data from multiple daily files. 

    + To give more user control, I still kept singular automatic and manual update. Can be removed at request of Dr. Bonaiti.

- Update to UI, new button to mass update master log automatically. A manual option can be included at the request of Dr. Bonaiti but for now that would seem to defeat the purpose of saving Dr. Bonaiti time.

    + Additionally may update UI to look better, but functionality over looks is the current priority.

- To be done Still:

    + Account for most recent enrollment out of all user enrollments, program can partially complete this task as of now.
    
    + Allow Dr. Bonaiti to simply click cert and not have to enter the row of who he wants to certify
    
    + Allow Dr. Bonaiti To email about missing assignments without having to input the email address manually

## 6/30/2023

- Meeting with Dr. Bonaiti in which we went over new developments

    + We practically now have the final daily file format

    + Clarified information about how master log is to be update 

- Programming

    + To be completed/Works in Progress are the last 3 tasks discussed at the beginning of the week: First, account for the most recent enrollment and update data based off of that. Second, automate certification process and automate emailing of missing assignments process. Note: Program cam technically account for recent enrollment and change data because all that is required is labeling date students passes exam. Program can also change any other data that is new but that feature has temporarily been taken out because it was not explicitly asked for and may override data incorrectly
                          
    + Converted program over to final format of daily file. Changes to UI were made. Many variables had to be changed, created, or removed.
                          
    + Actual master log with program included has been handed over to Dr. Bonaiti. Now awaiting feedback.

## 7/3/2023

- Meeting with Dr. Bonaiti and Dr. Jantrania

    + Discussed how the internship has been going and how we will do things moving forward
                            
    + Discussed what is currently most important for program/received feedback on program

- Program revisions

    + Program was previously putting test completion dates in the incorrect spots - Fixed and has been sent to Dr. Bonaiti with instruction
                           
    + Program is able to work even with deleted and reorganized columns - Ongoing This has taken priority over the 2 following task
                            
    + Automatizing the certification process/Integrating into master workbook
                           
    + Automating emailing process for missing assignments 

- Feedback 

    + Dr. Bonaiti suggested I give more detailed instructions alongside deliverables
                           
    + I implemented this feedback give giving more concise and hopefully clear instruction on how to update program code using step by step process and photos

## 7/5/2023

- Merging certification process with master workbook.
                          
    + Program is still incapable of generating password file, encrypted file, pdf file

## 7/6/2023

- Merging certification process with master workbook
                          
    + Program is now capable of generating pdf file and can also work in any directory within the computer (as long as its not OneDrive)
                          
    + Program is still incapable of generating password file and encrypted file. Has constantly been throwing error in which file isn't found which is because program isn't even generating file to begin. May have to contact project team if I cant resolve it alone by the end of tomorrow

## 7/7/2023

- Program is now complete, automatic certification process and emailing process is functional. Aside from encryption which should work when Adobe Pro is installed

## 7/10/2023

- Reviewed what will be done this week in terms of what needs to done for the program and what the future of my internship may be

## 7/12/2023

- Program is now virtually finished

    + Problem with encryption generation has been solved

    + emails now have learner name

    + program adds date when enrollee was certified

    + some necessary cells need and keep their formulas and formatting, others which don't now don't have them anymore

## 7/13/2023

- Meeting with Dr. Bonaiti, Reviewing program improvements/recommendations

- Implementing Dr. Bonaiti's feedback on the program
    
    + Program is now capable of: Fix why it opens the file directory, make cert and email checkbox bigger, Allow email to be sent with some emails missing

## 7/14/2023

- Submitting final deliverable after stress testing and debugging program

## 7/17/2023

- Meeting with Dr. Bonaiti discussing additional changes and featues to the program along with issues he's encountering that need to be fixed

- Programming trying to fix bugs, eventually moved on to adding features as bugs that are trying to be fixed are stubborn. Program now has have false and true in separate col and list of names who are used to test are again anyways

## 7/19/2023

- Re-did list of names in reverse order because after testing I realized it was last-first not first-last.   
              
- Semi figured out why checkboxes overlap. The issue of x amount generated on the Xth iteration was solved but now instead it does so for every program update. So on the 3rd program update, 3 layers of checkboxes will be added. So it seems these problems have a similar cause. If all else fails I will resorts to shapes.
              
- Fixed amount of people that passed to correct amounts
              
- Reduced run time slightly by ~1 to 2 seconds when updating program. Main issue was removeKeyword function was iterating through each cell and taking to much time
              
- Allow Dr. Bonaiti to highlight area and revert it to default format, no fill, black text, no formula

## 7/20/2023

- Spent many hours in an attempt to solve the stubborn overlapping of checkboxes issue as it is starting to prove to be detrimental to the functionality of the program.
              
- Eventually moved away from the problem and bit and looked into generated folder for new enrollments in outlook for Dr. Bonaiti, but decided it was best to deal with the bigger problem at hand and went back to debugging.
              
- I looked at many sources that seemed to have similar problems and/or solutions but none worked or where not applicable to the program

## 7/21/2023

- meeting with Dr. Bonaiti and discussing what needs to changed and fixed with the program

- fixed some things in the meeting with Dr. Bonaiti, as for the rest, it will be completed over the weekend and given to Dr. Bonaiti.

- Program is moving away from checkboxes and to buttons
          
- Debugging prior to meeting but no significant improvements were made

## 7/23/2023

- Changed checkboxes to buttons to make program more functional. non functioning macros problem resolved and buttons are inserted in correct position. But overlapping is still an issue. But a trade off of buttons is they are less laggy and don't make overlapping noticeable. Right now functionality matters and buttons are the functional solution.

- Also cleaned up a lot of the code as they were many unnecessary/unused lines of code in the file. Program went from ~1.2k lines of code to 991 lines of code

## 7/26/2023

- Documentation
    
    + Github Repository for entire project has been created, Repository includes all updates up to current version, README.md and DEVELOPMENT.md

    + README.md has setup and instructions for use section complete
        ` Finish by completing troubleshooting section
                                      
    + DEVELOPMENT.md has progression of program/all work I've done up until what the program is now.

- Programming
                     
    + add a troubleshoot button that reassigns all variables values and etc.

    + revert to default functions properly now 

    + check email address as well 

    + Program only uses emails and checks test names when adding enrollees no longer looks at names 

## 7/27/2023

- Programming
    + Researching and implementing a framework in preparation for adding new columns to master sheet update and outlook auto renaming

## 7/28/2023

- Documentation
                   
    + Update to GitHub, optional update to excel VBA code (has comments for future reference). Update to README.md, update to DEVELOPMENT.md. New File For Outlook auto renaming program for outlook visual basic
             
- Programming

    + outlook auto renaming complete

## 7/31/2023

- Helped Mr. Segura setup program on his laptop

## 8/2/2023

- Program now pre adds enrollee metadata to mastersheet (due for change as we havent actually recieved the daily file which will contain metadata)

- presentation for 8/8/23 done

- updated documentation 

# 8/7/2023

- fixed issues related to names with spaces in them ex (Name Middle Last) 

- add cea name and email to learner emails 

- email to learner should have county extension website url 

- CEA email should have cea name but has learner name instead 

- fixed issues with pass dates incorrectly being inserted

- Meeting with Dr. Bonaiti reviewing issues with program and also practicing and receiving feedback on presentation

- Improved presentation

# 8/9/2023

- Presentation meeting

- Fixed template for program

- Updated documentation
