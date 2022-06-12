# **A Voting System! 🗳️**
##### This is the manual file/explanations for this voting system!
##### Voting System - curated by 21900842 Abigail Yong 

------------------------------------------------------------------------------------------------------

## Description and use

Use: To hold mini elections/voting system for any clubs, organizations, ministries and communites.\
This is done by using C programming, and it requires an id for both voters and voter committees. \
My contribution to this project is creating this voting system. \
I did so after observing different elective committees in Handong struggle to have a efficient and quick voting system. \
With this system, you can vote and check results easily.


For raspberry pi, follow the steps below:
1. Log into a pi terminal on your Raspberry Pi
2. $ sudo systemctl stop nginx
3. $ sudo apt-get install apache2-y
4. $ start service apache2 restart
5. $ git clone https://github.com/aeibby/VotingSystem.git
6. $ sudo mv VotingSystem /var/www/html/
7. Download necessary files and run normally on any terminal/editor
8. Run 'VotingMain.c' after compiling using _$ gcc VotingMain.c_ & _./a.exe_

------------------------------------------------------------------------------------------------------

## Explanation on how to use:

⚠️ To login as an Admin \
Username: Admin \
Password: 12345

☑️ _Admin rights (Voter committees):_
1. Hold a New Voting Round
2. Continue Previous Voting Round
3. Show Results
4. Exit/logout from Admin panel

☑️ _Student rights (Voters):_
1. Entering student ID (with a format)
2. Choosing votes
3. Exit/logout

☑️ _When creating a voting round done in the Admin panel:_
1. Enter year (eg: 2022)
2. Enter branch code in 5 letters (eg: ossLF)
3. Enter voter population (eg: 100)
4. Enter the number of candidates (eg: 2)
5. Enter name of Candidates 1 (eg: sam)
6. Enter name of Candidates 2 (eg: will)

This will then create a file under the folder you currently have these files under.

To refrain from other inputs and fake votes, there is a format given to avoid such miscellaneous inputs.

When entering a student ID, follow this format: \
_year...branch code...voterid_ \
Examples of a student ID: \
2022ossLF00031 \
2022ossLF00045 \
2022ossLF00022 \
2022ossLF00098 \
Determine your last 2 digits by how which nth voter you are! :)


** The _voterid_ is the according to whichever number of voter you are in 5 digits. The maximum voter population is up to 10000. \
After that, as a student with a valid student ID, you will be able to input the choice of candidate by entering the number!

After voting, results will show as inputted with the voter turnout! 🥇

-----------------------------------------------------------------------------------------------------

## Questions 
https://youtu.be/30UVoBUAej0 \
This is the explanation of the Voting System! \
If you have any further questions, please do not hesitate to email me abby@handong.ac.kr :) \
I will try my best to solve your inquiries! \
Thank you for using this voting system! 🥰



