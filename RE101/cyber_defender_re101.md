#  Cyber Defenders RE101 Lab Writeup
   We need Remnux distro and Window 10 or something...

#  Question 1: File: MALWARE000 - I've used this new encryption I heard about online for my warez; I bet you can't extract the flag!

<img width="1208" height="663" alt="2" src="https://github.com/user-attachments/assets/e12cd013-b4c3-44cb-8e66-3b53c4a4d95f" />

Answer: "flag<0ops_i_used_1337_b64_encryption>"

Explanation: Running the strings command on malware000 file revealed a Base64 encoded string that I decoded to obtain the flag.

#  Question 2: File: Just some JS - Check out what I can do!

<img width="1230" height="840" alt="1" src="https://github.com/user-attachments/assets/8556c12b-a362-49f9-970e-1bbb0c2dd149" />
<img width="1219" height="778" alt="2" src="https://github.com/user-attachments/assets/0173aff5-44bc-4f59-97f2-af6b7630a5e0" />

Answer: "flag<what_a_cheeky_language!1!>"

Explanation: Running the strings command on just_some_js file revealed a JSFuck Language encoded string that I decoded to obtain the flag.

#  Question 3: File: This is not JS - I'm tired of Javascript. Luckily, I found the grand-daddy of that lame last language!

<img width="1353" height="899" alt="1" src="https://github.com/user-attachments/assets/7deb4320-2d40-4f30-acd5-c70069cd2fa8" />
<img width="1217" height="957" alt="2" src="https://github.com/user-attachments/assets/7b69fe27-4691-45b8-9249-b18ddff6a7ba" />

Answer: "flag<Now_THIS_is_programming>"

Explanation: Running the strings command on this_is_not_js file revealed a Brainfuck Language encoded string that I decoded to obtain the flag.
