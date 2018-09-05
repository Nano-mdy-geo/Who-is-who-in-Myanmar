# Who-is-who-in-Myanmar
This is  Who Is Who In Myanmar


							A PROJECT REPORT ON
						
							“Who Is Who In Myanmar”
							
       							       FOR
							       
						UNIVERSITY OF COMPUTER STUDIES (MANDALAY)

						SUBMITTED IN PARTIAL FULFILLMENT OF
					
						INTERNSHIP PROJECT UNDER THE GUIDANCE OF
						
						Director                  U Ravi Chhabra
						Supervisor                Dr. Wai Wai Zin
							
							     SUMITTED BY

					        Mg Thu Ya Tun	        Ma Aye Moe Aung
				    		Ma Yoon Me Me Mon	Ma Khaing Khaing Htwe
						Ma Than Than Htwe	Ma Phyu Thinzar Maung


					        UNIVERSITY OF COMPUTER STUDIES (MANDALAY)
						
							     September, 2018




                         			
						    ABSTRACT
        Nowadays, data and information are used for a variety of purpose in organization.Many people can view and search data and information by using webpage on the internet.When Myanmar is developing in information technology (IT) gradually, website, web application and webpage play a crucial role.Webpages are widely used everywhere in the world such as education, health, industries, governments, administration and business 	sectors etc.
	Our webpage “Who is who in Myanmar” is created and it describes the biography and news of national leaders, parties, artists and many sectors of Myanmar. Our webpage is one kind of searching information in Myanmar. So, user can find about people who live in Myanmar in seconds by online and they do not need to go anywhere. Materialize and Material CSS framework, Cascading Style Sheet (CSS), Bootstrap and Hypertext Preprocessor (PHP), Hypertext Markup Language (HTML),  are also used for adding style to web sites and making interactive webpages.

                                                
						
						ACKNOWLEDGEMENTS
 
        First, we respectfully thank to U Kyaw Zwa Soe, the Rector of University of Computer Studies (Mandalay),for his
kind permission to carry out this project, general guidance and workable environment during the period of study.
	
	Secondly, we would like to respectfully thank Dr. Sann Sann Tint, our pro-rector of University of 
Computer Studies (Mandalay), for her kind permission to carry out our project.
	
         We deeply thanks to Director’s U Ravi Chhabra, CEO of GEO Mandalar Investment & Technology Company, for his 
guide way to create our project with successfully and nicely.
	 
        We specially thank to our supervisor, Dr. Wai Wai Zin, Lecturer, Faculty of Computer Systems and Technologies, 
University of Computer Studies (Mandalay) for her valuable and constructive suggestions during the planning and development of this project. Her willingness to give her time so generously has been very much appreciated. Advice given by other academic lectures has been a great help in building the software solution.
	
 	We especially thanks to our teachers, parents and all our friends for their encouragement, help, providing 
many useful suggestions and giving us a great support during internship program. First, we would like to thankful greatly following persons who have contributed directly or indirectly the success of this project.
   
   	Finally, we would like to express our deepest gratitude and sincere thanks to all persons who contribute directly 
or indirectly towards the success of this project.


						Project Detail
				Project Title		Who is Who in Myanmar
				Project Id		Geo_Nano


						Group Member
		Roll no	Name			Signature				Date
		
		
		
		5CS-88				Ma Khaing Khaing Htwe		
		5CS-89				Ma Aye Moe Aung		
		5CS-90				Mg Thu Ya Tun		
		5CS-91				Ma Than Than Htwe		
		5CS-92				Ma Yoon Me Me Mon		
		5CS-163				Ma Phyu Thinzar Maung		

		
		
                  
Supervisor      :	Dr. Wai Wai Zin
Rank            :	Lecturer
Department      :	Faculty of Computer Systems and Technologies University of Computer Studies (Mandalay)









                                                         CONTENTS

ABSTACTS		
		
ACKNOWLEDEMENTS				
		
GROUP MEMBER LIST		
				
CHAPTER  1	INTRODUCTION                                              	
	1.1  Introduction	
	1.2  Objectives	
	1.3  Project  Scope	
		
CHAPTER  2	METHODOLOGY  	
	2.1 Require Analysis	
	2.2 Creating Acount	
	2.3 Learning Python Program	
	2.4 Creating Flask Application	
		
