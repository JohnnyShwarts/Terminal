### Create a text file like in the first Terminal homework. - [Git_Task1.txt]()

1. Transfer the script to this file.

2. Opposite of each action - write command in Git Bash

3. Create file __“newFile.json”__. - ```touch newFile.json```
+ using touch ```touch newFile.json``` only creates. 
+ using echo ```echo > newFile.json``` only creates. 
+ using cat ```cat > newFile.json``` creates and can start appending to file. 
+ using vim ```vim newFile.json``` creates and can start editing the file.
+ using nano ```nano newFile.json``` creates and can start editing the file.

Add file under git. - ```git add new.json```

Commit the file. - ```git commit -m 'new.json'```

Push the file to an external GitHub repository. - ```git push```

Create files __new2.json, new2.xml, new2.txt__ - ```touch new2.json new2.xml new2.txt```

Add files under git. - ```git add .```

Commit files. - ```git commit -m '3 files'```

Push files to external GitHub repository. - ```git push```

Edit the contents of the file __“new2.txt”__ - write information about yourself (name, age, number of pets, future desired salary).
-  vim new2.txt - press i - full name - Johnny Shwarts
-  age - 33 years 
-  number of pets - 1
-  desired salary - $1000
-  press Esc - enter: wq
