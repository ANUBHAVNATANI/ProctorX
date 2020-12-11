### Youtube Video -- https://www.youtube.com/watch?v=7Q_lfauqAsc&feature=emb_title&ab_channel=WHITEKNIGHT

Online cheating detection using AI and React Js

Online-Proctoring-System
Online Courses greatly expand the reach of todays educational institutions, both by provid- ing a wider range of educational resources to enrolled students and by making educational resources available to persons who cannot access a campus due to location or schedule con- straints. Exams are a critical component of any educational program, and online educational programs are no exception. In any exam, there is a possibility of cheating, and therefore its detection and prevention is important. According to a survey about 29% of the students admitted cheating. When exams are administered in a conventional and proctored classroom environment, the students are mon- itored by a human proctor throughout the exam. The overall goal of this system is to maintain academic integrity of exams, by providing real-time proctoring to detect the ma- jority of cheating behaviors of the test taker. To achieve such goals, audio-visual observations about the test takers are required to be able to detect any cheat behavior. Our system monitors some signs in the room where the test taker resides, using two cameras and a microphone. The first camera is the webcam of laptop itself. The other camera can be a smartphone camera. The microphone is the built in microphone of laptop, So no extra hardware is required on behalf of student to give the exam. Using such sensors, we propose to detect the following cheat behaviors:

cheat from text books/notes/papers,
using a phone to call a friend,
asking a friend in the test room, and
having another person take the exam other than the test take
This project has the following features:

Proposes an automated online exam proctoring system with visual and audio sensors for the purpose of detecting cheating.
Collects a multimedia dataset of images of student from both the cameras during exams and also the dataset of anomalous behaviours of student.

# Tech Stack
**Tensorflowjs** : all the detection for any violation is done on the client side and hence we are easily able to analyse the movements and activities of the candidates

**ReactJS & MaterialUI**: We have used it to create a very simple and easy to use UI of the application

**Note** : We have built the UI not for what the candidate would see, but to capture all the activities of the candidate. UI can be changed anytime for a candidate to give the exam

**Web Speech API** : We have done tracking of the candidate’s voice while he is giving the test, so he is not talking to someone

# Progress and Features

Team : beta19

A prototype to proctor candidates on online tests or examinations
Product : proctor-x

Assumptions : 
webcam/mic access
We are representing how we are able to track all the violations by the user. Instead of closing the test platform, we are logging all the unfair activities as logs

**Features**
1. Full Screen Mode [Done] <br>
Violation as soon as full screen mode is closed click on this icon to turn back to full screen mode <br>
2. Tab Switching [Done]<br>
3. Detect the tab switch so that no user is able view/cheat from any other tab on the browser<br>
4. Window Switching [Done]<br>
5. You cannot minimise the current browser window to cheat from some other application<br>
Ctrl + S, Ctrl+C, Ctrl+V not allowed [Done]<br>
6. You cannot copy or paste the answers<br>
7. You cannot save the examination page<br>
8. No system clipboard access[Done]<br>
9. Since you can’t use the copy and paste function, you have no access to the system clipboard<br>
10. No screenshots [Done]<br>
11. Screenshots are not controlled by web browser but by the OS, hence user can click the screenshots but can’t access them neither on the same device nor any other connected ones<br>
12. For same device : You can’t switch tabs/window<br>
13. For connected device : You can’t look away from the current exam session, which is ensured by camera tracking your eye movement<br>
14. Violation Logging [Done]<br>
15. Instead of closing the test platform, we are logging all the unfair activities as logs<br>
16. Voice Recognition	 We would keep a check that the candidate mustn’t speak [Done]<br>
17. [AN]Automatic question answer generation [Second Thought]	<br>
18. [AN]Eye movement using open cv js	[Done]<br>
19. Interruption limitation [Done]	<br>									
20. [AN]Machine learning model - phone recognition,copy recognition etc.  tensorflow js [Done]<br>
21. [AN]Multiple cameras [Done]<br>

**[AN] : Anubhav Natani


