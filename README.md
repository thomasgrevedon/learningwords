# learningwords
Mobile application to practice and learn words in context 
Users can paste sentences of full text where there is or are words that they would like to learn in context. Then the user just need to select which words, he would like to review/learn.  
Features will involve: 
 * possibilities to review words with blank space within the text
 * offering possibilities to help user find the word (giving help options)
 * User could get points on how many words he succeded to find and depending if he used the help option. There could be a ranking.
 * There could be a battle bettween user on some texts. 
 
# Technical stack

Front: 
 * Ionic
 
Back: 
 * Java - Spring Boot
 
BDD: 
 * to be determined but deployed with docker image
 
Tools:
 * Creating a CICD for new developments and fixes. 
 * Configuring ELK stack to track what is happening in the app
 * Monitoring the application with Grafana / Promotheus / cadvisor (to be choosen)

Tests:
 * Front tests should be implemented (testing library to be choosen)
 * jUnit can be used for the back

# Contributing

Tools needed to contribute on the project: 
- Code editor (if you are using VS Code, VS tasks will be used to ease deployment)
- NPM cli (could be gotten with installing nodejs)
- Java 8 (JDK)
- Docker (for windows users, use docker quickstart terminal)

Collaborating on git: 
There is a master branch for the production environment. 
There is a develop branch from where each new branch should be coming from. Each feature or fix needs a new branch. 
All branches should not have capital letter and should start with either feat/ or fix/. Then a minimal description of the feature is required for the title of the branch. 


