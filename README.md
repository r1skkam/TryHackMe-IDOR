[TryHackMe | IDOR](https://tryhackme.com/room/idor)

# TryHackMe-IDOR
`Learn how to find and exploit IDOR vulnerabilities in a web application giving you access to data that you shouldn't have.`

## Task 1 What is an IDOR? 
*Insecure Direct Object Reference*

## Task 2 An IDOR Example
`http://online-service.thm/profile?user_id=1305`

`http://online-service.thm/profile?user_id=1000`

`https://onlinestore.thm/order/1234/invoice`

`https://onlinestore.thm/order/1000/invoice`

## Task 3 Finding IDORs in Encoded IDs
[Base64 Decode and Encode - Online](https://www.base64decode.org/)

## Task 4 Finding IDORs in Hashed IDs
[CrackStation - Online Password Hash Cracking - MD5, SHA1, Linux, Rainbow Tables, etc.](https://crackstation.net/)

## Task 5 Finding IDORs in Unpredictable IDs

## Task 6 Where are IDORs located 
**/user/details**

**/user/details?user_id=123**

## Task 7 A Practical IDOR Example
**https://LAB_WEB_URL.p.thmlabs.com**

**/api/v1/customer?id={user_id}**

[What is the username for user id 1?](https://github.com/r1skkam/TryHackMe-IDOR/blob/main/id%201.png)

[What is the email address for user id 3?](https://github.com/r1skkam/TryHackMe-IDOR/blob/main/id%203.png)
