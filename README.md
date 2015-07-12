# DeepDream Music Video
These are some of the parameters used for generating the deepdream music video.  
Read more about the process on medium and watch the video on youtube.  
The [DeepDreamAnimator](https://github.com/samim23/DeepDreamAnim) was used to render/tune all animations.

![calista](https://i.imgur.com/iBGVPq1.jpg "calista")

## Parameters

**heavy face**  
python dreamer.py --input cali1 --output cali1/frames --octaves 5 --octavescale 1.8 --iterations 20 --jitter 32 --zoom 1 --stepsize 2 --blend 0.8 --layers inception_3b/output

**controlled face**  
python dreamer.py --input cali2 --output cali2/frames --preview 300 --octaves 6 --octavescale 1.4 --iterations 10 --jitter 32 --zoom 1 --stepsize 1.5 --blend 0.6 --layers inception_3b/output

**distored face**  
python dreamer.py --input cali3 --output cali3/frames --preview 300 --octaves 6 --octavescale 1.4 --iterations 15 --jitter 32 --zoom 1 --stepsize 1.5 --blend 0.8 --layers inception_4a/output

**heavy face cool**  
python dreamer.py --input cali4 --output cali4/frames --octaves 4 --octavescale 2 --iterations 20 --jitter 32 --zoom 1 --stepsize 2.5 --blend 0.8 --layers inception_3b/output

**wild face**     
python dreamer.py --input cali5 --output cali5/frames --octaves 5 --octavescale 1.7 --iterations 8 --jitter 32 --zoom 1 --stepsize 1.5 --blend 0.7 --layers inception_3b/output inception_4a/output inception_4b/output inception_4c/output

**volcano**  
python dreamer.py --input volcano --output volcano/frames --octaves 5 --octavescale 1.7 --iterations 13 --jitter 64 --zoom 1 --stepsize 0.7 --blend 0.8 --layers inception_3b/output inception_4a/output

**sky**   
python dreamer.py --input sky --output sky/frames --octaves 5 --octavescale 1.5 --iterations 2 --jitter 64 --zoom 1 --stepsize 2.6 --blend 0.7 --layers inception_4b/output inception_4b/output inception_3b/output

**face cali6**    
python dreamer.py --input cali6 --output cali6/frames --octaves 5 --octavescale 1.6 --iterations 10 --jitter 32 --zoom 1 --stepsize 1.5 --blend 0.6 --layers inception_4b/output

**atom 1**    
python dreamer.py --input atom2 --output atom2/frames --octaves 5 --octavescale 1.7 --iterations 12 --jitter 32 --zoom 1 --stepsize 1 --blend 0.87 --layers inception_3b/output

**atom 2**  
python dreamer.py --input atom --output atom/frames --octaves 5 --octavescale 1.5 --iterations 12 --jitter 64 --zoom 1 --stepsize 1.8 --blend 0.83 --layers inception_3b/output

**nuke 1**   
python dreamer.py --input nuke1 --output nuke1/frames --octaves 5 --octavescale 1.5 --iterations 12 --jitter 64 --zoom 1 --stepsize 1.8 --blend 0.83 --layers inception_3b/output

**nuke test**    
python dreamer.py --input nuke1 --output nuke1/frames --octaves 5 --octavescale 1.5 --iterations 5 --jitter 64 --zoom 1 --stepsize 1.2 --blend 0.8 --layers inception_3b/output

**flower1**    
python dreamer.py --input flower --output flower/frames --octaves 5 --octavescale 1.7 --iterations 15 --jitter 32 --zoom 1 --stepsize 2.5 --blend 0.7 --layers inception_3b/output

**flower2**   
python dreamer.py --input flower2 --output flower2/frames --octaves 4 --octavescale 1.8 --iterations 10 --jitter 32 --zoom 1 --stepsize 2.8 --blend 0.8 --layers inception_3b/output

**flower3**    
python dreamer.py --input flower3 --output flower3/frames --octaves 5 --octavescale 1.8 --iterations 10 --jitter 32 --zoom 1 --stepsize 2.2 --blend 0.8 --layers inception_3b/output

**club 2**    
python dreamer.py --input club2 --output club2/frames --octaves 6 --octavescale 1.4 --iterations 5 --jitter 32 --zoom 1 --stepsize 1.5 --blend 0.5 --layers inception_3b/output

**club 1 great**    
python dreamer.py --input club1 --output club1/frames --octaves 4 --octavescale 2 --iterations 5 --jitter 32 --zoom 1 --stepsize 1.5 --blend 0.7 --layers inception_3b/output inception_4a/output inception_4b/output inception_4c/output inception_4e/output inception_5a/output

**club 1 test**    
python dreamer.py --input club1 --output club1/frames --octaves 5 --octavescale 1.4 --iterations 8 --jitter 32 --zoom 1 --stepsize 1.5 --blend 0.7 --layers inception_3b/output inception_3b/output inception_4a/output inception_4b/output inception_4c/output inception_4e/output

**club 3**  
python dreamer.py --input club1 --output club1/frames --octaves 5 --octavescale 1.4 --iterations 5 --jitter 32 --zoom 1 --stepsize 2 --blend 0.8 --layers inception_3b/output inception_4a/output inception_4b/output inception_4c/output inception_4d/output inception_4e/output inception_5a/output inception_5b/output

**fractal**  
python dreamer.py --input cali4 --output cali4/frames --octaves 4 --octavescale 2 --iterations 13 --jitter 32 --zoom 1 --stepsize 2.5 --blend 0.7 --layers inception_3b/output
