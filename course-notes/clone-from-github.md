# Cloning a project from github To Android Studio

## Cloning to you machine

- Use this method if you wish to own the code push your code to your own repo


1. Copy the path from the repo

2. At the command line make sure you are in the directory that you wish the code to be saved in

`$ git clone [paste path here]`

3. `$ git status`

4. `$ git add [local dirctory name you have just cloned] `

5. `$ git commit -m "initial commit"`

6. `$ git push origin master`

7. In android studio select `open existing project`

8. Find file and select ok or open.

9. Follow steps 7 to 14 below to set up the project

## Cloning directly into android studio

1. In the repo you wish to clone click the green button and copy the path.

2. Open Android Studio

3. On the welcome screen select `get from version control`

4. Paste the path into the top box

5. Check you are saving it to the location you require locally.

6. Click `clone`

7. Open `lib` -> `main.dart`

8. You may see am error regarding dart configuration:-

9. `tools` -> `flutter` -> `pub get`

10. Set SDK for Flutter

`/home/rosedm/snap/flutter/common/flutter`

11. Apply and OK

12. You should now see an option to get dependancies

13. Use `AVD manager` to add your device

14. Run from cold to test the code