CHAPTER 3	DESIGN AND IMPLEMENTATION	
		
CHAPTER 4	CONCLUSION	
	4.1 Conclusion
	4.2 Advantages		
		
Reference

            						
							CHAPTER (1)
                                                       INRODUCTION

        Nowadays, web sites are used anywhere such as business, governmental, team, companies, organizations etc. Websites are typically dedicated to a particular topic or purpose ranging from entertainment and social networking for providing news and education. So, they are becoming an important part of our everyday life. Every user is capable to accept that information through this web sites.
        Myanmar is one of most interesting places in South East Asia. The world ‘Myanmar’ represents all the ethnic groups living in the country. The population of Myanmar is 60 million people that include politicians, business people leader, writers, artists, parties, members of parliamentary, business leaders, celebrity (they are beauty pageant, model, actor, vocalist, directors, promoter, and so on.) and also can know the unique popular people such as historical, figures, freedom, fighter, regional leader from parliament and very important to know about the famous people. 
	
1.1 Objectives
 	To know that how to use Github
 	To learn python programming fundamental
 	To apply heroku app 
 	To create design by using materialize and material  CSS framework
 	To work with group members to complete the lab   setup   
 	To develop portfolio and personal pages on GitHub and other platforms
 	To development modern software with Firebase and Heroku
 	To work and experience separate development roles to develop a product

1.2 Project Scope
    This project is designed and implemented for biography of Myanmar people. 
    The users of this system are: Admin and Normal users.
1.2.1	Admin
 	Admin can manage all the actions: retrieve, insert, delete, update of the system and 
	change up to date data information.

1.2.2	Normal users
        User can view by following function:
	• Data information
	• Famous people 
	• Birthdate
	• Father Name & Mother Name
	• Education
	• Ethnicity
	• Religion
	• Occupation
	• Ward village
    


   							CHAPTER(2)
							METHODOLOGY


2.1 Requirement Analysis
      Requirement analysis is the process of determining user expectations of a new or modified data information. Requirement analysis is critical to the success of a development project. Firstly, we discussed about the general purpose of the system. For example, we are playing vim adventure and then said to understand key by writing command prompt. Then, we are created accounts on github, heroku, codeacdemy respectively.
After gathering the requirements, we determined whether the stated requirements are unclear, incomplete, ambiguous, or contradictory, and then resolving these issues. Next, we documented the requirements in various forms, such as text files, process specification. 

2.1.1 Playing Vim Adventure Game



Key:
L right arrow    		
J down arrow
H left arrow  		
Kup arrow
Wword forward
E end forward
B backward of word
X delete character

2.2	 Creating Accounts


 There are three account in our project development .So, three accounts are –
i.	GitHub Account
ii.	Code Academy Account
iii.	Heroku  Account.


2.2.1 Marking a GitHub Account

 GitHub is a code hosting platform for version control and collaboration .It lets you and others
 work together on projects from anywhere.
      
2.2.1.1 How Git works?

   Here is a basic overview of how Git works:

i.	Create a "repository" (project) with a git hosting tool(like Bit bucket)
ii.	Copy (or clone) the repository to your local machine.
iii.	Add a file your local repo and "commit” the changes.
iv.	"Push" your changes to your master branch.
v.	Make a change to your file with a git hosting tool and commit.
vi.	"Pull" the changes to your local machine.
vii.	Create a "branch" (version) make a change commit.
viii.	Open a "pull request" (propose changes to the master branch).
ix.	"Merge" your  branch to the master branch 

   
2.2.1.2 GitHub Tutorial

  	This tutorial teaches you GitHub essentials like repositories, branches, commits,  and Pull Request. You'll create Hello Word repository and learn GitHub's Pull  Request workflow, a popular way to create and view code.
   First, we create  Github accounts and by learning GitHub Guide line with hello world repository.

Creating Repository
  When create a repository, we needs these facts are repository name(eg..Hello World) and write a short description and select initialize this repository with a README.
  Ecah GitHub account to create the following repository:
 
	i.   Python_exercise
	ii.  Coding_sprint
	iii. Hello_Geo
	iv.  Flask-mega-tutorial
	v.   Tilde
	vi.  Hello-world
	vii.  Flask-with -jinja


