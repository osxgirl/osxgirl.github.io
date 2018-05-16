---
layout: post
title:      "coding jewelbots!! //[❤️] 🍌🍓🍇🥝🍑🍉"
date:       2018-05-16 20:04:06 +0000
permalink:  coding_jewelbots
---


a [jewelbot](http://jewelbots.com) is a friendship bracelet that is programmed by using an IDE on your Mac or PC. the bracelet has a vibration device and 4 LEDs to operate. You can even link it to another bracelet and set alerts when the two are within range! There is a wonderful and supportive community for building friendships too.


<p><a href="https://imgur.com/blCeZB3"><img src="https://i.imgur.com/blCeZB3m.jpg" title="Jewbot Charm" /></a>
<a href="https://imgur.com/oOGN2Hw"><img src="https://i.imgur.com/oOGN2Hwm.jpg" title="Heather & Mackenzie" /></a>
<a href="https://imgur.com/wmfC22W"><img src="https://i.imgur.com/wmfC22Wm.jpg" title="Jewbot & Macintosh" /></a>
<a href="https://imgur.com/ae2jKlH"><img src="https://i.imgur.com/ae2jKlHm.jpg" title="Mackenzie's Jewbot" /></a></p>

🍌🍓🍇🥝🍑🍉

Here is code I found from one of the Ambassadors of @jewelbots - Ellie Galloway
It’s called Fruit Lights :

`

LED led;
Timer timer;
Animation animation;

void setup() {
// put your setup code here, to run once:

}

void loop() {
// put your main code here, to run repeatedly:

}

void button_press (void) {
// first we have a banana
led.setLight(0, 255, 255, 0);
led.setLight(1, 255, 255, 0);
led.setLight(2, 255, 255, 0);
timer.pause(3000);
led.turn_off_all();
timer.pause(100);
// and now a strawberry
led.turn_on_single(NW, RED);
led.turn_on_single(SW, RED);
led.turn_on_single(NE, RED);
led.setLight(3, 0, 204, 0);
timer.pause(3000);
led.turn_off_all();
timer.pause(100);
// how about a blueberry
led.turn_on_single(NW, BLUE);
led.turn_on_single(SE, BLUE);
led.turn_on_single(NE, MAGENTA);
led.turn_on_single(SW, MAGENTA);
timer.pause(3000);
led.turn_off_all();
timer.pause(100);
// and now a fig that has been cut in half
led.setLight(1, 25, 0, 51);
led.setLight(0, 25, 0, 51);
led.turn_on_single(SE, RED);
led.turn_on_single(NE, RED);
timer.pause(3000);
led.turn_off_all();
timer.pause(100);
// a mango
led.setLight(0, 255, 140, 0);
led.setLight(1, 255, 140, 0);
led.setLight(2, 255, 140, 0);
led.setLight(3, 255, 140, 0);
timer.pause(3000);
led.turn_off_all();
timer.pause(100);
// a watermelon cracking open
led.turn_on_all(GREEN);
timer.pause(1000);
led.turn_on_single(SE, RED);
led.turn_on_single(SW, RED);
timer.pause(500);
led.turn_on_single(NW, RED);
led.setLight(2, 0, 0, 0);
timer.pause(3000);
led.turn_off_all();

} 

`

This code changes the colors of the LEDs, flashes the LED and vibrates the bracelet at different strengths and duration. 

It’s fascinating to wear programming made by someone you don’t know. It’s a new art, a new form of expression.
 
 //[❤️] 







