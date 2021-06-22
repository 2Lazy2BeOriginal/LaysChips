YOU WON'T BE ABLE To USE YOUR COMPUTER WHILE THIS PROGRAM IS RUNNING. THIS IS BECAUSE THIS PROGRAM WILL HIJACK YOUR MOUSE AND KEYBOARD JUST TO ENTER THE CODE
1. Install pycharm (if you can do python3.8) Download the GetCode zip file and extract it. Move the folder to desktop or somewhere else
2. Once downloaded go run the program. Open the file by clicking file in the top left, click open, then find the folder you extracted
3. when u open the project, you should see an 'add configuration' on the top right, click it and it should ask you to create a new one. Click it and scroll down until you see 'python'.
4. after that you should see a menu of the project details. set the script path to wherever main.py is. It's in the GetCode folder. It is important that the path ends in main.py or else you will get the same "can't find __main__" error. Next select an interperter, when u first start it will say <no interpreter>. click the drop menu and select 'python3.8' or 'python3.9'. Any is fine.
  
  If you are unable to find one then go to settings -> Project: ... -> project interpreter and click the settings icon and click 'Add'. Here you should see 4 tabs, go to         VirturalEnv Interpreter and take note of 'Base Interpreter' path. Then click the System INterpreter tab and click the 3 dots and you should find your way until you find python.exe. That is the interpreter python will use to run the program
  
5. If u have prexisting code you want to put in then now is the time to add in. go to the code.txt and add code each line should be it's own code. 
6. Go to the import on the 3rd line (the text will be grey and can blend in with the other text) and click the ... hover your mouse over the "import pyautogui" and click alt+shift+enter to install it. If it doesn't work go to the file -> settings -> Project: ... -> project interpreter and click the + button and type pyautogui and selenium 
7. open up mynintendo and go to the page where you can redeem the 16 character code. Scroll all the way to the top and make sure it's full screen and have it ready (if you don't the mouse will move all over and it can enter the code in places you don't want to)
8. There are two variables, GetCode and EnterCode, this is so that the program knows what u wanna do, setting GetCode to False and EnterCode to True will have the program get code but won't enter to mynintendo. The first letter MUST be capitalized or else you will get a syntax error. the True or False must be highlighted in orange 
  There is another variable called folder, inside the '' will be the path to the folder, it's the same as the path to main.py except this time you get rid of the \main.py and yes get rid of the \
9. Adjust the HowMany variable to how many codes u want to get and redeem to your account (your account will include the new codes plus the codes you added to codes.txt) 
10. then click on the play button on top right and QUICKLY MINIMIZE THE PROGRAM and the bot should go open the lays chips website to get codes. If it asks u to give permission click allow. After it's done getting x number of codes the website will close and then input the code for you. REMEMBER TO NOT TOUCH THE MOUSE WHEN THIS HAPPENS AND TO HAVE THE WEB PAGE READY
11. If the loop doesn't work then run the program again. (my program uses images to know where to click). While the loop is running. DON'T TOUCH ANYTHING
12. After the program is done, you have to manually delete all the code in the code.txt
  
if you set GetCode to True the codes will appear at the console.log at the bottom screen. Click the Main.py tab to see it. Copy and paste the codes to a random text document to give to someone or save it 
  
if you encounter into an error where they can not find codes.txt or names.JSON then u must show the directory. so text = open('codes.txt') becomes text = open(r'C:\path\to\your\code.txt') and same with name except it will be names = json.loads(open(r'C:\path\to\your\names.json').read()) *hint you can copy and paste the C:/Users.../main.py and paste it and replace main.py with whatever text doc u need. remember to replace every / with \ 

  if you have questions dm 2Lazy2BeOriginal#4095
