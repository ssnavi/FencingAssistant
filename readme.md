# Fencing Co Pilot
Transforming sports performance through AI Co-pilot helping students and coaches progress towards identified skill goals. 

This is a deep learning based sports coaching assistant. It aims to help students and coaches in identification of issues and tracking their progress towards identified goals. 
Our initial focus is on fencing, running it for a) en guard position b) gait analysis and c) the motion of advancing. Based on the videos, AI models will auto-generate scores 
for the position under evaluation that can be reviewed by the coach (hence co-pilot mode) for further action.

### Phase 1: Given any image, identify fencing as a sport
- work covered in imagenet tuner folder
### Phase 2: For a video identify the enguard position
- use frames of videos as input for movenet
- work covered in movenet tuner folder
### Phase 3: Do gait analysis of enguard position
- determine whether given frame of fencer demonstrates correct posture or not
### Phase 4: Do gait analysis of multiple fencers at once
- during footwork, use frame of multiple fencers to see who has correct posture 
### Phase 5: Do gait analysis on a fencing drill video
- work covered in movienet tuner folder
- determine who has right posture during multiple advances forward
### Phase 6: Plug in to a live video stream and do real time gait analysis
- real time analysis of footwork drills
### Phase 7: Identify advance action with hand in a live frame
- analysis of action with multiple elements
### Phase 8: Identify fencers engaging in a live frame
- during basic drills (suited up), identify fencers 
### Phase 9: Identify frames of action in a live video
- identify where fencers are engaging, i.e. attacks or parrys
### Phase 10 : Do analysis of major fencing actions. Project will be expanded once we reach here.
