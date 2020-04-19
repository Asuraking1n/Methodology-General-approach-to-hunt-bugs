                                \*    Method of Hunting by error_404_unavilable   */
                                 \*follow me on instagram-> @error_404_unavilable*/
                                  \*         Recon is Key of Success            */
1- Find subdomains using assetfinder or knock.py (you can use some websites also)

2- Check the live subdomains ( httpstatus.io)

3- Try to find subdomains of subdomains and their http status (more targets more opportunity)

4- Now try to search some github resporitries for any leakeage of imformation about the target (use queries like {example.com ' password'} 

5- Take the main domain and start hunting try all vulnerabilities listed below after main domain try to hunt on less 
   popular domain. (less popular means more chance to find bug)
   
8- Alaways try with low level vulnerabilities. (it increases your confidence,generally people try with high severity vulnerability and they loose patience and quit)

7- vulnerabilities list-----
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
  LOW LEVEL---
  -----------------------------------------------------------------------------------------------------------------------------------------------
  
1- Missing SPF record (use " https://www.kitterman.com/spf/validate.html " this site to check spf record)

2- Missing HSTS header ( use " https://www.ssllabs.com/ssltest/ " this site to check HSTS header )

3- No rate limit (use burpsuite sequencer or intruder to perform this attack try on OTP or E mails verification parts of any sites

4- URL redirection (find any parameter which have any kind of tendency to redirect)

5- Host header injection (try to change host parameter with any other site after intercepting target request) 

6- Account lockout (if after brute forcing wrong credentials your account get locked and even after puting write credentials it doesn't open than this is account lockout)
 
7- Buffer overflow (when any site stores user control data in memory buffer then it may be buffer overflow ex- search field try to put 1000 'z'(any character) thier)

8- Long password DOS attack (when any site don't have fix length on thier username and password field it may crash if we put 1000s of character their)

-----------------------------------------------------------------------------------------------------------------------------------------------
  MEDIUM LEVEL

-----------------------------------------------------------------------------------------------------------------------------------------------

1- Cross site scripting (check all refelected,store,DOM based and blind) 
 
2- HTML injection (try to inject simple HTML codes on parameter)

3- Inscure CORS configration (you can use curl command " curl http://any.com -H "Orgin:http://fb.com" -I)

4- Server side request forgery (Try to find parameters like - dest,url,uri,path,continue,window,next,data,file,site,html etc basically those params which redirects you somewhere) 

5- Source code Disclosure (there are several internal files which a developer forgets to hide you can simply use a list of file  to bruteforce and check source code disclosure {contact me on instagram for the list ig ID = @error_404_unavilable})

6- CSRF (alaways try csrf to account takeover, just think big to get big)

7- session fixation (it is game of cookies try to get the cookies of logged in IDs and paste it on another browser with another ID)

8- password reset poisining (try to find host header injection first)

9- SQL injection (try each and every place like cookies,header,main link etc)

10-Authentication testing

11-Server side includes injection

12-Multifactor Authentication

13-MySql Authentication bypass

14-CSRF same site bypass

15-IDOR (try to check every place where ID includes)

16-Heart bleed (security bug in OPenSSL crypto library)
------------------------------------------------------------------------------------------------------------------------------------------------
  HIGH LEVEL
  
------------------------------------------------------------------------------------------------------------------------------------------------

1- Parameter tempering (try to intercept the request and the values of params like if the price of hot dog is 12$ to to change the price parameter from 12$ to 1$

2- Hostile Subdomain take over (try to find nonj active sub domains, your can use a tool called subbrute)

3- Critical file disclosure (here are several internal files which a developer forgets to hide you can simply use a list of file to  bruteforce and check sensitive data disclosure {contact me on instagram for the list ig ID = @error_404_unavilable}))

4- command injection (when an application incorporates user-controllable data into a command that is processed by a shell command interpreter)

5- File uploading vulnerability (try to find insufficient checks of file upload)
   
   
  *** (these are RCE, same way on different place)***
6- Docker RCE
7- Postgres RCE
8- Apache spark Spark RCE
9- PHP MyAdmin RCE

10-File inclusion (Try to find parameters like - dest,url,uri,path,continue,window,next,data,file,site,html etc basically those params which redirects you somewhere)
------------------------------------------------------------------------------------------------------------------------------------------------

Try to combine two or more vulnerabilites this will increase the severity and chance of bounty also.
more the vulnerabilites more will be bounty...

Happy Hacking......







