To Use this script follow the two steps below.

1. Clone this repository.
2. Run file "Git-Hub-Manager" in terminal with one parameter or two (First parameter required).
The first (required) parameter is (the git directory you wish to access located according to Documents folder)
The second optional parameter is a custom message for commiting changes to upload to your Git Hub page.
For example I have a git directory called Python-Programs.
To run this script on my example directory you would need to type
    $ ./Git-Hub-Manager Python-Programs
    
To use the second optional parameter type you custom message afterwards (Do not use quotes)
For example we can run this program on my Python-Programs directory as follows.
    $ ./Git-Hub-Manager Python-Programs My custom commit message.

Additional Information

  Program should run on most Linux distros as well as most MacOS intalllations 
  In order to use this program with Windows or any operating system that does not work by default
  you will need to modify the file to search for your complete C: directory or
  whatever directory you wish to use. 
  To do this modify line 6 of the file "Git-Hub-Manager" in whatever texteditor you want to use.

***  Important note ***
    You may need to give the "Git-Hub-Manager" file permissions as an executable. 
    You can do this by typing in terminal
    $ chmod +x Git-Hub-Manager
    
