# DND 5.2 SRD in Markdown

The project is roughly complete and currently should be widely useable.

There is a caveat that it isn't consistently formatted all the way through. Primarily features are not denoted the same way through out the document. I also haven't done any passes through to do proof reading to ensure that I didn't miss any weird line breaks in the middle of sentences. I did correct them as I saw them going through, but I could have missed some.

I may go through and clean up the formatting and proof read at some point, but honestly, it's pretty much done and anyone should feel free to use it as is. Any changes will be relatively minor and won't really affect most people very much.

Please use this however you please, while still abiding by the license terms that wizards of the coast put on the original document, which also apply to this document.

## Formatting changes

There was a step by step numbered list in "Playing the Game" in the "D20 Tests" section that was numbered beginning at 4 and ending at 6. I changed this to be 1-3 instead, since that seemed to be the actual intent, and the 4-6 numbering seemed like a typo.

The class tables for each class had a heading above all the spell slots that reads `--Spell Slots Per Level--` with the numbers directly beneath them. I removed that text and put it in the table caption. I am not certain mark down could support having multiple header lines as it was done here. I like the approach OldManUmby took in their work on the [DND SRD ReMastered](https://github.com/OldManUmby/DND.SRD.Wiki) project, where caster classes have their spell slots in a seperate table from their main class. But I decided not to do that since I'm going for accurate to the original as a base for everyone. This project is meant to enable people to do whatever they want with it, including improve it.

The PDF puts "Monsters A-Z" as a sub section of Monsters. I put it as its own independent chapter, like the "Animals" chapter is in the pdf.

I didn't go through and add subsections in the monsters a-z section. For example "Animated objects" isn't a section. You'll just find the animated object listed individually.

## Process

I used a wonderful tool called [marker](https://github.com/VikParuchuri/marker) to generate a "pretty good, but still needs work" markdown file, which I then split into multiple files. So far as I can tell, the main section that came out the roughest was the monsters / animals sections. I may try and re-generate just those sections by themselves to see if I get better results.

Basically, this was a semi-automated process. I generated a base file, and then I painstakingly go through and ensure the format, tables, headings, etc... are how I want them.

For the monsters, I took the excellently done ones from [Mike Shea's Lazy GM Tools repository](https://github.com/mshea/lazy_gm_tools), of [slyflourish.com](https://slyflourish.com/) fame. If you need 5e monsters, definitely check that repository out. There are monsters from many sources there including some of kobold press's monsters and level up advanced 5e.

## Markdown Extensions

Table captions are denoted with `Table: Caption Text` before tables.

## Contributions

I likely won't accept any as the project is largely done. But feel free to use this repository for your own project, GM notes, player notes, making a better version of them in markdown, whatever. 

## Legal Notice

This work includes material from the System Reference Document 5.2 (“SRD 5.2”) by Wizards of the Coast LLC, available at https://www.dndbeyond.com/srd. The SRD 5.2 is licensed under the Creative Commons Attribution 4.0 International License, available at https://creativecommons.org/licenses/by/4.0/legalcode.