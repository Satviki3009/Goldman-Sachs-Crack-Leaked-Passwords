# Goldman-Sachs-Crack-Leaked-Passwords
Password Controls and Security Policies

OVERVIEW
-----------------------------------------------------------------------------------------------------------------------------------------------------------
As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. To be successful at your job you often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

PROJECT OBJECTIVE
-----------------------------------------------------------------------------------------------------------------------------------------------------------
Your job is to crack as many passwords as possible with available tools (e.g. use Hashcat).

Here are your task instructions:

What type of hashing algorithm was used to protect passwords?
What level of protection does the mechanism offer for passwords?
What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?
What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?
What would you change in the password policy to make breaking the passwords harder?

PROJECT REPORT & OBSERVATIONS
-----------------------------------------------------------------------------------------------------------------------------------------------------------
Linked below is a data file containing all the hashes dumped together:
https://github.com/Satviki3009/Goldman-Sachs-Crack-Leaked-Passwords/blob/f3c3c220953a64b2b0c416bd9fb12eeb76e6c18e/password_dump.txt

Using https://crackstation.net/ I cracked the given passwords & narrowed down my observations into this report. 


1)What type of hashing algorithm was used to protect passwords?
Ans: Md5

2)What level of protection does the mechanism offer for passwords?
Ans:  MD5 provides a very low level of protection

3)What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?
Ans: Controls to be implemented to make cracking harder:
i) Instill password salting.
ii) Using a hash algorith that prvides better security.

4)What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?
Ans: i) Minimum password length is set to 6.
ii) No rules or regulations for setting password - the policy accepts all lowercase & no special character passwords as well
 
5)What would you change in the password policy to make breaking the passwords harder?
Ans: i) The password limit should be set to minimum 8 characters.
ii) Use of atleast 1 special caracter ($ , % , & ...) along with uppercase letters should be mandatory.
iii) Avoid common words, DOB's or any other personal information. 
iv) A software that suggests changes to make the password stronger
