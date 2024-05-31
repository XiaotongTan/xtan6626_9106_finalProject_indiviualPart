# xtan6626_9106_finalProject_indiviualPart
## Chosen Part: Audio

### Project Interaction
- Click the 'Play/Pause' button to start or pause the music. Upon playing, watch as the squares labeled redSquare and blueSquare dynamically bounce to the beat of the music. At the same time, all graphical elements except the yellowLines and yellowPart will change colors in synchronization with the music's volume and pitch.

- Dynamic Squares: redSquare and blueSquare adjust their vertical and horizontal positions respectively, according to the music’s volume. This movement is achieved using the map() function to scale the amplitude of the audio input to a usable range for visual modifications.
  - Exotic technology map function here: According to the [guidance on JavaScript Tutorial](https://www.javascripttutorial.net/javascript-array-map/), the map() function is designed to transform each element in an array, applying a specified operation and returning a new array with the transformed elements. Arrow functions make the code more concise. In this project,  I used the map() function to dynamically adjust the position based on the amplitude of the audio input.

- Dynamic Color:  color parameter (RGB) of the graphical elements transition based on the audio's amplitude. As the music intensifies, so does the brightness and intensity of these graphical elements,creating a synchronization between sound and visuals.

### Indiviual Features
Compared to other group projects, my code focuses on integrating both vertical and horizontal movements synchronized with color changes, providing a multi response to audio inputs. 
