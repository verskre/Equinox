# Compositing

The compositor blends multiple layers of media, such as videos and graphics, into one final output. Compositing is used for programmable visual effects and overlaying graphics. Each layer is blended with the previous layer.

![img](../assets/compositor.png)<br>
<small>The compositor, with 4 layers and multiple clips loaded.</small>

## Layers

![img](../assets/guide/layer.png)<br>

A layer is a collection of compiled clips, where each layer plays one clip. Layers are equipped with their own effects chain, where effects can be applied onto the layer before blending.

## Adding clips

![img](/assets/guide/insert_clip.gif)<br>

To add clips, simply drag a file from a file explorer into an empty clip slot. To remove the clip, hover over the clip slot and click the "X" on the top-right.

## Controls

### Mixing

![img](../assets/compositor_controls.png)<br>

- **B** — Bypasses the layer from composition.
- **S** — Solos the layer, bypassing all other layers from composition.
- **X** — Removes the clip and any effects in its FX chain.

The alpha slider controls the alpha of the clip.<br>

### Blend mode

You can customize how layers are overlayed by changing the blend mode. The blend mode determines how layers are overlayed with each other.

### Playback controls

![img](../assets/guide/layer-playback.png)<br>

The skip buttons transverse through the layer's active clips. By default, it skips over empty clip slots.<br>

### Clip manager

![img](../assets/guide/clip-manager.png)<br>

On the lower deck of the VJ, next to the effects library, is the clip manager. The clip manager has configurations for playback, transform and the effects chain.

### Playback

- __Blend mode__ - Control blend mode<br>
- __Speed__ - Adjust speed of clip<br>
- __Trim start__ - How much of the clip is cut at the beginning<br>
- __Trim end__ - How much of the clip is cut at the end<br>

### Transform

- __Translate X__ - Translation in the x-axis<br>
- __Translate Y__ - Translation in the y-axis<br>
- __Rotation__ - Degree of rotation, in degrees<br>
- __Scale__ - Degree of scale<br>

### Cue points

TBA

## Effects chain

Each layer has its own effects chain, where different effects can be applied onto a layer. Effects are processed before the layer is composited.<br>

To add effects onto an FX chain, navigate to the effects library and drag the effect onto the FX chain.<br>

![img](../assets/guide/clip-fx-chain.png)<br>
<small>Look at this cool kalediscope!</small>