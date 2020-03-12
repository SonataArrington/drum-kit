Javascript Project 1 of 31

Drum Kit 

This is a digital drum set that allows you to play a drum sound when you press the key associated with that sound.

The keys are:

* A- CLAP
* S- HIHAT
* D- KICK
* F- OPENHAT
* G- BOOM
* H- RIDE
* J- SNARE
* K- TOM
* L- TINK

In this project:
* addEventListeners - attaches an event handler to the specified element. element.addEventListener(event, function);

* keyCodes A number which represents an actual key on the keyboard. It returns the Unicode character code of the key that triggered the onkeypress event, or the Unicode key code of the key that triggered the onkeydown or onkeyup event.

* The data-* global attributes form a class of attributes called custom data attributes, that allow proprietary information to be exchanged between the HTML and its DOM       representation by scripts. (Best description I could find). For example :

    - const audio = document.querySelector(`audio[data-key="${e.keyCode}"]`);
    - Selecting an audio element with the data dash key pointing to the keyCode

* Transitioned/Transitionend - object.addEventListener("transitionend" or "transitioned", function);        // Standard syntax

* Keyword 'this' refers to the object that it belongs to. var greeting = {morning: "Good morning", afternoon: "Good afternoon", evening: "Good evening", function() {this.afternoon;}}

