# Effects

Effects are post-production tools that are designed to manipulate visuals in real-time. Effects apply filters or enhancements to change the way an image is represented.

![img](../assets/bad_apple.png)
<small>A frame of Bad Apple, with ASCII and Chromatic Abberation applied.</small>


### Master effects chain

<p>The master effects chain is the main effects pipeline of your project. Parameterized effects can be added onto the pipeline, where you can edit the video to how you wish. Effects can be rearranged, customized, and automated.</p>

![img](../assets/guide/master-fx-chain.png)<br>
<small>The master effect chain with listed effects.</small>

### Effects library

![img](../assets/guide/effects-library.png)

The effects library is a collection of effects that can be applied to media. It is located on the right side of the bottom deck of the VJ.

### Adding effects

<p>To add an effect, navigate to the effects library (bottom-right panel), and drag your desired effect to the effects chain. The effect will be immediately applied, and you can customize it by clicking on the chevron to drop down its parameters.</p>

### Controls

![img](../assets/guide/effect.png)<br>

From left to right:

- __Dry/wet slider__ - Adjusts the ratio between the dry (unprocessed) and wet (processed) signal.<br>
- __Options__ - Open options for effect<br>
- __Lock__ - Disables editing of the effect.<br>
- __Eye__ - Toggle whether the effect is active. Turn off to disable cooking.<br>
- __X__ - Delete the effect from the FX chain.<br>

### Adding custom effects

<p>All effects are stored in the '/effects' directory as Components. Each effect has its cooking set to false, as to not consume resources in the background. Effect cooking is automatically turned on once applied to an effects chain.</p>

<p>To be recognised as an effect, it must have the operator tag 'effect', and the effect's input and output must be of a TOP type. You can copy an effects template from the '/templates/' folder.</p>