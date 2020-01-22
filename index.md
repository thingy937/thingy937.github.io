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


.onoffswitch {
    position: relative; width: 119px;
    -webkit-user-select:none; -moz-user-select:none; -ms-user-select: none;
}
.onoffswitch-checkbox {
    display: none;
}
.onoffswitch-label {
    display: block; overflow: hidden; cursor: pointer;
    border: 2px solid #000000; border-radius: 50px;
}
.onoffswitch-inner {
    display: block; width: 200%; margin-left: -100%;
    transition: margin 0.3s ease-in 0s;
}
.onoffswitch-inner:before, .onoffswitch-inner:after {
    display: block; float: left; width: 50%; height: 41px; padding: 0; line-height: 41px;
    font-size: 40px; color: white; font-family: Trebuchet, Arial, sans-serif; font-weight: bold;
    box-sizing: border-box;
}
.onoffswitch-inner:before {
    content: "on";
    padding-left: 10px;
    background-color: #4D4D4D; color: #000000;
}
.onoffswitch-inner:after {
    content: "off";
    padding-right: 10px;
    background-color: #4D4D4D; color: #000000;
    text-align: right;
}
.onoffswitch-switch {
    display: block; width: 20px; margin: 10.5px;
    background: #ED1313;
    position: absolute; top: 0; bottom: 0;
    right: 74px;
    border: 2px solid #000000; border-radius: 50px;
    transition: all 0.3s ease-in 0s; 
}
.onoffswitch-checkbox:checked + .onoffswitch-label .onoffswitch-inner {
    margin-left: 0;
}
.onoffswitch-checkbox:checked + .onoffswitch-label .onoffswitch-switch {
    right: 0px; 
    background-color: #26CC50; 
}
