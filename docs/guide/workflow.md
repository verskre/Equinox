# Workflow

### Pipeline

Equinox implements a five-stage pipeline to generate real-time visual output. Equinox utilises Derivative's built-in Scene Changer from the pallette to handle scenes. All scenes are stored in the '/scenes' directory. The scene's output is routed to the Scene Changer at the start of the pipeline.<br>

``` mermaid
graph LR
  A[Scene] --> B;
  B[Compositing] --> C;
  C[Master FX chain] --> D;
  D[Grading] --> E;
  E[Output];
```


### FX Stages
&nbsp;1. __Scene__ - Final video corrections and color grading<br>
&nbsp;2. __Compositing__ - Media is mixed in with the source signal.<br>
&nbsp;3. __Master FX chain__ - Pipeline of effects that manipulate the signal<br>
&nbsp;4. __Grading__ - Final video corrections and color grading<br>
&nbsp;5. __Output__ - Final video corrections and color grading<br>

### Output & projection