# FoundryVTT-Macros

Hello everyone,
*UPDATE*

-I added a new Version for Foundry 0.8.6

-The new Version now always misses on a nat 1 ( somehow i missed that :[ )





I want to share my Animate Objects Macro.

Since I’m not a programmer, but wanted to use AO with midi-qol (for the sanity of my DM), I started to “learn” Javascript and a little html.

I’m pretty sure, a person who knows how to code can do a better job, but it works and look ok, in my opinion.

The Macro will send a blind roll to your dm with the AC you roll against.Since you can add a modifier to the AC ( for cover or something else )I feel the need to send it. You can disable this in the 4th line of the macro.

Here is the Popup and Chat for the macro User:
![AO Player](https://user-images.githubusercontent.com/53573492/120703408-8c7c1980-c4b5-11eb-83e4-5df785ff2a3d.png)

and the AC check for your DM:
![ao DM](https://user-images.githubusercontent.com/53573492/120703440-969e1800-c4b5-11eb-9944-e36471337b18.jpg)

Keep in mind, you have to use midi-qol and Advanced Macros in your Foundry World.

How to:

Enable the “Macro on Use” Option in the Workflow settings of Midi-Qol (Admin only)
create a new script macro and copy the content of “Animate Objects Attack.js”
Create a new Cantrip on the token you want to use as the attacker, with nothing in it, except the name of the macro in the “On Use Macro” field.
Select 1 Enemy and your AO token ( or your caster if you play without a extra token)
Cast the Cantrip.
Choose your Options and click one of the buttons to attack.

I hope somebody won’t have to do the work and use this :)
