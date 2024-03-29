<img width="961" alt="image" src="https://github.com/LakshitLuhadia/PixelPerfectAI/assets/148317491/28758f83-024a-47c1-98fb-444e18c6dcf5">

Inspiration

"As we sifted through countless photos on our phones, fatigue setting in, inspiration sparked. Fueled by the desire for quick and effortless Instagram-worthy posts, our idea was born....PixelPerfect"

What it does

It is an image sorting script that efficiently employs advanced analysis to sort images (we used cases such as very blurry pictures and very high quality pictures to set as the base standard) and that returns images it deems are the highest quality amongst each other

How we built it

We skillfully wielded the vast arrays of OpenCV and dlib to craft our facial recognition and image quality assessment feature. We set up an AWS EC2 server creating an Instance, allowing remote access and setting up SSH, continuously expanding our knowledge of AWS services and troubleshooting common issues as well as optimizing our server for efficiency.

Accomplishments that we're proud of

We successfully integrated it into an AWS EC2 web server, incorporating facial recognition to identify faces, smiles, and assess image quality, including blurry pictures. -Used Grayscale filter on each RGB to which filtered out irrelevant information to our analysis of intensity of each RGB thus making it uniform for us to apply the Laplacian Filter -Used the Laplacian filter for edge detection and provides a measure of the rate of change of intensity/brightness in an image. This determined if an image was blurry or not.
