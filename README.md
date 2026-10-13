# Bear's Password Page ʕ•ᴥ•ʔ

Your passwords suck. Mine don't. Let's fix that.

A bear with anger issues generates strong, ridiculous passwords inside a fake Windows 95 window, on a homepage that never left 1997. It runs in your browser and sends nothing anywhere, because I don't want your shit.

The bear swears. If that's a problem, close the tab and go back to using `password123` like a goddamn animal.

**[Open the damn site](https://YOUR-USERNAME.github.io/YOUR-REPO/)**

## What you get

```
STR@n93Ly?FAnTAST!c?h0Rs3      strangely fantastic horse
5hyLY*eTh3r3@l*Urch!n          shyly ethereal urchin
c@rEfuLlY?@MAz!N9?k03L         carefully amazing koel
```

Yes, those are real passwords. Yes, they look like a keyboard fell down the stairs. That's the point.

Every password is an **adverb + adjective + animal**, and then the bear fucks it up a little:

- one random symbol gets jammed between the words
- letters that can turn into symbols usually do (a→@, e→3, i→!, o→0, s→5, g→9)
- every other letter gets random caps, like a ransom note
- anything over 30 characters gets rerolled, because some websites are babies about long passwords

Under each password you get the plain words ("Reads as: strangely fantastic horse"), so you can actually remember it. You're welcome.

## "But is it safe tho?"

Yes. Calm down. **As long as you use a different password on every site.** If you reuse it everywhere, that's on you, and the bear will find out.

- About **52 bits** of strength, roughly the same as a 4-word diceware passphrase. And that's assuming the attacker knows *exactly* how this thing works and has the same word lists. Knowing the recipe doesn't help when the ingredients are random.
- Randomness comes from your browser's actual crypto generator (`crypto.getRandomValues`), not `Math.random`, which is basically a snitch.
- Everything happens on your device. No server, no cookies, no tracking, no analytics, no outside requests. The font is baked into the page. I literally could not spy on you if I wanted to. And I don't want to. You're not that interesting.

For the really important shit (your password manager's master password, your main email, disk encryption), use something longer. Don't be lazy about the one password that guards all the others.

## Run it yourself

It's one HTML file. Download `index.html`, double-click it, done. Works offline. Works on a plane. Probably works in a bunker. Doesn't need npm, doesn't need a build step, doesn't need your fucking email address.

## Features nobody asked for

- a bear that judges you
- a bear that gets increasingly pissed off if you click "Gimme another one!" too many times (try 50, I dare you)
- a visitor counter that is completely fake and proud of it
- 88x31 buttons, including a free cupholder (no, it doesn't actually open your CD drive, browsers ruined that decades ago)
- twinkling stars, because I'm not a monster
- a dark mode, for people whose eyes can't handle the raw power of Windows 95 grey
- a custom 404 page, because the bear eats pages now
- secrets. a bunch of them. find them yourself, I'm not your mom

## Credits and licences

The boring-but-important legal bit. Read it, it's short.

- **My code** is under the [MIT License](LICENSE). Fork it, steal it, remix it, just keep the licence in there.
- **Adjective and animal word lists** come from [coolname](https://github.com/alexanderlukanin13/coolname) by Alexander Lukanin, under the BSD 2-Clause License. See [LICENSE-coolname](LICENSE-coolname). Thanks, Alexander. You're a legend.
- **Comic Neue font** by the Comic Neue Project Authors, under the SIL Open Font License 1.1. See [LICENSE-comicneue](LICENSE-comicneue). Real Comic Sans is used when your computer has it. Android doesn't, so it gets Comic Neue instead of that cursed handwriting font.

The MIT license only covers my code. The word lists and the font keep their own licences. Don't be weird about it.

---

The bear does not represent the views of anyone. The bear barely represents the views of the bear. ʕ •`ᴥ•´ʔ
