# VR Game

I created a game in Unreal Engine 4.24 that uses the mouse and keyboard to simulate VR interactions. 
Pick up golden balls. Throw and catch them if it is within range. Then throw them at targets. If the ball hits the target, the target will spin with glee!
Use the mouse to move the hand around the character. The hand is maintained at a fixed arms length away from the camera. Use the W,A,S,D keys to look towards different directions. Pick up and release the ball using the left mouse button.  

There is a mild gravitational force that pulls the ball towards the target based on the distance between the target and where the camera is looking. The pull radii is largest when the target is at the center of where the camera is looking. 
It decreases as the camera is looking away from the target. 
Only the closest target from the ball will exert its pull force on the ball, so only one force from one target will act at a time.
Even with this aim assistance help, it's still quite challenging!

See a demo here:
<figure class="video_container">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/hQnLVMPqFMQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</figure>

Play it on your windows 64 machine [here](https://www.dropbox.com/s/751rkrbe2m2bics/SDG.zip?dl=0 "Throwing Balls Game")