2.2.2 Making Code Academy Account
We create code academy account by studying 
•	Learn  git tutorial and
•	Learn the command line tutorial on code academy.              
First, we create codecademy accounts and login in to codeacademy and to start the learn git and command line tutorial with GitHub account. 
    
2.2.3 Create Heroku App Account
We are making function with Hero Account.
1.  Create   App on Heroku
2. Deploy   App with  github on Heroku
3. View   output from  Heroku 
4.  Getting started  on Heroku with Python
 
     
We can create app at most five app on each account. Heroku  Apps are connected with Github Account by marking deploy master branch and delete this repository.
Heroku is to perform many function with Python. We learn python code by connecting with Heroku.

2.3 Learning Python Program
       We run python exercise 50 in GitBush source code editor with a Python application programming interface (API). Using GitBush command prompt, we use common commands are cd, touch, vim, git add, git commit, git push and so on.









We run python exercise 50 with GitBush and run the program using the cd, touch, vim, git add and git comit repesectively.
 












Figure 2.9Run python ex1.py
2.4 Creating Flask Framework Application

Flask is fun. This bold declaration is one of the first things you see when you view the official Flask documentation and, you will come to understand why so many Python developers agree.

2.4.1 What is flask?

Flask is a lightweight Web framework written in Python. Flask started out as an April fool's joke that became a highly popular underdog in the Python web framework world. At its core, it provides a set of powerful libraries for handling the most common web development tasks, such as:


•	Install flask
•	Create flask program from github run with browser
•	URL routing that makes it easy to map URLs to your code
•	Template rendering with Jinja2, one of the most powerful Python template engines
•	Session management and securing coolies
•	HTTP request parsing and flexible response handling 
•	Interactive wen-based debugger
•	Easy-to-use, flexible application configuration management




 
Figure 2.10 Create flask program with jinja template




							CHAPTER (3)
						Design and Implementation
Web Sites are Among popular website our created “Who is who in Myanmar”. Our website shows the biography famous people among in our country. Famous people such as candidate from parties, members of parliamentary, business leaders, celebrity (they are beauty pageant, model, actor, vocalist, directors, promoter, and so on.) and also can know the unique popular people(such as historical, figures, freedom, fighter, regional leader from parliament and very important to know about the famous people.). This site is intended only to view information such as Wikipedia.
3.1 Who is who in Myanmar
 
 Figure(3.1) Menu View







3.2 Home Page
This page shows about of  Our project’s topic. 
 
Figure(3.2) Home Menu 
3.3 About Page
This page describe our project scanerio by clicking About link in Footer Tag.
 
		Figure(3.3) About of Our Project View
3.4 Spec Page
This page describe our internship program flow by clicking Spec link in Footer Tag.
 
Figure(3.4) Steps of Internship task
3.5 Contact Page
This page describe our roles by clicking Contact link in Footer Tag.
 Figure(3.5) Description of Group
3.6 Author Page
Our project shows information of person in myanmar. This data have in Author Page. Author page has five sub topics. They have member, party, business, celebrity and modern historical figure. Celebrity have five sub topics and Modern Historical Figures have three sub topics. These topics have famous person’s information in myanmar. 
 
Figure(3.6) Author View










3.6.1 Members
  Members of parlimentary try to develop our country with associated roles. Their biography and skill can be known in this page. For example, President U Win Myint and Daw Aung San Su Kyi.  
This page is clicking Member tab from Author page.
 
Figure(3.6.1) Daw Aung San Su Kyi- Member of parlimentary
 
Figure(3.6.2) President U Win Myint-Member of Perlimentary
You can click ‘read more’ button if you would like to do more.
 
Figure(3.6.3) About of Daw Aung San Su Kyi

 
Figure(3.6.4) About of U Win Myint









3.6.2 Party
Governments have many parties. They are making ability to apply for developing our country. Many parties have appeared after freedom Era. For example, NLD and USDP parties are famous in myanmr.
This page is clicking Party page from Author Page.
 
Figure(3.6.5) USDP-Party
 
Figure(3.6.6)NLD-Party
3.6.3 Business Leader
Business is one of the most important roles in each country.Everyone have to do business for lodging and bording.But some people can do not only for them but also for their country to improve their  business standard.In Myanmar,there are a few people like that.For example are as shown in the figure.
Daw Win Win Tint is a founder of modern mini market(City Mart).
U Zaw Zaw is a CEO of Myanmar Football and Max Company Owner.





















