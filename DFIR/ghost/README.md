# Challenge " ghost "
## Descreption 
Something mysterious seems to be lingering in these files. As if a ghost left his trace! 
Although she's unseen but she's trying to whisper some secrets, try to reveal them~

~you may want to check discord as well ~ 

# initial analysis
From the description, it's clear that I need to focus on hidden details, as the reference to a "ghost" suggests something unseen or concealed. Additionally, the only provided file is an .xlsm (Excel macro-enabled file), which immediately makes me think that the macros might contain something important. 

# analysis 
### Step 1: Inspecting the excel file
Upon opening the file, an image pops up. If you pay close attention, you can see that the sheet is named " Sheet one and **!only** " means there is another hidden sheet.

![image](https://github.com/user-attachments/assets/49f32b32-4f1e-4f2d-9610-b0a747ebe69d)

Indeed, after further inspection, I found a second hidden sheet. This sheet contained several *Arabic flags and text encouraging prayer and support*.

When I attempted to interact with the sheet by **moving elements, changing text color, or deleting content**, I discovered hidden text beneath the Lebanon flag and said  **"Can_You_See_My_ghostie_Password?"** but where should i use this password ? 

<img src="https://github.com/user-attachments/assets/d111931a-c785-4e5d-ab01-b7b90f51435c" alt="image2" style="width:400px;height:400px; display: flex; "/> <img src="https://github.com/user-attachments/assets/feb092bb-b599-430c-8df5-298a50606d08" alt="image3" style="width:400px; display: flex;"/> 

### Step 2:Examining the Macros
Since the file is macro-enabled (.xlsm), I checked the VBA macros and found the following script that ping to this website *https://pastebin.com/wAxAYrx1*
```
Rem Attribute VBA_ModuleType=VBAModule
Option VBASupport 1
Sub ghost()
https://pastebin.com/wAxAYrx1
End Sub
```
Using the previous password "Can_You_See_My_ghostie_Password?" give us this hexadecimal code :
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
### Step 3: Decoding the Hex DATA
Since the string was in hexadecimal, I used CyberChef *https://gchq.github.io/CyberChef/* to decode it.
Using the **From HEX**function, i obtained :
```
N3q8ryccAATACpQi4AAAAAAAAAByAAAAAAAAAJnLd8TIom9ATJvvSaB8wdSHk0B8YjBJzeaKUkFZgi4H2yPVFhQYWJ113xPPF9AIUJL/rjejDUSxwVx6uIhRkS9e1f3nMHOKGv/6R8yJpVgo+UJCorYvZXIGV/87WirUQe+b90DKX8JeCa71ngScCT53viUV/t5TaSkfKTpWzmD7H2J3qRXacW8IqjmSJov1LageCFnHSSnwCqJJ0f8dZN0Gu9VAInZj9Wqqyrrui0BEocUvpUAlbQxyMQtfD9j7yLuwYXZBr7qVdXT6vmlZJ4aoZ32y3eoivDm3dQ3oPTb88ikIjAEEBgABCYDgAAcLAQACJAbxBwESUw9XATghQTzcDKEC7zKxs6y3ISEBAAEADIDWgtsACAoBvNpPRAAABQERGwBmAGwAYQBnAC4AdAB4AHQALgB0AHgAdAAAABkAFAoBAL8GR2mG8NoBFQYBACAAAAAAAA==
```
We notice that the output ends with "==" so its likely coded in BASE64.
### Step 4: Decoding the Base64 Data
Using the same website to decode it:
**FROM BASE64** the output is :

![image](https://github.com/user-attachments/assets/9f6fdbac-ddcc-46ac-abb3-10369543b0fa)

as you can see in the first line we have **7z** so it's an 7z file.
### Step 5: Extracting the Archive
I saved the decoded data as download.7z and verified its format using the command:
```
file download.7z                                                                                                                                 
download.7z: 7-zip archive data, version 0.4
```
Using the command *7z l file* allow us to see the content of the file
```
7z l download.7z                                                                                                                                                                                                                      

7-Zip 23.01 (x64) : Copyright (c) 1999-2023 Igor Pavlov : 2023-06-20
 64-bit locale=en_US.UTF-8 Threads:32 OPEN_MAX:1024

Scanning the drive for archives:
1 file, 370 bytes (1 KiB)

Listing archive: download.7z

--
Path = download.7z
Type = 7z
Physical Size = 370
Headers Size = 146
Method = LZMA2:12 7zAES
Solid = -
Blocks = 1

   Date      Time    Attr         Size   Compressed  Name
------------------- ----- ------------ ------------  ------------------------
2024-08-17 04:18:24 ....A          731          224  flag.txt.txt
------------------- ----- ------------ ------------  ------------------------
2024-08-17 04:18:24                731          224  1 files


```
### Step 6: Unzip the file
Now the goal is to **brute-force** the file using **7z2john**, but using an entire wordlist is a time-consuming and beside that we have a hint "*ghost ghost ghost ....Love everything that has "ghost" in it 👻* 
we can say that the password has "*ghost*" in it. So from the *rockyoulist* we can only extract words with *ghost* in it using *grep*.
```
cat /usr/share/wordlists/rockyou.txt | grep -i "ghost*" > ghostlist.txt
7z2john Desktop/download.7z > Desktop/hash.txt
john --wordlist=ghostlist.txt Desktop/hash.txt                                                                                                                                                                                        
Using default input encoding: UTF-8
Loaded 1 password hash (7z, 7-Zip archive encryption [SHA256 128/128 AVX 4x AES])
Cost 1 (iteration count) is 524288 for all loaded hashes
Cost 2 (padding size) is 10 for all loaded hashes
Cost 3 (compression type) is 2 for all loaded hashes
Cost 4 (data length) is 214 for all loaded hashes
Will run 2 OpenMP threads
Press 'q' or Ctrl-C to abort, almost any other key for status
ghostwhisperer   (download.7z)     
1g 0:00:00:06 DONE (2025-01-31 15:54) 0.1494g/s 20.32p/s 20.32c/s 20.32C/s holyghost7..ghostring
Use the "--show" option to display all of the cracked passwords reliably
Session completed. 
```
The password is **ghostwhisperer**
### Step 7: Extract and Read the Flag

```
cat flag.txt.txt                                                                                                                                                                                                                      
Ai-impored ghost! now i can finally communicate with you humans! are you smart enough to detect my words ?
file flag.txt.txt                                                                                                                                                                                                                     
flag.txt.txt: Unicode text, UTF-8 text, with very long lines (315), with no line terminators
```
As you can see, displaying the content of the file *flag.txt.txt* didnt lead us to anything, the problem here is using **cat** to display it, because a regular cat will print the nulls to standard output, but your terminal will generally display them each as nothing, while cat -v represents them as ^@.
```
cat -v flag.txt.txt                                                                                                                                                                                                                   
Ai-M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-^MM-bM-^@M-^LM-oM-;M-?impored M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-bM-^@M-^MM-bM-^@M-^MM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-bM-^@M-^LM-oM-;M-?ghostM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^M! now iM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-^LM-bM-^@M-,M-bM-^@M-^M canM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-oM-;M-?M-bM-^@M-,M-oM-;M-? finallyM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-oM-;M-?M-bM-^@M-^MM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-^MM-oM-;M-?M-oM-;M-?M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-bM-^@M-^MM-oM-;M-? M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-bM-^@M-,M-bM-^@M-^LcommunicateM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-oM-;M-?M-bM-^@M-^LM-bM-^@M-^L withM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-oM-;M-?M-bM-^@M-^LM-oM-;M-? youM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-oM-;M-?M-bM-^@M-^MM-bM-^@M-^L humans! areM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-^MM-oM-;M-?M-oM-;M-?M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-oM-;M-?M-bM-^@M-^LM-bM-^@M-^M youM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-oM-;M-?M-bM-^@M-,M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-^MM-oM-;M-?M-oM-;M-? smart M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-oM-;M-?M-bM-^@M-^MM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-bM-^@M-,M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-oM-;M-?M-bM-^@M-^LM-oM-;M-?M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-^MM-oM-;M-?M-oM-;M-?enough M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-bM-^@M-^MM-bM-^@M-,to detectM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-oM-;M-?M-bM-^@M-^LM-bM-^@M-^M M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-bM-^@M-,M-oM-;M-?M-bM-^@M-^Lmy wordsM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-oM-;M-?M-bM-^@M-^LM-oM-;M-?M-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^LM-bM-^@M-^MM-oM-;M-?M-oM-;M-?M-bM-^@M-^M ?
```
and if you try to open the file in a texteditor like **vscode** or **sublime** you will have this output :
```
Ai-<0x200c><0x200c><0x200c><0x200c><0x200c><0xffef>impored .....etc
```
**<0x200c>** is The zero-width non-joiner (ZWNJ) (‌) is a non-printing character used in the computerization of writing systems that make use of ligatures. 

Using this website *https://330k.github.io/misc_tools/unicode_steganography.html* to decode the type of text and the output it :
**SecAI{4_gh0st_1n_th3_f1l3}** 

It's the **flag**
