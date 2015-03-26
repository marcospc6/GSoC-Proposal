About me

Name: Marcos Paulo Espolador Chaves
Email: marcospc6@gmail.com	
Telephone: +55 (19) 98301-2470
Time zone: BRT (Brasília Time) UTC/GMT -3 hours
Source control username: marcospc6
Blog: http://marcosgsocpython.blogspot.com.br/ 


Short Bio

My name is Marcos Paulo Espolador Chaves, I’m a brazilian undergraduate student of computer science at University of Campinas, UNICAMP, currently in my last year of college. 
I have passion for developing and I’m a fan of open source software. I’ve been an internship at Sofist (http://www.sofist.com.br/) since my second year at college and recently I’ve been hired as a full time worker. Sofist is a software testing company but I always worked as a developer for both inside and outside solutions.
University

University: State University of Campinas, UNICAMP
Major: Computer Science
Current Year and Expected Graduation date: Currently in my 5th year, graduating at the end of this year
Degree: BSc
Background and coding skills

I have experience with C, C++, Java, Python, JavaScript, Maven, REST, Flask and Shellscript. For code versioning I’ve already made large use of SVN, but its been some time since I’ve only been using Git (feature branches FTW). Recently I started to use quality control tools such as SonarQube (it did wonders for me) and Jenkins.
A couple months ago my coworkers and I started porting some legacy C/C++ code to Python, a code that we have used to evaluate some images using OpenCV, for that, we have used NumPy and I definitely enjoyed the experience. 

I believe I can be of some help in making it better, mainly in solving the issue with porting parts of it from C (while maintaining optimal performance).
I’m an undergraduate but I’m already going through graduate courses at UNICAMP (aiming at my master’s degree), this semester I’m having classes with my friend and teacher Edson Borin (http://www.ic.unicamp.br/~edson/Home.html), the course is about techniques for development and acceleration of scientific applications (finding bottlenecks, making your application run faster, etc) and I feel I could apply that knowledge for this task.
At my work, recently I’ve been taking the place of the Scrum Master, dealing with retrospectives/plannings for the following sprints. Also been practicing delivering the results to our final client. So I believe exercising this skill in GSoC will make it even better.
Proposal Title

	Porting core functions of Numpy from C++ to Python/Cython
Proposal Description
Given my recent activities described above, while I was browsing the ideas page I felt the urge to choose “Porting parts of Numpy from C to Cython”. 
	This project is aimed at good legibility for the open software comunity as well as fast execution times, intend to balance both as development progress.
Intended Schedule:

	Given my intentions, I expect to use my current development method and all my knowledge. That includes continuous inspection with sonar and feedback from my mentor regarding code quality and logic. Can’t forget about perfomance since that’s what I’ve been investing in the last six months with code profiling for both my work and my graduation.
 Since my regular schedule is preety full I want to start coding soon and validate my theories, so I can deal with the real work as fast as possible, avoiding lack of time at the end of the summer. I believe mentor feedback will be crucial to me, even if not very much, at least constant feedback will be the key.
	My daily schedule will be around 4 hours a day, everyday, during working days and 8 at weekends.
	




Background preparation:

	March 27 - April 27:
		March 27 - April 3:
		- Development enviroment setup
		April 3 - April 10:
		- Current Numpy’s documentation analysis, getting to know the documentation processes
		April 10 - April 17:
		- Getting in touch with mentors, getting to know Numpy’s development processes
		April 17 - April 27:
		- Investigation about ways to unify .c and .pyx function calling, find ways to integrate this funcionality in the existing public API for Numpy 
Community Bounding:
	April 27 - May 25:
		April 27 - May 5:
		- My sister’s wedding, gotta catch a plane! I will be unavailable at this week
		May 5 - May 12:
		- Validation of previous analysis (trial and error), documentation of results and feedback from mentor.  Choose some specific core code in C which we must try to port
		May 12 - May 19:
		- Definition of Done (DoD) of the concept must be clearly defined and documented
		May 19 - May 25:
		- Coding week, preparation to start the real work

Student Coding:
	May 25 - August 24:
		May 25 - June 1:
		- Some “hacky proof-of-concept system” is expected to exist at this point, then proceed with mentor input. List ideas on how to attack the big picture
		- Getting feedback from mentor, then straight coding week
		June 1 - June 8:
		- Checking current direction with DoD, feedback from mentor
		June 8 - June 15
		- Run profiler on current code, check for hot code and bottlenecks, then optimize,  document beta public API documentation  
		June 15 - June 22:
		- Proof of Concept API must be done at this point 
		June 22 - June 29:
		- Get feedback from mentor, at this point, based on the developed POC, we must decide what else are we going to implement 
		June 29 - July 6
		- Profile all functions for hot spots, optimize 
		July 6 - July 13:
		- Document actual API, collect data for perfomance standards
		July 13 - July 20:
		- Straight coding week, optimization
		July 20 - July 27:
		- Feedback from mentor regarding DoD and final value delivery for Numpy, define realistic final objectives and deadlines for the next 3 weeks, track time spent on tasks until so far
		July 27 - August 3:
		- Straight coding week
		August 3 - August 10:
- Straight coding week
		August 10 - August 17:
		- Final validation with mentor, documentation
		August 17 - August 24:
		- Final adjusts, doing anything that needs to be finalized, delivery!

Off season:
	August 24 - February 9
		Enjoy ultimate glory! Get feedback from mentor and community, document ideas. Drink lots of whiskey and prepare for next year.

