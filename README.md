# STROTSS
Style Transfer by Relaxed Optimal Transport and Self-Similarity

This project is based on https://github.com/nkolkin13/STROTSS

# Slides of presentation

https://docs.google.com/presentation/d/1TWtte-P4NktXqOqJRQit_UgS-iievxpIjZdByPEVEhc/edit?usp=share_link

# Our numerical experiments

We've tested the influences of different loss by keeping only the corresponding term in the objective function. Additionally, if we only keep the content loss and the palette matching loss, this method will perform the colour transfer. In terms of implementation, user can just comment the corresponding term in the ```gen_remd_dp_objective_guided()```  of ```style_objectives.py```.

Usage: 

```
#python3 styleTransfer.py {PATH_TO_CONTENT} {PATH_TO_STYLE} {CONTENT_WEIGHT} {MAX_SCALES} {OUTPUT_PATH}
```
