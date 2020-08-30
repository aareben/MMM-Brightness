# MMM-Brightness
This is a brightness module for the official raspberry pi 7 inch display. It might be able to work on other displays but I am not able to test it.
This is not a visual module and therefore you require another module to send notifications to this module. I recommend this module as it's the only one I've tested. (https://github.com/tosti007/MMM-TouchNotifications) 

I am happy to accept any changes or critisizm because this is my first module and I'm a noob in javascript.

## Installing
First go into the modules folder
````
cd ~/MagicMirror/modules
````
then copy this module in
```` 
git clone https://github.com/aareben/MMM-Brightness.git
````
then go to your config file and paste this in.
````
 {
  module: "MMM-Brightness",
  config: {
  //Config stuff
  }
 },
````

## Config Options
| Option             | Description
| ------------------ | -----------
| `startingBrightness`| Brightness to start the Magic Mirror on. <br><br> **Possible values:** `10 to 200` <br> **Default value:** `130`
| `jump`         | The amnount that the brightness goes up or down when you activate. <br><br> **Possible values:** `1 to 30` <br> **Default value:** `10`

---------
Any questions, please start an issue and I will be happy to answer them.
