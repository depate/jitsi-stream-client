# Jitsi Client for Streaming

This is a small HTML/Javascript Client for Jitsi. With this client you can join any Jitsi Room and the Client shows the participants on a fixed window on the screen. The client can show a maximum of 9 Videos. The positions on the Screen are fixed and mapped by the username of the participants.

With this design it is possible to capture the Screen with OBS and crop the different Video feeds of your Users seperately.
Its best to open the Browser on a second Monitor. (Use Chrome or Chromium)

The Jitsi Server can be changed in the script.js file. The default Server is "meet.theater.digital".

Furthermore you can Control the Volume of each Participant via a Slider and even via Midi Controller. (Korg nanoKontrol2)

Since this client will join the Jitsi Meeting, its name is "Streamer". It has no Video for the other users.


## User mapping

Below the Video Placeholdes there a Input Boxes for the Usernames. You have to enter the exact name of the participant into the box and hit the reload Button to apply.

On the very bottom of the page is a List with all current users in the Meeting Room.

Ask your users that they give themself a uniqe username. Best are simple names without blanks and any special symbols. Please avoid duplicate names.

