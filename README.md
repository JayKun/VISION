<h1>Project VISION</h1>

<h2>Description </h2>

<p>Using the Intel Edison, a camera, a speaker, Node js and Google's Vision API, IBM Watson Text to Speech, my team and I were able to create a visual aid device that allows the visually impaired to navigate around the obstacles. The basic idea is to have a button that once pressed triggers the camera to take a photo of the surrounding, pipe the image using a web server hosted on the Intel Edison using Node js. Finally, the image is processed using Google's VISION API to obtain a JSON file containing the description of 
object in the image ;the JSON file is converted into a text file and converted into a .wav file using the IBM Watson Text to Speech API.
</p>

<h2>Code Example</h2>

<p> The program can be easily run just by moving the image to be tested into the same file directory as "index.js" and renaming it  "img.jpg". Executing the program is simple as "node index.js". The program would return labels describing the image to the console.
</p>

