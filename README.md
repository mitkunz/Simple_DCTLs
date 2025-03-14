# Simple_DCTLs

DCTL (also known as Davinci Color Transform Language) is a programming language designed for creating custom effects and tools for Davinci Resolve.
Feel free to check out these DCTLs I made specifically for everyday color grading tasks.

## Technicolor Emulation

A little DCTL that simulates the Technicolor look. You can fine-tune the RGB Mix values and also enable a logarithmic rolloff function to eliminate clipping. 
The basic RGB mix idea is an adapted version of the PowerGrade implementation by [Tim Yemmax
](https://www.youtube.com/watch?v=NlvvBf9UcOk) and [JanikBrosFilms](https://www.youtube.com/watch?v=kXNRtrK3Lx8), which is further improved with anti-clipping functionality.

Example             |  Settings Panel
:-------------------------:|:-------------------------:
![dctl_technicolor_example](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/d0ade95d-f9d3-4692-bb0a-433fe08e6d61)  |  ![dctl_technicolor_settings](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/994dfc80-d3b1-4882-9f82-b22c1bb169fb)


## Film Saturation Emulation

This Saturation DCTL enables you to easily achieve rich levels of saturation without worrying about any color clipping in any channel. A logarithmic rolloff function compresses high saturation areas.

Example             |  Settings Panel
:-------------------------:|:-------------------------:
![dctl_sat_example](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/2f0f4de6-7c4e-4ba4-a24d-84ef9315d2dc)  |  ![dctl_sat_settings](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/f99a52ba-e8b9-432d-bbb9-4ef074522d34)


## Adjustable Grey Card

Think of it as your trusty grey card, but with added perks. Not only does it allow you to fine-tune the black and white levels, but you also have the flexibility to adjust the displayed steps of dynamic range.

Example             |  Settings Panel
:-------------------------:|:-------------------------:
![dctl_greycard_example](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/3e91d563-ef07-47bf-81fa-62ab2e877e90)  |  ![dctl_greycard_settings](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/d8d2118d-ffe5-4e1e-b219-b64cf53387f4)


## Animatable Letterbox

This ist simply a Letterbox DCTL with presets of all the common formats (Scope, CinemaScope, Netflix, Flat, HDTV, iMax, Academy, Square, Instagram, Tim Tok), but this DCTL takes it a step further by being fully animatable. Now, you can dynamically adjust your aspect ratio using keyframes right on the color page.

Example             |  Settings Panel
:-------------------------:|:-------------------------:
![dctl_letterbox_example](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/84f5e9e4-dc0c-49db-9229-7c7790906b5b)  |  ![dctl_letterbox_settings](https://github.com/mitkunz/Simple_DCTLs/assets/143692878/25240d6f-1cdc-4125-987a-7fb4aafa6bc9)

