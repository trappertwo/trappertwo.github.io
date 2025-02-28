## Detecting Depression using Speech Processing

![cover image](/images/cosmos-copy.png)

I'm excited to share the final poster for the project I did at UCLA's COSMOS program this summer as part of Cluster 6: From Medicine to Hollywood: Artificial Intelligence for Speech and Imagery. In this project, we focused on developing an AI model that can help identify depression from audio samples of a person's voice. Improving this kind of technology to a point where it could reliably be used in actual healthcare situations would have the capacity to help a lot of people get the treatment they need, so my partner and I set out to engineer such a model. 

We employed the DAIC-WoZ dataset, a set of audio responses to clinical interview questions asked by an animated virtual interviewer (hence the WoZ: Wizard-of-Oz). We chose to try two different approaches: gradient boosting, a method that aggregates several "weak" models to make an inference, and a convolutional neural network, an architecture used for extracting features from images (the images in question were mel-spectrograms, image representations of vocal samples).

We found that some audible features, such as lower pitch and slower talking speed, and some non-audible features indicated that a person may have depression from their voice. In the end, our gradient boosting model had a better accuracy of 73%. Working on this project was an amazing chance to get hands-on experience working with developing AI models. I hope to explore this subject and areas like this in the future.

Check out the full poster for more details!
