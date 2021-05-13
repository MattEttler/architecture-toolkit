## Overview

A blob of tips, tricks, observations, and techniques I have picked up while learning how to plan, and communicate those plans.

### Tips and Tricks
#### Planar Embedding
Having trouble with keeping a clean flow to your view?
Check if your graph is Planar Embeddable:
```
E = edges
V = vertices
 
planar_embeddable = E <= 3V-6 
```
If it is, it means you can diagram it with zero bends. This will help reduce visual complexity in your view.

#### Models
Models should be preferred over pictures.
ArchiMate is a very strong option when it comes to modelling.
It offers the ability to model relationships once, and create many different view.

### Observations

An ideal schematic must be a planar embeddable graph.
An ideal schematic must have only has straight edges.
An ideal schematic must be a visually literal representation of its information.
circuit angles must be uniform.
edge labels should the top-left of an edge.
vertices lightly-prefer to be uniformly denser than sparse. 
Every time you put a kink in an edge, you are adding extra information that does not add to the functional .
