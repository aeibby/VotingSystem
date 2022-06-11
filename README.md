# ** This is the manual file for this Mini Voting System! **
## Voting System - curated by 21900842 Abigail Yong 

Use: To hold mini elections/voting system for any clubs, organizations, ministries and communites.
This is done by using C programming, and it requires an id for both voters and voter committees. :star_struck:

**TO RUN THIS CODE, YOU NEED TO DOWNLOAD BOTH 'Voting.h' and 'VotingMain.c' AND RUN 'VotingMain.c' AFTER COMPILATION ON AN EDITOR.**

:warning:	> If you will be holding this voting, username: Admin, password: 12345 :warning:	

Admin rights (Voter committees): 
1. Hold a New Voting Round
2. Continue Previous Voting Round
3. Delete Illegal Votes
4. Ban User IDs
5. Show Results
6. Exit/logout from Admin panel

Student rights (Voters):
1. Entering student ID (with a format)
2. Choosing votes
3. Exit/logout

When creating a voting round done in the Admin panel:
1. Enter year (eg: 2022)
2. Enter branch code in 5 letters (eg: ossLF)
3. Enter voter population (eg: 100)
4. Enter the number of candidates (eg: 2)
5. Enter name of Candidates 1 (eg: sam)
6. Enter name of Candidates 2 (eg: will)

This will then create a file under the folder you currently have these files under.

To refrain from other inputs and fake votes, there is a format given to avoid such miscellaneous inputs.

When entering a student ID, follow this format:
year...branch code...voterid
Examples of a student ID: 
2022ossLF00031
2022ossLF00045 
2022ossLF00029 
2022ossLF00098

** The voterid is the according to whichever number of voter you are in 5 digits. The maximum voter population is up to 10000.

After that, as a student with a valid student ID, you will be able to input the choice of candidate by entering the number!


