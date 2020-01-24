Welcome to my site. Here you will find console commands for the chrome dino game which you get when you are offline. You can also find this by typing chrome://dino in your browser


Speed = Runner.instance_.setSpeed(1000)

Immortality = Step 1) var original = Runner.prototype.gameOver     Step 2) Runner.prototype.gameOver = function(){}
#note: to get a valid score you must use the stop immortallity command beneath.

Stop immortallity = Runner.prototype.gameOver = original

Jump height = Runner.instance_.tRex.setJumpVelocity(10)

Distance set = Runner.instance_.distanceRan = 12345 / Runner.instance_.distanceMeter.config.COEFFICIENT

full colour version: #Note: instructions coming soon

https://raw.githubusercontent.com/thingy937/thingy937.github.io/master/beta6.png

<div class="onoffswitch">
    <input type="checkbox" name="onoffswitch" class="onoffswitch-checkbox" id="myonoffswitch" checked>
    <label class="onoffswitch-label" for="myonoffswitch">
        <span class="onoffswitch-inner"></span>
        <span class="onoffswitch-switch"></span>
    </label>
</div>


<p>:</p>
<!-- #######  DON'T GO LOOKING WHERE YOUR NOT MEANT TO. #########-->
<h1 style="color: #5e9ca0; text-align: center;"><span style="color: #000000;"><strong><span style="text-decoration: underline;">Welcome</span></strong></span></h1>
<p><span style="color: #000000;"><strong><span style="text-decoration: underline;"><span style="color: #ff0000; text-decoration: underline;">This is work in progress and images to help will come soon.</span></span></strong></span></p>
<h2 style="color: #2e6c80; text-align: center;"><span style="color: #000000;"><strong><span style="text-decoration: underline;">Hacking the dino game.</span></strong></span></h2>
<p style="text-align: center;">Hacking the chrome dino game is actually surprisingly easy once you know what code to put in.</p>
<p style="text-align: center;">To find the dino game you either need to have lost an internet connection or of gone to chrome://dino (I recommend the second option by far). Once on the page you can right click anywhere on the page or press F12 to bring up the inspect element page. Once there you select the console tab at the top of the page. In this is where we are going to input our code to hack the game. You will find the code beneath.</p>
<p style="text-align: center;"><span style="text-decoration: underline;"><span style="color: #ff0000; text-decoration: underline;">You can change the value in the brackets to fine tune the settings. </span></span></p>
<p style="text-align: center;"><span style="text-decoration: underline;"><span style="color: #ff0000; text-decoration: underline;">(10 is the original value)</span></span></p>
<p>&nbsp;To change the speed copy and paste this in:&nbsp; &nbsp;Runner.instance_.setSpeed(1000)</p>
<p style="text-align: center;">To change the jump height copy and paste this in:Jump height = Runner.instance_.tRex.setJumpVelocity(10)</p>
<p style="text-align: center;">To set the game to a particular score copy and paste this in:&nbsp;Runner.instance_.distanceRan = (12345) / Runner.instance_.distanceMeter.config.COEFFICIENT]</p>
<p style="text-align: center;">Becoming immortal requires 2 steps if you want to be able to switch back to being mortal afterwards to set your score. Step 1:&nbsp;var original = Runner.prototype.gameOver&nbsp; &nbsp;(This stores the original code in another variable for switching back to later.)&nbsp; &nbsp;</p>
<p style="text-align: center;">Step 2:&nbsp;Runner.prototype.gameOver = function(){} This removes functionality from the collision mechanic.</p>
<p style="text-align: center;">Removing the immortality to set the score is more simple:&nbsp;Runner.prototype.gameOver = original</p>
<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;"><span style="text-decoration: underline;"><strong>Custom graphics</strong></span></p>
<p style="text-align: center;">My custom graphics for the game aren't quite complete yet, but basically inputting this image into the game code will put the game into full colour which I prepared myself. (I will also in the future&nbsp;</p>
<p style="text-align: center;">&nbsp;</p>
<p>&nbsp;</p>
<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;"><strong>&nbsp;</strong></p>
