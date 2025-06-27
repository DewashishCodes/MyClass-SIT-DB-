Hi contributor, its so nice to see you actively contribute!
Let me walk through the format we want you to create the database for MyClass@SIT:-

The Hierarchy:<br>
Freshman/Sophomore -> Branch -> Batch(eg:A2,B3,etc) -> Day of the week -> Timeslot -> Subject,Location,Faculty

Please make sure to make changes to the database in exactly this hierarchial order. We have already sorted things out till the branch hierarchy level for you.

The Syntax:
``` 
"Monday": {
          "08:45-09:45": { "subject": "FEEEL", "location": "BEEE LAB 3rd floor", "faculty": "Sangeeta Pant" },
          "09:45-10:45": { "subject": "FEEEL", "location": "BEEE LAB 3rd floor", "faculty": "Sangeeta Pant" },
          "10:45-11:45": { "subject": "FEEE", "location": "C108", "faculty": "Pritesh Shah" },
          "11:45-12:45": { "subject": "Chemistry", "location": "C108", "faculty": "Shekhar Bhame" },
          "12:45-13:40": { "subject": "Lunch", "location": "-", "faculty": "-" },
          "13:40-14:35": { "subject": "PPS", "location": "B106", "faculty": "Vipin Tiwari" },
          "14:35-15:30": { "subject": "PPSL", "location": "CAD Lab 1st floor", "faculty": "Vipin Tiwari" },
          "15:30-16:25": { "subject": "PPSL", "location": "CAD Lab 1st floor", "faculty": "Vipin Tiwari" }
        },
```
This is the syntax you have to follow, make sure to close all your curly brackets so that there is no error in your code.

The Procedure:
1. Fork the Repository
Go to this repo:
👉 https://github.com/DewashishCodes/MyClass-SIT-DB-

Click the “Fork” button on the top right.
This creates your personal copy of the project.

2. Clone Your Forked Repository
Open your terminal and run:
```
git clone https://github.com/YOUR_USERNAME/MyClass-SIT-DB-.git
```
🔁 Replace YOUR_USERNAME with your actual GitHub username.

Then move into the project folder:
```
cd MyClass-SIT-DB-
```
If you’re not in the folder, run:
```
cd path/to/MyClass-SIT-DB-
```

3. Create a New Branch for Your Work
Always do contributions on a separate branch, not on main:
```
git checkout -b data-entry-YOUR_NAME-June27
```

4. Make your changes 

5. Stage and commit changes
```
git add .
git commit -m "Added data of XYZ Branch ABC batch"
```

6. Push your branch to github
```
git push origin data-entry-YOUR_NAME-June27
```

7. Create a pull request (PR)
    Go to your fork on GitHub.
    You’ll see a “Compare & pull request” button — click it. 

    Confirm that:

    base repo = DewashishCodes/MyClass-SIT-DB-<br>
    head repo = YOUR_USERNAME/MyClass-SIT-DB-

    Add a meaningful title and description.
    Click “Create pull request”.

8. Stay Updated with Main Repository
```
# Only once: Add the main repo as upstream
git remote add upstream https://github.com/DewashishCodes/MyClass-SIT-DB-.git

# Pull latest changes
git checkout main
git pull upstream main
git push origin main
```


