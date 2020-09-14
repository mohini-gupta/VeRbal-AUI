# VeRbal - ConVRsational 
## Virtual Reality
### Advanced User Interface 

<img align="center"  width="80px" src="https://github.com/mohini-gupta/VeRbal-AUI/blob/master/web-folder/logo.JPG" />

*This project was created as a Advanced User Interface course in Politecnico Di Milano by a group of total 4 students.*  

VeRbal helps children learn language skills with fun. In a Virtual Reality environment, children have to match objects to the sentences they listen to by gazing at the objects. The text is also visible to the children. By moving their head, children will try to select the right object. This way, VeRbal transforms the already existing sentence-image matching therapy from a "boring" 2D paper exercise into an interactive and encouraging 3D experience. 

For the VR game we used the free program “Unity” with the addition of the Google VR SDK [6] and the Android Studio [7]. 

VeRbal is divided into two game modes: 
- a training mode which tells a sequential cheerful horse story and corrects wrong choices. 
- a test mode, where after listening to the sentence and selecting the right choice, the total feedback is send to the website.  

Website is created to monitor the children's progress. As of now, anyone can monitor whatever is viewed in the VR game. It is created using basic HTML and CSS. The backend is done using Node.js. The interaction between the Unity VR game and the website happens by capturing a screenshot every second and sending it using the Websocket connection in C# and Node.js.

Following are the screenshots of the application:

### 1. Test mode
<img width="80px" src="https://github.com/mohini-gupta/VeRbal-AUI/blob/master/web-folder/VeRbal_1.PNG" />

 ### 2. Training mode 
 (screenshot from the VR applicaton)
 <img width="80px" src="https://github.com/mohini-gupta/VeRbal-AUI/blob/master/web-folder/VeRbal_3.PNG" />
 
 ### 3. Website
 <img width="80px" src="https://github.com/mohini-gupta/VeRbal-AUI/blob/master/web-folder/VeRbal_4.PNG" />
 
 
 ## How to use?
 Download the Verbal.APK from the <a href="https://www.linkedin.com/in/mohini-gupta485/">APK</a> folder. Use a VR headset and start playing with the game!  
