# Content Masked Loss 

Peter Schaldenbrand, Jean Oh<br/>
Carnegie Mellon University<br/>
2021

## AAAI'21 [arXiv pre-print](https://arxiv.org/abs/2012.10043)

Human-Like Brush Stroke Planning in a Reinforcement Learning Painting Agent. 


### Download Pre-Trained Models
The actor and renderer models can be downloaded from this box account.
https://cmu.box.com/s/ojydzfocwjhbm4tsjbgt4ju5uwd6013c

### Generating Strokes for Robot Painting Arm
Run the `generate_actions.py` script on your desired image, and the brush stroke instructions will be found in .csv files in a directory named /arduino_actions.
```
$ python generate_actions.py --img=[image to paint] --max_step=[number of brush strokes] \
--actor=pretrained_models/cml1/actor.pkl --renderer=renderer_constrained.pkl
```
