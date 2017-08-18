# "The Samsung Internet Story: Why Samsung Made A Web Browser" - Coldfront 2017

My slides for [Coldfront 2017](https://2017.coldfront.co/). 

## To view the slides

(In progress!) They're at: https://poshaughnessy.github.io/the-samsung-internet-story-coldfront-2017/

Use arrow keys or the arrow buttons to move left/right.


## To run locally

```
npm install
npm start
```


## To use the Bluetooth remote control

Load up the Remote page on a Web Bluetooth supporting browser, e.g. Chrome for Android, on the device you want to use 
as a presentation remote: http://localhost:9000/remote.html

Press Connect and (as long as you have the Node server running and Bluetooth enabled on both devices) you should see
a device option called 'Remote Receiver'. Select that, wait til it says Connected, then you can use the buttons to send 
commands!


## To deploy (for Peter's reference)

```
npm run deploy
```
