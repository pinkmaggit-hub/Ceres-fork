# Ceres

# folder name

please make sure the folder is called `Ceres`, otherwise youre going to get a big crash

# important !!!

im gonna class this as a pre-release, because this mod isnt in a state where i want to release it just yet
reason i am making this is because im going away for a week and wont be able work on it then, so i wanted
to get something out, that way hopefully i can get some feedback on current features and also heads up on
any bugs people encounter than i need to squash. with that in mind, every single part of this mod is able
to be disabled via the config page, so if there is something absolutely game breaking that i cant fix before
i go away then please disable it and i will get round to fixing it as soon as im able

# compat

i havent had a great chance to test with a wide variety of mods, so unsure of any potential game breaking stuff
that being said, everything is disablable (idk if thats a word). from the little bit of testing i have done, as
far as i can tell this mod is compatible with cryptid and talisman, as well as of course being functional as a 
standalone mod. if you encounter any compat issues then please let me know as soon as and i will get straight on
fixing them.

# current features

at the time of writing this, this mod adds:
- 13 new jokers (2 currently unobtainable tho)
- 9 new tarot cards
- 2 new planet cards (currently removed because i didnt have to time to fix properly lol)
- 2 new spectral cards
- 7 new card enhancements like effects
- 2 new vouchers
- 2 new editions
- 4 new booster packs
- 5 new blinds
- 3 new suits

5 of the new enhancements im going to refer to as perk cards, as the packs for them do. these are essentially cards that have
special effects when you play them. im also working towards making them a unique game item, instead of being found under the
enhancements, but for now having them as enhancements works well enough, and due to the small amount of them they shouldnt clutter
the collection too much. there are some new terms i use for these cards but everything is explained it info boxes, hopefully
clearly enough

when it comes to disabling features, things such as consumables are tied to relevant suits/enhancements etc. for example, disabling
one of the suits will also disable the corresponding suit conv consumable, and blind for that suit. i feel that makes the most sense
but if thats something people want changed i would be more than happy to

# known 'quirks'

currently 2 jokers are unobtainable through legitimate means, namely the makima and aizen 'divine' jokers. i do plan
on adding ways to obtain them further down the line, but as i mentioned i wanted to get something released soon. the
snakes eyes joker is currently only compatible with vanilla joker/enhancements, as ive had to hard code the compat list
for the time being, i would like to figure out a way to do it dynamically, but considering the inconsistencies between
mods and even base game items im unsure if itll be possible.

im also in the process of making the colourblind edition only available on compatible jokers, but my code apparently just
stopped working so for the time being its available on all jokers (and playing cards) but will not function on some jokers,
but just take up the edition slot, please bare that in mind when using the spectral to apply the edition.

with regards to features that dont quite function how i want them to just yet, the makima joker has a few quirks when retriggering
other jokers, such as jokers like hack or hanging chad, that retrigger other cards, if youre going to use the joker then im afraid
youll just have to bare with that for now

also something very important to note, is that i would like to implement unlock requirements for different jokers etc in the future
i know thats not something everyone would like so in the misc options you can enable unlock all / discover all. unlock all is enabled
by default when the settings file is created, because otherwise you would have no way to unlock any locked items, so i urge you to
keep that setting on until i have sorted out proper unlock requirements

# stuff ive had to disable for the time being

- ben joker, incompatible with talisman i think, he cant handle big numbers
- the planet cards for the time being, maybe due to incompat with bunco i think, they were locked behind
one of the unobtainable jokers anyway

# last few notes

just to recap, this mod isnt quite in a state where i want it yet, but it should be stable enough to use. any problems you have with 
the mod, please just drop a message in the thread for it on the balatro discord, or drop me a dm on discord at nekojoe. thank you to
everyone on the balatro discord who has helped me out with anything, god knows what id be doing without that help lol