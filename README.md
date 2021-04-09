Use this code to fill in a google form automatically.
The form I used in the code is a replica of a previous attendance form.

usage:
    
    1.  Go to https://www.python.org/downloads/ and download python 
    2.  Open cmd (press windows key and type cmd.exe) and type "pip install selenium" 
    3.  Download any code editor that can run python. I used VS code https://code.visualstudio.com/ 
    4.  Download geckodriver (firefox) https://github.com/mozilla/geckodriver/releases or chromedriver https://chromedriver.chromium.org/downloads or msedgedriver https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
    5.  Copy the code into the code editor (I don't recommend this as you don't learn anything or at least analyse the code and understand it) 
    6.  Change 'student id', 'password', 'firstname.lastname@student.tdsb.on.ca', 'First name', and 'Last name' to your info and run the program
   
If you encounter a "Unable to locate element" error, add "time.sleep()" above the line with the error and re-run it.


You will encounter an error if you directly copy ```time.sleep()```


I'll let you change it so you can actually learn (not spoonfeeding you people)

If you want to use a specific driver, you need the corresponding browser.




------------------------------------------



### Todo

- [x] Firefox users
- [x] Edge users
