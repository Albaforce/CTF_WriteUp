# Challenge " ghost "
## Descreption 
Something mysterious seems to be lingering in these files. As if a ghost left his trace! 
Although she's unseen but she's trying to whisper some secrets, try to reveal them~

~you may want to check discord as well ~ 

# initial analysis
From the descreption i notice that for sure i need to focus to some details because they are talking about ghost == hidden things == things you can't see. Also we only have .xlsm file and the first guess in my mind is something in the macros .

# analysis 
When opening the file this image pops up, and if you focus more you can see the name of sheet " Sheet one and **!only** " means there is another hidden sheet.

![image](https://github.com/user-attachments/assets/49f32b32-4f1e-4f2d-9610-b0a747ebe69d)

The second sheet have some arabic flags and text on it to ** pray and support them **, when making some changes on them " moving ,changing text color, deleting "
i notice that there is a text hidden below **lebanon flag** and said  **"Can_You_See_My_ghostie_Password?"** but where to put it ?

<img src="https://github.com/user-attachments/assets/d111931a-c785-4e5d-ab01-b7b90f51435c" alt="image2" style="width:400px;height:400px; display: flex; "/> <img src="https://github.com/user-attachments/assets/feb092bb-b599-430c-8df5-298a50606d08" alt="image3" style="width:400px; display: flex;"/> 

After checking the macros i found this one that ping to this website *https://pastebin.com/wAxAYrx1*
```
Rem Attribute VBA_ModuleType=VBAModule
Option VBASupport 1
Sub ghost()
https://pastebin.com/wAxAYrx1
End Sub
```
Using the previous password "Can_You_See_My_ghostie_Password?" give us this hex code :
```
don't forgot to pray for palastine/sudan/syria :)  here's your flag mate ( or .. 3 more steps to it, UK, I'm a ghost, u need to
break a lot of barriers in order to communicate with me ! ) :
4e 33 71 38 72 79 63 63 41 41 54 41 43 70 51 69 34 41 41 41 41 41 41 41 41 41 42 79 41 41 41 41 41 41 41 41 41 4a 6e 4c 64 38 54
49 6f 6d 39 41 54 4a 76 76 53 61 42 38 77 64 53 48 6b 30 42 38 59 6a 42 4a 7a 65 61 4b 55 6b 46 5a 67 69 34 48 32 79 50 56 46 68
51 59 57 4a 31 31 33 78 50 50 46 39 41 49 55 4a 4c 2f 72 6a 65 6a 44 55 53 78 77 56 78 36 75 49 68 52 6b 53 39 65 31 66 33 6e 4d
48 4f 4b 47 76 2f 36 52 38 79 4a 70 56 67 6f 2b 55 4a 43 6f 72 59 76 5a 58 49 47 56 2f 38 37 57 69 72 55 51 65 2b 62 39 30 44 4b
58 38 4a 65 43 61 37 31 6e 67 53 63 43 54 35 33 76 69 55 56 2f 74 35 54 61 53 6b 66 4b 54 70 57 7a 6d 44 37 48 32 4a 33 71 52 58
61 63 57 38 49 71 6a 6d 53 4a 6f 76 31 4c 61 67 65 43 46 6e 48 53 53 6e 77 43 71 4a 4a 30 66 38 64 5a 4e 30 47 75 39 56 41 49 6e
5a 6a 39 57 71 71 79 72 72 75 69 30 42 45 6f 63 55 76 70 55 41 6c 62 51 78 79 4d 51 74 66 44 39 6a 37 79 4c 75 77 59 58 5a 42 72
37 71 56 64 58 54 36 76 6d 6c 5a 4a 34 61 6f 5a 33 32 79 33 65 6f 69 76 44 6d 33 64 51 33 6f 50 54 62 38 38 69 6b 49 6a 41 45 45
42 67 41 42 43 59 44 67 41 41 63 4c 41 51 41 43 4a 41 62 78 42 77 45 53 55 77 39 58 41 54 67 68 51 54 7a 63 44 4b 45 43 37 7a 4b
78 73 36 79 33 49 53 45 42 41 41 45 41 44 49 44 57 67 74 73 41 43 41 6f 42 76 4e 70 50 52 41 41 41 42 51 45 52 47 77 42 6d 41 47
77 41 59 51 42 6e 41 43 34 41 64 41 42 34 41 48 51 41 4c 67 42 30 41 48 67 41 64 41 41 41 41 42 6b 41 46 41 6f 42 41 4c 38 47 52
32 6d 47 38 4e 6f 42 46 51 59 42 41 43 41 41 41 41 41 41 41 41 3d 3d
``` 
As you see it's an hex code, so going to *https://gchq.github.io/CyberChef/* to see what's hidden here :
**From HEX** the output is :
```
N3q8ryccAATACpQi4AAAAAAAAAByAAAAAAAAAJnLd8TIom9ATJvvSaB8wdSHk0B8YjBJzeaKUkFZgi4H2yPVFhQYWJ113xPPF9AIUJL/rjejDUSxwVx6uIhRkS9e1f3nMHOKGv/6R8yJpVgo+UJCorYvZXIGV/87WirUQe+b90DKX8JeCa71ngScCT53viUV/t5TaSkfKTpWzmD7H2J3qRXacW8IqjmSJov1LageCFnHSSnwCqJJ0f8dZN0Gu9VAInZj9Wqqyrrui0BEocUvpUAlbQxyMQtfD9j7yLuwYXZBr7qVdXT6vmlZJ4aoZ32y3eoivDm3dQ3oPTb88ikIjAEEBgABCYDgAAcLAQACJAbxBwESUw9XATghQTzcDKEC7zKxs6y3ISEBAAEADIDWgtsACAoBvNpPRAAABQERGwBmAGwAYQBnAC4AdAB4AHQALgB0AHgAdAAAABkAFAoBAL8GR2mG8NoBFQYBACAAAAAAAA==
```
We notice that the output ends with "==" so its likely coded in BASE64, using the same website to decode it:
**FROM BASE64** the output is :
```

```
