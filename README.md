# Custom Items
An updated mobile compatible version of Johuan's Custom Items.

Check this [forum post](https://tshock.co/xf/index.php?resources/custom-items.220/) for details on how to install, manage, and use this plugin.

Allows you to spawn an item with custom attributes
These items will reset when you drop it, store the item in a chest or other container, or leave the server, so you cannot transfer it to another person.

Command:
/customitem <itemid/itemname> <parameters> <#>
/citem for short

/givecustomitem <playername> <itemid/itemname> <parameters> <#>
/gcitem for short

Parameters
hexcolor (hc)
Gives a custom color to an item (client side)
Example of hex: 0000FF is blue
damage (d)
Custom damage to an item
knockback (kb)
Custom knockback
useanimation (ua)
Amount of time an item will linger when a player uses it
Use with usetime so when an item has finished firing, the animation will finish at the same time
usetime (ut)
Amount of time it takes to use
shoot (s)
The projectile shot by an item
shootspeed (ss)
The speed of the projectile shot by an item
width (w)
Width of an item (client side)
height (h)
Height of an item (client side)
scale (sc)
The multiplier of an item's size when it is used (client side)
ammo (a)
Gives an item the ammo attribute
useammo
Tells when ammo an item uses
useammo 0 means the weapon will not use ammo
notammo (na)
Tells whether an item is not an ammo
Either true or false
Order doesn't matter when inputting parameters. You can put any parameters you need, however you want them.

Examples
Chlorophyte shotbow that shoots cannonballs really fast

/customitem "chlorophyte shotbow" scale 2 damage 400 useammo 0 shoot 162 shootspeed 25 usetime 4

customitem
customitem.give 
