VM Name: dev-onboarding-dtr
Username: Demetrius
Password: Rimabros98 for Settings

1: Update your local main branch
 git checkout main
 git pull origin main

2: Create and switch to your new feature branch
Use a naming convention like 'feature/your-name/task-description'.
 git checkout -b feature/name/short-description

3: Make your code changes and stage them
Verify which files you changed before staging.
 git status
 git add <file-names>

4: Commit your changes locally
 git commit -m "Add descriptive action-oriented message"

5: Push your branch to the remote repository
 git push origin feature/name/short-description

6: Open a Pull Request (PR)
* Go to the repository webpage (e.g., GitHub / GitLab).
* Click "Compare & pull request".
* Select 'main' as the base branch.
* Select your feature branch as the compare branch.
* Add a description of your changes.
