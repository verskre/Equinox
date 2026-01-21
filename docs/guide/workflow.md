# Workflow

### Pipeline

Equinox implements a five-stage pipeline to generate real-time visual output. Equinox utilises Derivative's built-in Scene Changer from the pallette to handle scenes. All scenes are stored in the '/scenes' directory. The scene's output is routed to the Scene Changer at the start of the pipeline.<br>

The signal then follows:<br>
&nbsp;1. __Compositing__ - Media is mixed in with the source signal.<br>
&nbsp;2. __Master FX chain__ - Pipeline of effects that manipulate the signal<br>
&nbsp;3. __Grading__ - Final video corrections and color grading<br>

The processed signal is then sent to output.


![diagram](../assets/Workflow1.png)

### Output & projection

Equinox draws one large window that extends to all connected monitors.