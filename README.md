# HomeownerClassAutomation

## Setup
  In Chronological Order, Follow The Steps In These Videos: https://drive.google.com/drive/folders/1kQJWiv2BLN6wb9iiSNPkrloqLCJUYcGm?usp=drive_link 

  Ensure The Folder Housing Your "List-OnlineClass" File Has No Spaces
  Ensure This Folder Has The "password_protect_pdf" Python File (.py)
  Ensure This Folder Has The "HO to Learner (missing information)" Outlook Item Template File (.oft)
  Ensure In Your File Directory Settings You Has File Extensions Turned Off

## Instructions On Use

#### In The Menu Set Your Zoom To 95% For The Best User Experience

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image-2.png?raw=true)

Button 1 - Update Master Sheet (Automatic) | Instantly seeks out daily file matching system date and uses that file to update the enrollments

Button 2 - Mass Update Master Sheet (Automatic) | Instantly seeks out all daily files from the last time the master sheet was updated up until the current system date, these files are used to update the enrollment

Button 3 - Update Master Sheet (Manual) | User must manually insert daily file name (excluding file exstension), this file will be used to update enrollment

Button 4 - Troubleshoot | This Button Will Run All Necessary Functions The Program Needs In Order To Function Properly. This Should Be The First Thing Used When Attempting To Resolve An Issue With The Program

Button 5 - Revert To Default | This button will revert any highlighted area to black and white, blank format, no formulas.

##### Note For First Time Users: Button 4 And Button 5 Must Be Added Manually. To Do So, Follow The Instruction Below:
  1. (While In The Program Menu Tab) Insert > Illustrations > Shapes > Square
  2. Name the shape "Troubleshoot" then size and place in the menu where you see fit.
  3. Right Click The Shape > Assign Macro > Select "Thisworkbook.troubleshoot" > Select "OK"
  4. Use Ctrl + S to save you changes

  1. (While In The Master Log Sheet) Insert > Illustrations > Shapes > Square
  2. Name the shape "Revert To Default" then size and place in the sheet. But, keep this button 3 rows above the last empty row at all times
  3. Right Click The Shape > Assign Macro > Select "Thisworkbook.revertToDefault" > Select "OK"
  4. Use Ctrl + S to save you changes

#### In The Log Set Your Zoom Between 50%-80% For Best User Experince

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image-1.png?raw=true)

Button 1 - Email | Will Automatically Generate A Missing Assignment/Information Email For The Enrollee In Which The Row The Email Button Was Clicked

Button 2 - Cert | Will Automatically Generate An Encrypted And Non-Encrypted Course Certification pdf For The Enrollee In The Row In Which The Button Was Click. Then Will Create Two Emails, One To The Enrollee's CEA and One To The Enrollee With The Enrollee's Course Certification

## Troubleshooting

#### Firstly Please Ensure You've Run The Troubleshoot Button In The Program Menu

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image-3.png?raw=true)

#### Secondly, If That Doesnt Solve The Problem. Ensure Your References Are Correct

1. While in the "List-OnlineClass" program, use Fn + Alt + F11 (or Alt + F11) To Open The Code Editor. You Should See A Screen Similar To The One Below

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image.png?raw=true)


2. On This Screen Go To The Top Menu Bar > Tools > References. Then Ensure You Have Your References Checkboxed And Matching The References In The Image Below. (All Unchecked References Are In Alphabetical Order To Help Find Them)

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image-4.png?raw=true)

3. Then Once You've Checkboxed All References, Press "OK". Then Use Ctrl + S To Save Your Changes

#### Lastly, If That Doesn't Solve The Problem. Try To Re Copy And Paste The New Code Into Your Program 
##### These Instructions Also Act As The Instructions For Implementing A New Program Update Or Setting Up The Program

1. Ensure Your In The "MAIN" Branch Of The HomeownerClassAutomation GitHub Repository

2. Select The Most Recent/Update To Date HomeownerClass Automation.txt File (Generally At The Bottom Out Of All The Files. Can Also Be Double Checked By Checking Which File Has The Largest Update Number)
  - At The Time Of Writing This, The Most Recent Update Is "Homeowner Class Automation Update 8.txt"

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image-5.png?raw=true)

3. Copy All Of The Code In This File Using Ctrl + C After Highlighting All The Code In This File.

4. In Your "List-OnlineClass" File, Use Fn + Alt + F11 (or Alt + F11) To Open The Code Editor. Your Screen Should Be Similar To The Screen In The Image Below.

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image.png?raw=true)

5. In The Left-Hand Bar Of The Code Editor, Double Click "Thisworkbook". 

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image-6.png?raw=true)

6. Click On The Large Right Pane (Highlighted In The Image Below) Use Ctrl + A Then The "Delete" Button To Remove Any Previous Code. Then Use Ctrl + V To Insert The Code You Copied Earlier From The Update File.

![alt text](https://github.com/Ross-Ede/HomeownerClassAutomation/blob/main/images/image-7.png?raw=true)

7. Please Refer Back To "Ensure Your References Are Correct" Step Above To Ensure None Of Your References Changed During The Update

8. Use Ctrl + S To Save Your Changes

#### If You're Running Into A Specific Error While Using The Program; Please Use The Table Of Contents To Find Your Error And Its Solution

| # | Problem | Solution |
|---|:--------|----------|
| 01 | VBA Error 1004 – Application-Defined or Object-Defined Error | This Is Likely Due To Program's Global Variables Missing Its References. To Fix This Run The Troubleshoot Button In The Program Menu |
| 02 | Email Button Does Nothing On Click | Please Ensure The Button Still Has A Macro Assigned To It. Right Click > Assign Macro > "ThisWorkbook.missingEmail ButtonRow". Please Note 'ButtonRow' Must Be Replaced With The Number Of The Row The Button Is In |
| 03 | Cert Button Nothing On Click | Please Ensure The Button Still Has A Macro Assigned To It. Right Click > Assign Macro > "ThisWorkbook.makePDFs ButtonRow". Please Note 'ButtonRow' Must Be Replaced With The Number Of The Row The Button Is In |
| 04 | VBA Error 13 - Type Mismatch Error | Please Ensure That The CEA and DR Emails Are Valid And Not Returning A Value Such As "#N/A" or "#VALUE" |
| 05 | Macro Is Blocked/Disabled | Locate your file in the file explorer then right click and go to properties. In properties locate permissions that are preventing the macros from running. Then Press "OK". Return to the master workbook and select "enable content if prompted" |

