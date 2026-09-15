# motor-controller-notes
relatively informal notes, schematics, code snippets and other resources for EVC custom motor controller development, structured for obsidian.

very much a work in progress, so many links will lead to unfinished pages
# table of contents
[types-of-motors](learning%20materials/types-of-motors.md)
[motor-control-schemes](learning%20materials/motor-control-schemes.md)
[mc-26-schematics](mc-26-resources/mc-26-schematics.md)
[half-bridge](motor-controller-notes/learning%20materials/half-bridge.md)



note: i recommend going through these chronologically as later sections typically rely on previous sections, although it can be equally helpful to skip around sections by following the links to notes for vocab words/concepts that are unfamiliar
# additional resources
here are some videos/texts that i personally found useful. these are referenced throughout the note vault, but are also consolidated here for easy access

**videos:**
[Field Oriented Control of Permanent Magnet Motors](https://www.youtube.com/watch?v=cdiZUszYLiA)
- really good for understanding how *controlling* the motor works with a bunch of animations/simulations
- definitely recommend watching first ~25 minutes regardless if you are interested in writing control firmware/software or not

[High Performance Motor Control From the Ground Up || Field Oriented Control (FOC)](https://www.youtube.com/watch?v=ujofKWmGChw)
- less of a focus on the technical terms for motor controls, still covers the basics of it
- personally found the [TI FOC](https://www.youtube.com/watch?v=cdiZUszYLiA) video much more helpful in explaining intricacies of FOC
- discusses specific hardware choices in much more detail
- includes the github links, so you can poke around both the hardware and the software for both the motor drive and controller


**pdfs/textbooks:**
[Motor Control Compendium](https://www.ti.com/download/trng/docs/c2000/TI_MotorControlCompendium_2010.pdf)
- want to know what things mean but don't know where to start because none of the words seem english? you're in luck because this is basically every word you will ever hear that is associated with motors
- dave wilson from TI is my goat

**articles in general:**
[Introduction to Brushless DC Motor Control](https://www.mathworks.com/campaigns/offers/next/introduction-to-brushless-dc-motor-control.html)
- really good gifs for visualization
- pretty quick read
	- six "chapters" which are relatively short pages

