# Fencing Co Pilot
Transforming sports performance through AI Co-pilot helping students and coaches progress towards identified skill goals. 

This is a deep learning based sports coaching assistant. It aims to help students and coaches in identification of issues and tracking their progress towards identified goals. 
Our initial focus is on fencing, running it for a) en guard position b) gait analysis and c) the motion of advancing. Based on the videos, AI models will auto-generate scores 
for the position under evaluation that can be reviewed by the coach (hence co-pilot mode) for further action.

### Track 1: Given any image, identify fencing as a sport
- input: image of any sport
- output: correct classification of fencing image
  ### section 2: Do classification of major fencing actions. 
  - input: given video of fencing lunge, fleche, parry
  - output: is able to identify what each action is
  ### section 3: identify correctness of actions in video
  - input: given video of fencing lunge, fleche
  - output: is able to identify whether the action is being done correctly
  - factors: hand before leg, distance reached with action, posture
### Track 2: For a video identify the enguard position
- use frames of recorded videos as input for movenet
- output: correct classification of a frame as the fencer being in en gaurd position
  ### section 2: Do gait analysis of enguard position
  - input: frame of fencer in en gaurd position
  - output: determines whether given frame of fencer demonstrates correct posture or not
  ### section 3: Do gait analysis of multiple fencers at once
  - during footwork, use frame of multiple fencers to see who has correct posture
  - input: frame of group class in en gaurd position during footwork
  - output: determines who has correct posture and who does not
  ### section 4: Do gait analysis on a fencing drill video
  - input: video of group class footwork during advances forward
  - output: determines who maintains right posture
  ### section 5: Plug in to a live video stream and do real time gait analysis
  - input: real time video of group class footwork
  - output: analyzes who maintains correct posture
  ### section 6: Identify advance action with hand in a live frame
  - analysis of action with multiple elements
  - input: real time group class footwork doing advance with extension of arm
  - output: analyzes whether hand is moving before foot and for who
  ### section 7: Identify fencers engaging in a live frame
  - input: real time drills (suited up)
  - output: identifies bodies of fencers during drills 
  ### section 8: Identify frames of action in a live video
  - input: real time fencing
  - output: identifies where fencers are engaging, i.e. attacks or parrys
