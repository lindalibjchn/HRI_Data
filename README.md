# HRI Feature Data

Feature dataset for paper "Hmm, You Seem Confused! Tracking Interlocutor Confusion for Situated Task-Oriented HRI" pushished in HRI2023

We used four features to analyize our raw data, that is,
for facial frame data, feature analysis: facial emotion estimation, eye gaze estimation, head-pose estimation
for audio data, feature analysis: silence duriation time. 
Facial emotion categories: 0: 'Anger', 1: 'Disgust', 2: 'Fear', 3: 'Happiness', 4: 'Neutral', 5: 'Sadness', 6: 'Surprise'

In addition, we shared the speech transcripts in public groupped by conditions, and another speech transcript is the completing conversation from one participant with conditions (BAB).

If you refer to this feature data, please cite the paper. 

```
@inproceedings{10.1145/3568162.3576999,
author = {Li, Na and Ross, Robert},
title = {Hmm, You Seem Confused! Tracking Interlocutor Confusion for Situated Task-Oriented HRI},
year = {2023},
isbn = {9781450399647},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3568162.3576999},
doi = {10.1145/3568162.3576999},
abstract = {Our research seeks to develop a long-lasting and high-quality engagement between the user and the social robot, which in turn requires a more sophisticated alignment of the user and the system than is currently commonly available. Close monitoring of interlocutors' states, and we argue their confusion state in particular, and adjusting dialogue policies based on this state of confusion is needed for successful joint activity. In this paper, we present an initial study of human-robot conversation scenarios using a Pepper robot to investigate the confusion states of users. A Wizard-of-Oz (WoZ) HRI experiment is illustrated in detail with stimuli strategies to trigger confused states from interlocutors. For the collected data, we estimated emotions, head pose, and eye gaze, and these features were analysed against the silence duration time of the speech data and the post-study self-reported confusion states that are reported by participants. Our analysis found a significant relationship between confusion states and most of these features. We see these results as being particularly significant for multimodal situated dialogues for human-robot interaction and beyond.},
booktitle = {Proceedings of the 2023 ACM/IEEE International Conference on Human-Robot Interaction},
pages = {142–151},
numpages = {10},
keywords = {confusion detection, situated dialogues, user engagement, woz},
location = {<conf-loc>, <city>Stockholm</city>, <country>Sweden</country>, </conf-loc>},
series = {HRI '23}
}
```

