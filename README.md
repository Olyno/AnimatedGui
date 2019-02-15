# AnimatedGui
Animate your guis in Skript!

**How work with AnimatedGui?**

 1) Open a gui with the name of you want.
 2) Create a gui in ``plugins/AnimatedGuis/Guis`` with the name (uncoloured) of your gui.
 3) Do a ``/sk reload all``
 4) Open a chest with the name of your guis and enjoy the animation that you selected!
 
 **Example:**
 ```vb
open chest inventory with 6 row with name "&9Main" to player
```

Examples are created when Skript starts.

# FAQ

**How can I install this tool?**

> Download it and put it in the **"plugins/Skript/scripts"** folder. Then download the addons it needs:
 - [skript-mirror](https://github.com/btk5h/skript-mirror/releases)
 - [SkUtilities](https://github.com/tim740/skUtilities/releases)
 - [skript-yaml](https://github.com/Sashie/skript-yaml/releases)
 
> Finally, restart your minecraft server. You are ready to use it!

**How to propose an animation?**

> It's very simple. First, create your animation. After that, use the "ScreenToGif" software to make an animation gif in your gui. After that, make an issue on the github or a pull request of your animation. If no problems occur, then your animation will be accepted and anyone using the "AnimatedGuis" tool can use your animation!

**Important:** The gui of you use must to have the name ``&9Main``.

**Who can use my animations?**

> Anyone who has the "AnimatedGuis" tool in their scripts. All they need to do is to retrieve the animation you made and place it in their ``plugins/AnimatedGuis/Animations`` folders.

**How can I create my animation?**

> You can use an example and edit it to make your proper animation. More informations [here](https://github.com/AlexLew95/AnimatedGui/blob/master/Animations/README.md).
