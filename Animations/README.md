## Create your own animations:

**What is:** _(about the example below) (Explained in the order)_

 - "6_rows":
   - 6_rows represents the number of rows required for this animation. Here, this animation can only be used in the guis of 6 rows.
 - "frames":
    - frames represent the steps of the animation. They will be read in order. The "ids" of the frames do not matter.
 - "0": 
    - 0 is the id of the frame.
 - "duration": 
    - duration is the time that the frame will last.
 - "slots":
     - slots is the list of all slots which will change in this frame.
 - "0": 
     - 0 is the slot n°0 of the gui.
 - "name": 
     - name is the name of the item in the current slot.
 - "lores": 
     - lores are the lores of the item in the current slot.
 - "enchants": 
     - enchants are the enchants of the item in the current slot.
 - "item": 
     - item is the item of the current slot.
 - "sound": 
     - sound is the sound that the slot will last.
 - "duration": 
     - duration is the time that the slot will last.
 - "only_item": 
     - This part was created to be able to create an animation with only one item. All your animation will be done with the same item, the same enchantments etc... (same parameters that a slot)
 - "time_per_frame": 
     - time_per_frame is the time between each frame. The time of the slots will always be more important than the time of the frames.
 - "sound_per_frame": 
     - sound_per_frame is the sound that will be play between each frame. The sound of the slots will always be more important than the time of the frames.
 - "looped":
     - looped is if you want to loop the animation a infinite time.

**Parameters availables:**

| Parameter's name | Type          | Can be used in       |
|------------------|---------------|----------------------|
| name             | String        | slots                |
| lores            | Strings List  | slots                |
| enchants         | Enchants List | slots                |
| item             | Item Stack    | slots                |
| sound            | String        | everywhere           |
| duration         | Timespan      | everywhere           |
| looped           | Boolean       | animation itself     |

**Example of simple animation:**
 
 ```yml
6_rows:
    frames:
        '0':
            duration: 0 second
            slots:
                '0':
					name: My blue glass!
					lores:
					- I try a first lore
					- and a second lore
					enchants:
					- Sharpness 1
					- Efficiency 5
					item: blue glass
					sound: entity.firework.launch
					duration: 1 seconds
	only_item:
        item: /
    time_per_frame: 3 ticks
    sound_per_frame: block.anvil.break
    looped: false
 ```

## List of all animations available:

**squareFromBottom:**

![](https://i.imgur.com/hPt6zsk.gif)

**squareFromTop:**

![](https://i.imgur.com/kUTutNd.gif)

**squareFromLeft:**

![](https://i.imgur.com/tEiwbkI.gif)

**squareFromRight:**

![](https://i.imgur.com/eRPwb4t.gif)

**loadingLeft:**

![](https://i.imgur.com/JUeDp04.gif)
