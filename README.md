# ShowVizness
Build and perform show cues in TouchDesigner. The system revolves around Inputs (Clips), Outputs (Screens), FX chains and Routing.

## Clips

Capture Card, Generative, NDI, Spout or Video

Required for TOX
- "out" TOP - with content
- "params" Panel - Display Off - will show in sidebar.

## Screens

Need: window id, resolution, aspect ratio

## FX

Can be combined into sequential FX stacks and applied to either Clips or Screens.

Required for TOX
- "in" in TOP - input from the stack
- "out" out TOP - output to the stack

## Routing

This is a table of Clips to Screens. This allows each clip to be sent to 0, 1 or multiple screens.
