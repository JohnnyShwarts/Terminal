### Create a text file like in the first Terminal homework. - [Git_Task1.txt]()

1. Transfer the script to this file.

2. Opposite of each action - write command in Git Bash

3. Create file __“newFile.json”__. - ```touch newFile.json```
+ using touch ```touch newFile.json``` only creates. 
+ using echo ```echo > newFile.json``` only creates. 
+ using cat ```cat > newFile.json``` creates and can start appending to file. 
+ using vim ```vim newFile.json``` creates and can start editing the file.
+ using nano ```nano newFile.json``` creates and can start editing the file.

4. Add file under git. - ```git add new.json```

5. Commit the file. - ```git commit -m 'new.json'```

6. Push the file to an external GitHub repository. - ```git push```

7. Create files __new2.json, new2.xml, new2.txt__ - ```touch new2.json new2.xml new2.txt```

8. Add files under git. - ```git add .```

9. Commit files. - ```git commit -m '3 files'```

10. Push files to external GitHub repository. - ```git push```

11. Edit the contents of the file __“new2.txt”__ - write information about yourself (name, age, number of pets, future desired salary).

```vim new2.txt```
 - press ```i```
```txt
full name - Johnny Shwarts
age - 33 years 
number of pets - 1
desired salary - $1000
```
- press Esc - enter ```:wq```

12. Edit the contents of the __“new2.json” file__ - write information about yourself (name, age, number of pets, future desired salary). Everything is written in JSON format. - vim new2.json - ```vim new2.json``` 

- press ```i```

```Json
{
"Full N." : "Johnny Shwarts", 
"age" : 33, 
"animal" : 1, 
"salary" : 1000
}
```
- press Esc - enter ```:wq```

13. Add and commit __"new2.txt"__ in one line. - ```git commit new2.txt -m 'txt'```

14. Add and commit __“new2.json”__ in one line. - ```git commit new2.json -m 'json'```

15. Push changes to an external repository. - ```git push```