This pages are clicking Business leader tab from Author page.
 
Figure(3.6.7) Daw Win Win Tint- Business
 
Figure(3.6.8) U Zaw Zaw- Business



3.6.4 Celebrity Page
This page is clicking Celebrities Tab in Author page.
 
Figure(3.6..9) Celebrities View in Author Page













3.6.4.1 Model
As my opinion,model is the image of the country because most of the models have been participating in many international contests.Many people from different countries are watching what they will do.If the models do right or wrong,people will say them by name including their country name that they are good or not.Model from Myanmar as an example is Moe Set Wine.
This page is clicking model tab in cele tab from Author page.
 
		Figure(3.6.10) Moe Set Wine-Model










3.6.4.2 Actor
In Myanmar;actors are only famous in our country since they are not Hollywood stars.But they gain a lot of love from Myanmar people as they try best to act.
This page is clicking actor tab in cele tab from Author page.
 
 
		Figure(3.6.11) Nay Toe-Actor







3.6.4.3 Director
Myanmar directors are still trying and trying and trying to become their movies international. Directors are making different film types such as comedy, drama and horror but almost movies are comedy film type. For example, Wyne
This page is clicking director tab in cele tab from Author page.
 
			Figure(3.6.12) Wyne-Director








3.6.4.4 Vocalist
Singer entertain the people with their songs.The songs of the singers can release the stress of the people.Song types are R&B, Rock, Pop, Classical and so on.Sai Sai is the example of the famous singer in Myanmar.
This page is clicking vocalist tab in cele tab from Author page.
 
Figure(3.6.13) Sai Sai-Vocalist












3.6.4.5 Beauty Pageant
Desribe above as Model, for example, Han Lay.
This page is clicking beauty tab in cele tab from Author page.
 
				Figure(3.6.14)Han Lay-Beauty Peagant











3.6.5 Modern Historical Figure
This page is clicking Modern Historical Figures Tab in Author page.
 
                   figure(3.6.15) Modern Historical in Myanmar













3.6.5.1 33Comrades Page
Comrades donated their lives for our country. They did not scare to lose their lives. They only cared to have the independence of our country. Because of them, we can stand as the Myanmar people nowadays. The situation of our country may be bad but we still love our country and we hope the future of the Myanmar is better than today. I’m so proud to represent about the comrades
This page is clicking comrade tab in modern historical figure tab from Author page.
 
Figure(3.6.16) General Aung San-33Comrade
 
Figure(3.6.17) Master Zaya-33Comrade















3.6.5.2 Regional Leader
Minister make the best tasks in associate with roles each their towns. They are supported for developing country in some places. For example, U Phyo Min Thein is carried to solve traffic problems in Yangon Devision.
This page is clicking regional leader tab in modern historical figure tab from Author page.
 
 
Figure(3.6.18) U Phyo Min Thein-Regional Leader




3.6.5.3 Freedom Fighter
Freedom Fighter is trying to do modern and development country. They don’t care other things and they take care of their country do well. In my country, Daw Aung Sun Su Kyi is one of the most in Freedom Fighter. She’s information is describe in above (member page).






















3.7 Latest Page
This page shows latest update information in this website.
 
		figure(3.7) View of Latest Page













3.8 Search Page
This page search information of famous person in Myanmar. This page come back turn into Author Page.
 

		Figure (3.8) Search Page










								CHAPTER (4)
								Conclusion
4.1 Conclusion
The project is intended to search detail of famous person in Myanmar. By using this website, user can view biography and can know their lifetime without time consuming. So we would like to invite you to visit our website. 


4.2 Advantages
•	Our website can search data from various roles in one site such as member of union, business leader, celebrity and so on. 
•	Users can access the information from and device connected to the Internet using a standard browser. 
•	There is no need for extra training of that person who is using it.

References
http://www.yunkey9.com/
https://www.jetbrains.com/pycharm/whatsnew/
https://www.python.org/dev/peps/pep-0008/#introduction
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
http://www.gitlub.com/
https://www.codecademy.com
https://lostfootsteps.org/en
https://vim-adventures.com/
https://herokuapp.com/
https://wikipedia.com/





