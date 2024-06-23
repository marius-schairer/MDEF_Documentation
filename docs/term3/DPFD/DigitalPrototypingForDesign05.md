
# Reflection
The 5th challenge was fun and gave me a deeper understanding of machine learning and showed that ai models are best at distinguishing strong contrasts and become inaccurate at the mean values. The tools provided helped to prototype and test our idea quickly.

## Steps

Grabbing Data from Phone using ZIG Sim
Through using the app on your phone we could grab a variety of data points and send them to the wekinator. We used GPS, and Z-axis acceleration. We trained the model on multipe peoples running/walking to diversify movements as much as possible. 

Training Model in Wekinator
While the data was being grabbed from the phone it was also being sent to the Wekinator application on the laptop which we could then train through saying while running a person is 1 and while walking they were 0.

<iframe width="560" height="315" src="https://www.youtube.com/embed/6_YGM4k_xKA?si=9rYpKRVPVYWf-CJz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


Sending data to Max8
Once the training was done in Wekinator, we connected the model to Max8 and used it to send either the signal 0 or 1. 

Converting received input to sound in Max8
Using the received signal we were able to create a easy flow of code in Max8 that either turned on 1 sound or another based on this signal.
The final output

Having 2 songs change based on movement
In the end we managed to create a model and code that allowed us to have one person run or walk and have this translated into a song. This was fun to see happen because it could have implications in the way people interact with their own movement and what it could bring to the realm of dancing/running or other sports. 


<iframe width="560" height="315" src="https://www.youtube.com/embed/gc8T83aijoU?si=7mm7LN3SLWmN6fir" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>