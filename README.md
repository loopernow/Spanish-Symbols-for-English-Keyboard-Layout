# Spanish-Symbols-for-English-Keyboard-Layout
Small program for quickly typing Spanish accented vowels, eñes, diéresises, and inverted question marks and exclamation points without switching your keyboard layout or sacrificing any existing characters.

## How to use
Download the .exe and run it, or download the .ahk file and run it with Autohotkey v1. Then, press a single quote followed by a vowel to produce an accented vowel, or two periods followed by a u to produce ü, or two semicolons to produce ñ, or Alt plus ! or ? to produce ¡ or ¿. Case is honored, so typing two colons produces Ñ, typing ..U produces Ü, and typing ' plus a capital vowel produces an accented capital vowel (Á, É, etc.)

There may come a time that you want to type "ma'am." Don't worry. You can do that, and it won't turn into "maám". That edge case is accounted for.

There may come a time that you want to type a quote in the British English Style, but the quote begins with a vowel: 'Anyways, I don't think that's a good idea,' she said. Don't worry, you can do that too. To produce a single quote mark followed by a vowel, just type two single quote marks consecutivily, then type whatever you want. So, type ''Anyways to produce 'Anyways.

This script is only active when an English keyboard layout is active. While a Spanish keyboard layout is active, this program is dormant.

## Acknowledgements

Original inspiration for this script is here: [https://www.autohotkey.com/boards/viewtopic.php?t=82484](https://www.autohotkey.com/boards/viewtopic.php?p=469393#p469393). All I did was tweak it a little; the core idea is Autohotkey user guivho's. My primary contribution is typing double punctuation (; : .) plus an n or u to get a ñ or ü quickly, and pressing Alt plus the ! or ? key to get a ¡ or ¿ quickly. The inspiration for the double semicolon or colon to get ñ or Ñ is the typical Spanish keyboard layout, where the ñ key is next to the l key.

AI helped me write some of the code, primarily for a pretty help menu and for the functionality of only being active when an English keyboard layout is active.

I uploaded a previous version of this script at [https://www.autohotkey.com/boards/viewtopic.php?f=6&t=66744](https://www.autohotkey.com/boards/viewtopic.php?f=6&t=66744).
