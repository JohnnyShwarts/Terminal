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
},
```
- press Esc - enter ```:wq```

13. Add and commit __"new2.txt"__ in one line. - ```git commit new2.txt -m 'txt'```

14. Add and commit __“new2.json”__ in one line. - ```git commit new2.json -m 'json'```

15. Push changes to an external repository. - ```git push```

16. Edit the content of the __“new2.xml”__ file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in XML format. - ```vim new2.xml``` 

- press ```i```
```xml
<info>
<FullN>Johnny Shwarts</FullN> 
<age>25</age> 
<animal>1</animal> 
<salary>400</salary> 
</info>
```
- press Esc - type ```:wq```


17. Add and commit __“new2.xml”__ in one line. - ```git commit new2.xml -m 'xml'```

18. Push changes to an external repository. - ```git push```

19. Send Previous GitBush HW Terminal to an external repository. - ```git add .``` __->__ ```git commit -m 'la-la-land'``` __->__ ```git push```

20. In the GitHub web interface, create a __new3.txt file.___ - ```Add file``` __->__ ```Create new file``` __->__ ```Commit new file```

21. Edit the contents of the “new3.txt” file in the web interface - write information about your preferences (Favorite movie, favorite series, favorite food, favorite season, country you would like to visit). - ```Click on``` __new3.txt__ - ```Edit this file - Favorite movie - "SW", favorite series - "Big Bang Theory", favorite food - coffe, favorite season - summer, country you would like to visit - India, Australia.```

22. Make Commit changes (save) changes on the web interface - ```commit changes```

23. Synchronize external and local repositories (merge changes from external repository) - ```git pull```

24. Edit the contents of the __“new2.json”__ file in the web interface - add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, country you would like to visit). Everything is in __JSON format__ - 


```json
{
"FIO" : "Johnny Shwart", 
"age" : 33, 
"animal" : 1, 
"salary" : 1000, 
"favorite movie" : "SW", 
"favorite TV series" : "Big Bang Theory" , 
"favorite food" : "coffe", 
"favorite time of the year" : "summer", 
"the country you would like to visit" : ["India, Australia"]
},
```
25. Make a Commit changes (save) the changes on the web interface. - ```commit changes```

26. Synchronize external and local repositories - ```git pull```

27. Edit the contents of the “new2.xml” file in the web interface - add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, country you would like to visit). Everything is in XML format. - 

```XML
<info> 
 <FIO>Johnny Shwart</FIO> 
 <age>33</age> 
 <animal>1</animal> 
 <salary>1000</salary> 
 <favorite_movie>SW</favorite_movie> 
 <favorite_TV_series>Big Bang Theory</favorite_TV_series> 
 <favorite_food>coffe</favorite_food> 
 <favorite_time_of_the_year>summer</favorite_time_of_the_year> 
 <the_country_you_would_like_to_visit>India, Australia</the_country_you_would_like_to_visit> 
</info>
```
28. Make Commit changes (save) changes on the web interface - ```Commit changes```

29. Synchronize external and local repositories - ```git pull```
