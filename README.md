CSS Flat Buttons
================

Beautiful and highly customizable CSS buttons created by [KBRmedia](http://gempixel.com). View Live demo at http://gempixel.com/css-buttons/.

##Usage

The usage is very simple. All you need to do is to add the appropriate class and that is it. The list of class is as follows:

###Colors
**.green**, **.blue**, **.red**, **.orange**, **.purple**, **.black**

####Sample Markup assuming namespace is button

**Anchor/Link**

```<a href="" class="button red">I am a red button</a>```

**Input[type=submit]**

```<input type="submit" class="button red" value="I am a red button">```

**Button**

```<button class="button red">I am a red button</button>```

###Rounded corner

Just add **.rounded** to make the button rounded. The radius can be customized in the less file.

```<a href="" class="button red rounded">I am a red button</a>```

###Tooltip

Just add **.tooltip** and **data-tooltip="YOUR TOOLTIP CONTENT"** to enable the tooltip.

```<a href="" class="button red tooltip" data-tooltip="I am a tooltip">I am a red button</a>```

##Customization

You can easily customize the .less file included in the package and parse it using an online like less2css.org. Below is the list of variables you can modify.

 @namespace: button; // Button class name e.g. class="button"

 @font_size: 14px;  // The size of the font of the button

 @font_family: Helvitica, Arial; // The font family of the button

 @border_radius: 5px; // The border radius of the rounded style

 @default_color: #eee; // Default color of the button (class="button")
 
 @green_color: #7BA813; // Color of the green button (class="button green")

 @red_color: #C12D17; // Color of the red button (class="button red")
 
 @blue_color: #0093B7; // Color of the blue button (class="button blue")

 @orange_color: #DD8104; // Color of the orange button (class="button orange")

 @purple_color: #8C24FF; // Color of the purple button (class="button purple")

 @black_color: #444444; // Color of the black button (class="button black")



##License

This work is licensed under a Creative Commons Attribution 3.0 Unported License. Feel free to use it for both personal and commerical projects. You can linkback to my site http://gempixel.com if you want to but you are not required.
