# week7
Steps taken:
Exploit: User enumeration

The following are steps to take:
1.	After installation 
2.	One can access the login of wordpress by trying different login username and password 
3.	I used config.yml given credentials 

Versions affected are:

•	version 4.2 and version 4.7

[img]https://i.imgur.com/L39nuqH.gif[/img]

![](https://i.imgur.com/L39nuqH.gif[/img)



Vulnerability: XSS 
The following are steps to consider:
1.	After login as an admin
2.	Create a post 
3.	Navigate through pages
4.	Execute the following XSS script in the comment section
<IFRAME SRC=” javascript:alert(‘XSS’);”> </IFRAME>
Versions affected are:

•	version 4.0 and version 4.6


[img]https://i.imgur.com/LePZZ9m.gif[/img]

![](https://i.imgur.com/LePZZ9m.gif[/img)


XSS exploit by uploading a file
Steps to consider:
1.	login as an admin
2.	Go to new then post
3.	Upload an html file containing <SCRIPT>alert('XSS’) </SCRIPT>
4.	Publish it and then preview it to exploit

Versions affected are:
•	version 4.2 and version 4.9.1

[img]https://i.imgur.com/9rxItaF.gif[/img]

![](https://i.imgur.com/9rxItaF.gif[/img])




# Week8
