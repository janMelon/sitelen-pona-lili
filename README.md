# sitelen-pona-lili
"sitelen pona lili" is a sitelen pona font with "simplified" characters for typing in toki pona. 

![initial design](https://github.com/janMelon/sitelen-pona-lili/blob/main/sitelen-pona-lili-laso.png)

## Setting up the Font
After installing the font, turn on Kerning, all Ligatures, and the "use Contextual Alternates" option. In MS Word, you can find this option by either right-clicking and then selecting "font" or by pressing Ctrl+D. 

![font set up](misc/initial-settings.png)

## Using the Font
### The Alphabet
Sitelen Pona Lili has its own alphabet. Vowels (A, I, U, E, O) and N are the same as their sitelen pona ideograph. Consonants are half-width versions of sitelen pona ideographs with a corresponding initial phoneme, e.g. the letter "P" is the half-width version of the sitelen pona ideograph "pini".

### Typing Basic Words
If you have turned on ligatures, then every time you type a *toki pona* word, the string of individual letters will be automatically converted to its *sitelen pona* glyph. E.g. if you type the word "ale", then it will be converted to the *sitelen pona* glyph for "ale" which looks like an infinity sign ⟨∞⟩. Currently, all *pu* words and *ku suli* words are available in this font.

### Name Cartouche
Names in *toki pona* are written by putting glyphs inside a cartouche. You may use a sitelen pona ideograph or just the font's alphabet. To start a cartouche, type a left square bracket ⟨ &#91; ⟩. Then, type an underscore ⟨ &lowbar; ⟩ to make the upper and lower lines of cartouche. Now you can type any *sitelen pona* glyph and it will automatically be put inside the cartouche. To close the cartouche, type a right square bracket ⟨ &#93; ⟩. E.g. "jan Melon" can be written as "jan &#91;&lowbar;ma&lowbar;ee&lowbar;li&lowbar;oo&lowbar;ni&#93;".

## How Does This Actually Work?
As you may have already guessed, the font works by ligature substitution (liga) to replace multiple characters in a row with a single new character. Kerning (kern) for cartouches and other container glyphs is set to negative to make them overlap with the next glyph. This was made using [FontForge (p.s. it's free)](https://fontforge.org/en-US/) and you can see the [FontForge sfd files for this font here](/fontforge-files). There are many tutorials out there; specifically I followed [this one](https://www.youtube.com/watch?v=UUUeogQAjv0) when working on this.
