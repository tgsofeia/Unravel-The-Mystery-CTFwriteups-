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
> _Flag: PROC{73T1T80}_

### 2.	OSINT-101

![image](https://github.com/user-attachments/assets/9ff7148d-f93b-4c96-894a-fa7d4a57bf47)

Visual-centric social platform? Might be Instagram. And found this username on the same page

![image](https://github.com/user-attachments/assets/24083307-fc29-4677-9a83-52e6cbd646ef)

Okay! Found another clue on her Instagram page. 

![image](https://github.com/user-attachments/assets/2d6341d5-e75f-4e0c-a620-8998535611ab)

Copy and paste it on dcode website and now we know it was ROT8000 cipher.

> _Flag: PROC{3zpz_l3m0n_squ33zy}_

### 3.	Hideout#1

![image](https://github.com/user-attachments/assets/a57a8fbf-121e-460d-8bea-73e0634153cb)

Linkedln - click the credential. </br>
Then, found photo (dog). Search `Russian hacker` on imgur website.  Found this comment.

![image](https://github.com/user-attachments/assets/c962986b-fde0-423f-9b3f-40c6a5217b7e)

Click anything on this github and found this.  

![image](https://github.com/user-attachments/assets/4789c655-7dba-4d89-8b5d-609b3508823d)

Decode this and get the first flag.

![image](https://github.com/user-attachments/assets/1d448a89-b134-462b-a923-04b5528fc9af)

> _Flag:  PROC{Russ14n_H4ck3r_D4b3st}_

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
> _Flag: PROC{k0r34nh4ck3r_n3wfr13nd}_

### 5.	Hideout#3

![image](https://github.com/user-attachments/assets/25711ddd-6a55-4f78-b9e6-d69dbc441120)

So, we already got the registered vehicle manufacturer on previous challenge. </br>
Try to find it using finnik website and got the Volkswagen Golf. </br> 
Try to find the dealer on google and find this picture in the reviews section.

![image](https://github.com/user-attachments/assets/e5e01a4e-07a4-4c14-830c-c2fd0c72af5f)

There’s code on this picture. Decode and get the flag. </br>
> _Flag: PROC{W3lc0m3_T0_0uR_H1d30ut}_

## Cryptography

### 1.	All about that Base

![image](https://github.com/user-attachments/assets/cc466b26-c2e4-4b03-9035-b319a812b9df)

Download the txt file.

![image](https://github.com/user-attachments/assets/fda113e2-0117-47a8-8a9a-7e1d3894bf45)

Copy it on cyberchef and you will get the flag.

![image](https://github.com/user-attachments/assets/a18ab3ab-d620-4d83-bbe2-93a0f80517dd)

> _Flag: PROC{l4y3rs_0f_b4s3s}_

### 2.	SHIK SHAK SHOK

![image](https://github.com/user-attachments/assets/99b3488c-f4bf-4b8b-94bd-f50f51f53987)

Download the image and u will see that the image is used tic tac toe code. </br>
Try to decode it using dcode website. U will find it was a shik shak shok lyrics. </br>
But somehow there’s wrong spelling on the lyrics. So, that was the flag.

> _Flag: PROC{TICTACTOE}_

### 3.	That’s it??

![image](https://github.com/user-attachments/assets/ca8a86a3-5d5a-4c08-a476-587d1eeb7c53)

Download the txt file.

![image](https://github.com/user-attachments/assets/0d2ed582-130f-46ee-a1ae-c8688a739359)

Get this code but not really what is this? so try to identify this using dcode and get the answer. It was brainfuck code. Get the brainfuck interpreter and decode it.

![image](https://github.com/user-attachments/assets/1d4b0714-8900-4201-9bc4-8c5b353f1e8c)

So, it is base64 and decode it using cyberchef. And get this.

![image](https://github.com/user-attachments/assets/ecefca7c-10c8-4a63-af00-3dcc76b2c5b3)

Identify it and it was JSFuck and decode it using dcode. Got the flag. </br>
> _Flag: PROC{3S0t3r1c_1s_th3_w4yy}_

## Web Exploitation

### 1.	Feedback Form

![image](https://github.com/user-attachments/assets/868d937d-e853-4cfe-938a-25195e5f8f60)

Click the link.

![image](https://github.com/user-attachments/assets/db76dede-a186-443a-b1a9-54f42628c4a9)

> _Flag: PROC{XSS_f4ls3_f33dback}_

### 2.	Biskut Sedap

![image](https://github.com/user-attachments/assets/c76aeb69-c40f-416c-8e29-0af911b60c9d)

Inspect it.
> _Flag: PROC{0re0_c00kies_t3rb4ik}_

### 3.	Penyimpan Rahsia

![image](https://github.com/user-attachments/assets/540d3375-083b-4ac0-ad3c-bdde922940f6)

Click the link. </br>
Try to inspect it but got nothing. Maybe try to use robots.txt and get this.

![image](https://github.com/user-attachments/assets/ee1c3cd6-758e-4b03-b6ed-3e3cc687a729)

> _Flag: PROC{r0b0ts_peny1mp4n_r4hsi4}_

