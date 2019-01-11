
# Telegram home


## materials 
<ul>
  
<li>Raspberry pi – mini computer</li>
<li>Streaming camera or Raspberry pi camera</li>
<li>Servo motor – to control the lock</li>
<li>LED Lights – to show the lock condition (open/close)</li>
<li>Software(Language):</li>
<li>Python</li> 
<li>Telepot, Motion</li> 
</ul>


## Setting up Pi

### install Rasbian to Raspebbry pi with two options
<ul>
<li> by using monitor, keyboard and mouse. you can download noobs from <a href="https://www.raspberrypi.org/downloads/noobs/" target="_blank">raspberrypi.org </a>for free and install as usual </li>
  <a href="https://howchoo.com/g/ndy1zte2yjn/how-to-set-up-wifi-on-your-raspberry-pi-without-ethernet" target="_blank"><li> by using ssh with ip and wifi.</li></a>
</ul>


## Install Motion Software
To work with the Pi Camera you need a special version of Motion that supports MMAL cameras. The easiest way to install this is by downloading and installing a deb file as follows:

#### First get the deb file with the following command (if this doesn’t work then have a look for the correct release file on the Motion <a href="https://motion-project.github.io/motion_build.html">project GitHub</a>)
