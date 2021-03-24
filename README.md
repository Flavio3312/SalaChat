# SalaChat
Sala de chat responsive


To check the operation you have to open a port with the local IP on your router since that way you will be able to use it from all your devices.
You can also upload it to your server and layout it to your liking to use it over the internet by changing your local IP for a public one or the host data

Modify this code in main.js
var socket =io.connect('HTTP://YOUR IP AND :PORT',{'forceNew':true});
