# IoT-Hobby-Projects with the Beaglebone

## Getting Started

Head to [this page](http://beagleboard.org/static/beaglebone/latest/README.htm) to get the drivers installed on your machine.  This will take 5-10 minutes.

>**Note:** You only need to complete Step 1 (plug in to USB) and Step 2 (install drivers) on this page.

Once the drivers are installed, you should be able to SSH into your Beaglebone.

### Details:

- IP Address: 192.168.7.2
- Username: root
- Password: *instructor will tell you*

## Turning the Light on

Head to [this page](http://www.circuidipity.com/bbb-led.html) for a quick tutorial to get you set up with your "IoT Hello World" by blinking lights!

## Taking the Temperature

Head to [this page](http://www.bonebrews.com/temperature-monitoring-with-the-ds18b20-on-a-beaglebone-black/z) for a tutorial to take the temperature with a digital thermometer.

## Making a Web Server

Just like with any other computer, you can start a web server by creating an `index.html` file and running `python -m SimpleHTTPServer`.  Make sure python is installed first.

### Is the Button Pressed?

Now that you can turn a light on (output), let's try playing with the other side (input).  Head to [this page](https://learn.adafruit.com/connecting-a-push-button-to-beaglebone-black/overview) for a tutorial on this.

## Turning a Power Strip on

Using `crontab`, and a [solid state relay](https://en.wikipedia.org/wiki/Solid-state_relay), you can time a whole power strip of devices to turn off or on at certain times.  This can help cut down on your energy bills.

I used this functionality to create a small garden of lettuce and radishes in my basement apartment bedroom (turning lights on at 7 every morning, and off at 10 ever night).

## Being an Awesome Boyfriend/Girlfriend

For someone's birthday, you could create a mail server that sends a cute quote to their email everytime they press a button.  It can also send an email to you to let you know they miss you.

## Using Johnny5

Head to [this page](http://johnny-five.io/) to redo your hello-world, but this time **with javascript**.  Scroll down to `Hello World!` and click the `Beaglebone` link to see how to write the code (on the left) and how to set up the hardware (on the right).

## Other Ideas

What would you like to do with Internet of Things?  After the break, pitch your idea, and we'll assemble teams.
