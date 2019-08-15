# upstrem
open infra upstream training
# exercise

# verify your current directory

$ pwd


#list the directiry

$ ls -alt


# Did you find .ssh directory on your list?



# if yes check what's the rsa keys in it for pub and private?

$ ls -lt .ssh


# if not create an ssh key (or you can create ssh key anyway and override the existing files


ssh-keygen -t rsa -b 2048


# check contetnt of your pub key

An example session by prof. J.A.Gokhale assuming his email is jagokhale@onmail.org

[gokhalej@vindhya ~]$ ssh-keygen -t rsa -b 2048
Generating public/private rsa key pair.
Enter file in which to save the key (/home/gokhalej/.ssh/id_rsa):
Created directory '/home/gokhalej/.ssh'.
Enter passphrase (empty for no passphrase):jagokhale
Enter same passphrase again:jagokhale
Your identification has been saved in /home/gokhalej/.ssh/id_rsa.
Your public key has been saved in /home/gokhalej/.ssh/id_rsa.pub.
The key fingerprint is:
"README" [readonly] 67L, 2571C         
9f:83:66:88:b4:f0:07:5c:c3:27:5e:7c:17:13:73:d9 gokhalej@vindhya
The key's randomart image is:
+--[ RSA 2048]----+
|            =..o |
|     . .     =. E|
|      = + . .    |
|   . o = . .     |
|  . + . S        |
|   + + . o .     |
|    + o + +      |
|     . o   .     |
|                 |
+-----------------+
[gokhalej@vindhya ~]$ ls .ssh
id_rsa  id_rsa.pub
[gokhalej@vindhya ~]$ more .ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAABIwAAAQEA9rwCqjcmrUw1TMhe02BlG1mo5p6Nd2ebWClygPYjOb7DrZtCI7+THepMNfeOFzV1X2hskXQtIJL08IFX7SQKyKpVVi7V+J77kRuALi+0NetyYGeRPuqAMQCn/vL
NOnUPYDkzDDjv9fkHWRK7NRYOtSPRGLWyWv8ORBUc2esh9g663iRIdYalW9vdbgUbp8kBoU6l0Kvo2qq4V/Z8TLBp4kEwpiJoSOS3HeMUO9pWBIGaWIyviKu5JyhOCNspiVTWkufT6iFhwUeQ7nUOC6i3+Z07RG
/Nk4Y5P2If8EHiJ5Mijz13fbOHBYySp5mJ0Vi/LraNLy/p0SfMkaBqnrA16w== gokhalej@vindhya

# Note you need not reveal your private key, just use or copy your public key content and post to your OpenStack account when you access from this server or to your github upstream project here. (https://github.com/opentechfn/upstrem/). You must signin here and add your ssh key before you can use this, you will get invite for adding your email here from project owners Gokhale or Digambar.

Youcan have similar keys from other serevrs that use to access openstack account. As many keys you need you can use, but more than 2 or 3 is enough else you loose  track of what you did from where and when,

# Done now make sure you learn visual editor vim or vi to edit this file and add your entries where you need to test your vi skills.
# if you are happy with your notepadd++ on widows or some other IDE of your choice ignore this.

Other notes or refernces for quick learning.
Please read: How to use linux at command line/  https://ryanstutorials.net/linuxtutorial/
How to use vi or vim editor - https://www.cs.colostate.edu/helpdocs/vi.html
How to program in python 2 or 3 - https://www.cse.unsw.edu.au/~en1811/python-docs/python-3.6.4-docs-pdf/tutorial.pdf
Note you will create a file in your emainame (eg. jagokhale) and submit it. Each user will submit their own folders as submissions for passing the upstream github test.

After you are sure you have completed the upstream training conducted by local mentors please submit or sene email to
info@opentechfoundation.in and cc (copy) your mentor to ensure they approve of your training completion.
