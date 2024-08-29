# Unravel-The-Mystery-CTFwriteups-
My first CTF write-ups. Go easy on me, I’m still learning ( ͡❛ ω ͡❛). There's more to come, so stick around!



## **Osint**

### 1. Yesterday is history
   
![image](https://github.com/user-attachments/assets/0ad01f21-b82d-42d0-9817-1bf6af767e22)

Copy the url and paste it on url decoder. And you will get the url : <br/>
https://github.com/pinxthepixie/yesterdayishistory <br/>
So, now we already have the account name and using intel techniques to find any social media accounts of this name. <br/>

![image](https://github.com/user-attachments/assets/58d8af70-8965-428d-a10f-289f4c20619d)

Found the code (base 64) and try decoding it using cyber chef. <br/>
_Flag: PROC{73T1T80}_

### 2.	OSINT-101

![image](https://github.com/user-attachments/assets/9ff7148d-f93b-4c96-894a-fa7d4a57bf47)

Visual-centric social platform? Might be Instagram. And found this username on the same page

![image](https://github.com/user-attachments/assets/24083307-fc29-4677-9a83-52e6cbd646ef)

Okay! Found another clue on her Instagram page. 

![image](https://github.com/user-attachments/assets/2d6341d5-e75f-4e0c-a620-8998535611ab)

Copy and paste it on dcode website and now we know it was ROT8000 cipher.

_Flag: PROC{3zpz_l3m0n_squ33zy}_

### 3.	Hideout#1

![image](https://github.com/user-attachments/assets/a57a8fbf-121e-460d-8bea-73e0634153cb)

Linkedln - click the credential. </br>
Then, found photo (dog). Search `Russian hacker` on imgur website.  Found this comment.

![image](https://github.com/user-attachments/assets/c962986b-fde0-423f-9b3f-40c6a5217b7e)

Click anything on this github and found this.  

![image](https://github.com/user-attachments/assets/4789c655-7dba-4d89-8b5d-609b3508823d)

Decode this and get the first flag.

![image](https://github.com/user-attachments/assets/1d448a89-b134-462b-a923-04b5528fc9af)

_Flag:  PROC{Russ14n_H4ck3r_D4b3st}_

### 4.	Hideout#2

![image](https://github.com/user-attachments/assets/b0ceb013-30b6-4b65-903e-6e79b690d438)

This is a continuation of the previous challenge. So, we got the message thru the code.

![image](https://github.com/user-attachments/assets/109a140b-a64d-4ed5-8e68-1adeedee9b92)

Try to find any famous Japanese blogging. (omeba) and search for rssianhacker. </br>
There's song lyrics on it. Found it on youtube and see anything that related to……. The comment.

![image](https://github.com/user-attachments/assets/30c9ce68-0bd0-4fa2-9afd-c720b0888b5c)

There’s nothing on his profile, try again and found his following which is koreanheker and get the next clue.

![image](https://github.com/user-attachments/assets/ad94e0cd-f6fb-455c-860d-289798bdc1c3)

Decode the message and get the next flag... wohoo </br>
_Flag: PROC{k0r34nh4ck3r_n3wfr13nd}_

### 5.	Hideout#3

![image](https://github.com/user-attachments/assets/25711ddd-6a55-4f78-b9e6-d69dbc441120)

So, we already got the registered vehicle manufacturer on previous challenge. </br>
Try to find it using finnik website and got the Volkswagen Golf. </br> 
Try to find the dealer on google and find this picture in the reviews section.

![image](https://github.com/user-attachments/assets/e5e01a4e-07a4-4c14-830c-c2fd0c72af5f)

There’s code on this picture. Decode and get the flag. </br>
_Flag: PROC{W3lc0m3_T0_0uR_H1d30ut}_

## Cryptography
