1. Team members:
   Name: Zheng Zeng, Unity ID: zzeng
   Name: Hao Sun, Unity ID: hsun6
   Name: Huijun Zhang, Unity ID: hzhang12

2. Test framework:
   Test::Unit

3. Starting URL: 
   http://127.0.0.1:3000

4. Commands to run:
   In RubyMine, choose "Development: depot1" and click "Run"(which is a green arrow). Then start Mozilla Firefox and input "http://localhost:3000", you will go to the homepage.

   In Heroku, you should log in to see the project.

5. Extra functionalities except requirements:
(1) You can view your username when you log in, and logout anytime using the button.
(2) You can view whether you are the administrative user on the left.
(3) We used .css file to beautify the web page.


6. Guide:
(1)If you create user by clicking "Create User" on the left, it will create a normal user by default. If you want to test administrative user, you should click "Login", and login with user name: admin, password:123

(2)In the "Home" page, there is a list of posts just for briefly review. Please go to "Post and Reply" to post topics, reply topics, search topics or vote topics and replies.

(3)Normal users can only post topics, reply topics, search topics, vote topics and replies(at most once for each topic or reply, but cannot vote user's own topic or reply).
Administrative users can create other administrative users by clicking "Create User" and check "admin" box, delete users by clicking "Users".

(4)Topics are displayed according to the following rule: Order = Vote_num * 24 * 60 * 60 - (Time.now - created_at). 
This is a rule that the larger the "Order" is, the more front this topic will appear. Order is decided by vote number(one vote equals 24 hrs) minus time elapsed(in second). If Order = 0, this topic will be hidden.

7.a. Submit your git repo URL(or your app) to Expertia

     https://github.com/wshadowhunter/backchannel_final

  b. Submit your Heroku URL

     https://api.heroku.com/myapps/quiet-rain-1761

     email: wshadowhunter@yahoo.cn
     password: 6269939
