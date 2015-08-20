#Copying a repo on the Git desktop App:

1. Open git desktop app
2. Click '+' sign on the top left
3. Select the "Clone" option
4. Click on the repo you want to close
5. Click Clone <project name> at the bottom

#Commiting from the app onto Github:

1. Open the git desktop app
2. Select your repo on the left
3. Select which branch you want to commit to (at the top middle-left)
4. Move your progress to the dash-lined open circle
5. Add a title and description (near the bottom middle-left)
6. Click Commit to <branch name> at the bottom
7. Click Sync on the top right

#Request Pull requests from the app

1. Open the git desktop app
2. Select your repo on the left
3. Select the branch that you want to merge (at the top middle-left)
4. If the option appears, click "View Branch" underneath where you selected the branch
5. Click "Pull Request" on the top right 
6. In the new window on the right, select which branch you want to merge into
7. Add a title, and a description
8. Click Send

#Metadata in Unity
##.gitignore for metadata

1. Go to your master branch in the repo ONLINE
2. Click on the .gitignore file
3. Click the pencil icon to the right of the files name (near the top of the app)
4. Add the following lines to the bottom of the file:

Temp/

Library/

Obj/

*.csproj

*.unityproj

*.sln

*.user

*.userprefs

*.DS_store

4. Save

##Setting up Unity to work with Git

1. Open your project
2. Go to Edit>Project Settings>Editor
3. In the inspector, change Version Control Mode to "Visible Meta Files"
4. Change Asset Serialization Mode to Force Text
5. Save and close!


