<p>&nbsp;</p>
<!-- #######  DON'T GO LOOKING WHERE YOUR NOT MEANT TO. #########-->
<h1 style="color: #5e9ca0; text-align: center;"><span style="color: #993366; background-color: #ffffff;"><strong><span style="text-decoration: underline;">Welcome</span></strong></span></h1>
<p><span style="color: #000000;"><strong><span style="text-decoration: underline;"><span style="color: #ff0000; text-decoration: underline;">This is work in progress.</span></span></strong></span></p>
<h2 style="color: #2e6c80; text-align: center;"><span style="color: #0000ff;"><strong><span style="text-decoration: underline;">Hacking the dino game.</span></strong></span></h2>
<p style="text-align: center;">Hacking the chrome dino game is actually surprisingly easy once you know what code to put in.</p>
<p style="text-align: center;">To find the dino game you either need to have lost an internet connection or of gone to chrome://dino (I recommend the second option by far). Once on the page you can right click anywhere on the page or press F12 to bring up the inspect element page. Once there you select the console tab at the top of the page. In this is where we are going to input our code to hack the game. You will find the code beneath.</p>
<p style="text-align: center;"><span style="text-decoration: underline;"><span style="color: #ff0000; text-decoration: underline;">You can change the value in the brackets to fine tune the settings. </span></span></p>
<p style="text-align: center;"><span style="text-decoration: underline;"><span style="color: #ff0000; text-decoration: underline;">(10 is the original value)</span></span></p>
<p>&nbsp;To change the speed copy and paste this in:&nbsp; &nbsp;Runner.instance_.setSpeed(10)</p>
<p style="text-align: center;">To change the jump height copy and paste this in:Jump height = Runner.instance_.tRex.setJumpVelocity(10)</p>
<p style="text-align: center;">To set the game to a particular score copy and paste this in:&nbsp;Runner.instance_.distanceRan = (1000) / Runner.instance_.distanceMeter.config.COEFFICIENT]</p>
<p style="text-align: center;">Becoming immortal requires 2 steps if you want to be able to switch back to being mortal afterwards to set your score. Step 1:&nbsp;var rgnl = Runner.prototype.gameOver&nbsp; &nbsp;(This stores the original code in another variable for switching back to later.)&nbsp; &nbsp;</p>
<p style="text-align: center;">Step 2:&nbsp;Runner.prototype.gameOver = function(){} This removes functionality from the collision mechanic.</p>
<p style="text-align: center;">Removing the immortality to set the score is more simple:&nbsp;Runner.prototype.gameOver = rgnl</p>
<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;">&nbsp;</p>
<h2 style="text-align: center;"><span style="text-decoration: underline; color: #0000ff;"><strong>Custom Graphics.</strong></span></h2>
<p style="text-align: center;">My custom graphics for the game aren't quite complete yet, but basically inputting this image into the game code will put the game into full colour which I prepared myself. (I will also in the future add the base canvas of the game which you can edit with a full list of instructions to create your own custom graphics).</p>
<p style="text-align: center;">Here are the instuctions:</p>
<p style="text-align: left;">1) Right click the imgae below and select copy image address.</p>
<p style="text-align: left;"><img src="https://github.com/thingy937/dino-game-test-stuff/blob/master/DinoGameCustom.png?raw=true" /></p>
<p style="text-align: left;">&nbsp;2) Navigate back to the elements tab of the inspect element page.&nbsp;</p>
<p style="text-align: left;">3) When looking at the elements you will see a drop down named "offline-resources". Select this.</p>
<p style="text-align: left;">4) You will see two image id's. Right click the one labeled "offline-resources-1x" and select edit as html.</p>
<p style="text-align: left;">5) Now erase all of the bit circled in the image below (be careful not to get rid of the speech marks since it wont work if you do.)</p>
<p style="text-align: left;"><img src="https://raw.githubusercontent.com/thingy937/thingy937.github.io/master/dino%20game%20custonm%20graphics%20help%201.PNG" alt="" width="534" height="142" /></p>
<p style="text-align: left;">6) In the newly made space paste the image address that you copied earlier.</p>
<p style="text-align: left;">7) The last step is changing the background colour. Nearer to the bottom of the elements tab you will see this area which I have highlited in the picture below. All you need to do is click on the white box and find a blue that you want to use.</p>
<p style="text-align: left;"><img src="https://github.com/thingy937/thingy937.github.io/blob/master/dino%20game%20custonm%20graphics%20help%202.PNG?raw=true" alt="" width="527" height="270" /></p>
<p style="text-align: left;">&nbsp;8) Well there isn't an eighth step because now it should all be done. If there is anything that went wrong you can watch the tutorial video which I will link below soon. To exit the inspect elements tab you can either press F12 or the cross in the top right corner.</p>
<p style="text-align: left;">&nbsp;</p>
<p style="text-align: left;">&nbsp;</p>
<p style="text-align: left;">This is the end of the turtorial. Thanks for reading since dependent on what use this gets i might make more tutorials in the future.</p>
<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;"><strong>&nbsp;</strong></p>

<a href="thingy937.github.io">Click here</a>
