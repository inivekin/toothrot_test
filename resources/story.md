#: Testing toothrot


##: default

###: start

Hello there little one. Are you lost? (# further options => {"inspect":
"description", "smile": "smiling"} #)

(: What should I do? => click :)

(@) pwease help me kind sir, i'm just a little kiddy trying to make their way in this gosh darned world => sympathy_help
(@) don't touch me => anger_recoil
(@) *squint at him until he burns* => horrifying_death_sequence

###: description

They are very tall

(<)

###: smiling

Smiling does nothing in life. You need to take action.

(<)

###: sympathy_help

Don't worry little one, climb upon my back, we shall make it to safety.
(~~~)
Wait - you've purified yourself, right?
(~~~)
Surely you have.
(~~~)
Everyone has.
(~~~)
Including you...
(~~~)
Right?

(#) timeout: 10000
(@) YES! I swear! *and ride him like a steed to safety* => lie
(@) *BITE! BITE AT HIS HANDS* => horrifying_death_sequence

###: anger_recoil

AUUAGH!! Disgusting little one. Your parents should've taught you better.
(~~~)
Repent or I finish you.

(>) fight_to_death

###: lie

I don't think I believe you.

(>) lie_2

###: lie_2

I'll have to kill you to make sure.

(>) fight_to_death

###: fight_to_death

(#) timeout: 5000
(#) defaultOption: 0
(@) *BITE HIM YOU MUST BITE HIM* => horrifying_death_sequence
(@) *Plead for mercy* => die

###: horrifying_death_sequence

You stare intently at the tall one. They begin to shake. Begin to sweat. Begin
to cry out in pain. In a moment of confusion he reaches out to you expecting
the sympathy or the mercy they had for you, but you bite them (as is your
nature).
(~~~)
Your teeth sink into their skin and then your jaw sinks into
their skin and then your head seeks into their skin and then ...
(~~~)
Where are you? What is your name? You're very tall. Who is that little one over
there? Maybe they need help?

(>) start


###: die

The tall one climbs onto you. Your little hands a pinned to the ground.

A quick flick breaks your neck. You're done.


###: click

Click a button ya goose..

(<)

