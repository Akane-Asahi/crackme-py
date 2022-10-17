# PicoCTF picoGym Practice Challenges | Crackme-py

![Thumbnail](https://user-images.githubusercontent.com/111799231/196196419-b23dd1a9-6e26-46db-9229-0e7c10328ef2.jpg)

>Bored to read all the text? Well I can read it for you. Go to my Medium link (
https://medium.com/@theakaneasahi/picoctf-picogym-practice-challenges-crackme-py-39b227ee06a7 ) and there is options that will read all these below texts for you.

**What**
```
picoCTF{1|\/|_4_p34|\|ut_f3bc410e}
```

**How?**  

Step 1: 
When you'll "`wget`" the file, "`cat`" it.

<img width="482" alt="code1" src="https://user-images.githubusercontent.com/111799231/196198756-0ad24f9c-2724-4403-b72c-39296a910d85.png">
<img width="419" alt="code2" src="https://user-images.githubusercontent.com/111799231/196199102-a19cb48d-2f85-402b-9141-1061b9271ee0.png">

So, you'll see there are 2 methods, `decode_secret()`, `choose_greatest()`. But only choose_greatest is called. 

**Step 2:**
```
nano crackme.py
```
This will open editing option for the python file. Call the decode_secret() function. Call it before or after choose_greatest() method, doesn't really matter. You can also delete or comment out the calling of choose_greatest()function, as we don't need this actually. I didn't delete the call for the choose_greatest()function as you can see below picture.

<img width="328" alt="flag" src="https://user-images.githubusercontent.com/111799231/196196778-b2d9e077-c31c-4584-8c4b-04176504322d.png">


**Why?**  
Get used to edit python programming
This time you didn't have to program or decode anything to get the flag, but this is the indication that you will have to write your own decode function later.


