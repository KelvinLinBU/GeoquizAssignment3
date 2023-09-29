# GeoquizAssignment3
Geoquiz assignment 3. This is for CS501

Problem Three: In the android manifest, to fix the rotation/cheating issue, added line android:configChanges="orientation|screenSize" to the cheat activity. This fixed the issue. The reason for the issue in the first place was that every time the screen rotated, the cheat activity was destroyed and a new on was created. The code added saves it. 

Fixed Problem 4. Adjusted code to update quizViewModel.isCheater to false every time the next button is clicked. This fixes the issue.
