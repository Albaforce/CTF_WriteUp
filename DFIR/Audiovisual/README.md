 # challenge : 
- title: Audiovisual  
- description: 
Too much noise, i can't hear anything, but can i see ?

# initial analysis :
When i listened to the song there is nothing to figure out, but when rereading the descreption " *i can't hear anything, but **can i see ?*** It came to my mind that there must be some form of steganography. .

# Tool used " sonic visualiser " :
Sonic Visualiser is a free, open-source application multiplatforme, designed to be the first program you reach for when want to study a music recording closely, using it can be helpful cause it allows us to visualize audio frequencies, which can reveal hidden images in the spectrogram.
install *sonic visualiser* 
`sudo apt install sonic-visualiser`
open the Flag.wav on it 
`sonic-visualiser Flag.wav`

# analysis :
From the first image we can see that there is something hide in the first part of the audio.

![image](https://github.com/user-attachments/assets/b0ba9056-025d-4692-9c06-ec38b78d547d)

After viewing how to use this software, and after just using **Pane -> Add Spectogram** :

![image](https://github.com/user-attachments/assets/4978e675-365d-446d-992d-207f12f1c0a9)

It comes to my mind to clear this image even more and playing with colors using *canva or photoshop*, and here is the final result:

![image](https://github.com/user-attachments/assets/65f10afc-4cd2-4e17-a88c-8d2a67dbd3db)

After spending about two hours changing colors, hopping from one website to another, hoping to find a useful tool, but nothing worked, nothing useful, **it's time to use a ...

![image](https://github.com/user-attachments/assets/4136d9bb-d1e4-4688-9bbc-53ca29b3aaba)

The hint was **" Focus on the image you are too close "**. 
If you focus closely you can see that the dots in the image is **Braille code**.
***Braille code**is a code based on six dots, arranged in two columns of three dots, it's  a great way for blind people to read and write.*
After seeing the pattern, it resembled the six-dot arrangement of Braille, i use wikipedia this time to decode the dots.

![image](https://github.com/user-attachments/assets/fe9149b4-3ab9-4fe0-ab7b-bee4ba42960d)

The flag is `SECAI{THEQUITTERYOUBECOMETHEMOREABLEYOUHEAR}`
# Conclusion 
Sometimes, instead of rushing to use tools randomly, take a step back and think—what is this challenge trying to tell me? What clues do I have? How do I approach it logically? Critical thinking is often more valuable than just relying on tools.
