# File upload testing

## Scenarios
1. Testing out file upload in a file input field on a web-form.
2. Testing out multiple file uploads in a Document Manager.

## File extensions
Various file extensions that should be tested are mentioned below (the list is not exhaustive).

|Extension|Description|
|:---|:---|
|docx|Created when a file is saved from Microsoft word|
|dotx|Microsoft word template|
|dot|Microsoft word 2007 template|
|xlsx|Created when a file is saved from Microsoft Excel|
|csv|Comma seperated values|
|txt|Plain text file|
|ppt/pptx|Created when a file is saved from Microsoft Powerpoint|
|png/jpeg/jpg/webp|Images|
|mp4/avi|Videos|
|msg|Created when any mail is saved from Outlook|
|oft|Outlook file template|
|pdf|Portable document format|

## Creating test data

1. Creating test data for a single input field (Scenario #1) is simple. QA Tester can create required test data from the requisite application. Say, if a docx file is required QA tester can create a test file in Microsoft word and save it.
2. For Scenario #2, where multiple files might be required to test out boundary values or to do performance test, creating mulitple file by the approach listed in Pt #1 will be arduous.

### Creating multiple test files
If QA tester is having knowledge of any programming language, QA tester can create an script to do this task.
But if QA tester does not have programming knowledge, following approach will come to rescue (the commands that I have listed are for Windows user, but I believe same approach can be used in Mac as well):
1. Create an initial test file (say file_1.png) and save it in the desired working directory.
2. Use `copy` command in Command prompt (cmd). `copy` command allows you to copy and rename the file at once (if you were to copy and rename via GUI, this will involve a lot of keystorkes).
    1. So, command to create file_2.png will be `copy file_1.png file_2.png`
4. Now the next step is to create as many copy commands as the number of file required for testing. For this, Excel can be used. Save all these commands in a text file (say command.txt).
5. Lastly, in cmd run the command `cmd > command.txt`. All files will get created in the present working directory.
