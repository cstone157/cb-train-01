Introductory Training Project (CCS)

1. Description
  This is a simple introductory project intended to introduce members to git, docker, and the format that training projects will follow.
  
1a. Git
  Git is a code repository tool.  Imagine you are a member of a team writing a new piece of software, the team has 50 members.  How do you get the code?  How do you track changes to the code?  What do you do to ensure that changes you make don't delete the changes that other team members have made?
  Repository are a means of allowing a user to make changes to a coding project, identify changes made and by who, document the version history of the application/code, share with all of the other members of a team, and ensure that your changes don't delete your fellow team members code.
  A great place to lookup git commands are located at https://git-scm.com/docs/gittutorial.
  
1b. Docker
  Docker is a containerization tool.  Imagine you have been hired as a malware analyst, and you have a windows laptop to do your work, but you need to check an application that only runs on macOs.  How do you check this application?  How do you ensure that the thing you are checking doesn't infect your laptop?  
  What you do is you use a virtual machine, which is a piece of software that basically pretends to be a computer, that is isolated from the host computers OS, meaning that any malicious software on the VM (Virtual Machine) can affect the host computer.
  A containerization tool, is a VM with only the software necissary to run the application you want.  Say you need a database, rather than run a full VM or reconfigure your host machine, just use a containerized version of the database you need.
  
1c. Terminal/Command-line

2. Project Steps (Git)
2a.  First install git onto your development laptop (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), follow the steps on the site for your particular OS (Windows, macOs, Linux)
2b.  Install docker onto your development laptop (https://docs.docker.com/engine/install/), follow the steps on the site for your particular OS (Windows, macOs, Linux), ensure you also install docker-compose.yml
2c.  Clone (download) this project onto you development laptop.  You will first need to open a terminal and run the following command "$ git clone git@github.com:cstone157/cb-train-01.git", when you are cloning the project ensure you download it somewhere you will be able to find it.
2d.  Open the folder that the project was downloaded into.  The "$ ls" command lists all objects in a folder and the "$ cd <folder_name>" is the command to navigate into an folder and "$ cd .." navigates up a folder.
2e.  Create a branch in the project, the name of the new branch should be your "firstInitial.LastName" (no quotes) (https://git-scm.com/docs/git-branch), ensure that you switch to the new branch.

3. Project Steps (Docker)
3a.  First ensure that there are no docker containers running "$ docker ps -a", the "ps" shows containers, the "-a" shows all the containers even the ones not running
3.b  Run the command "$ docker-compose up -d" from the project folder, this will execute the "docker-compose.yml" located in your folder and run it in detached mode (the standard output from docker console will be directed to a log file, and if the console shuts down the container will keep running in the background).
3.c
3.d

4. Questions (Type your answers here)
4.a  

5. Submitting Your Project
5.a
