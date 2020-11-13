# SeniorProjectII

This program uses several different raw audio files to produce compressed sound for the user. We will be building out six Convolutional Neural Networks (CNN’s) for each of the six parameters of compression. Compression will be done through the six different parameters of audio signal processing which are: 


Threshold: Determines the level at which the compressor starts compressing

Ratio: Once the sound from the raw audio file exceeds the Threshold, the Ratio is what we use to level the sound

Attack: Determines how quickly it pulls the input signal down to the full ratio value when it exceeds the threshold

Release: Represents the total time it takes for the signal to return to an uncompressed state

Knee: Determines the character of the gain that is applied to the signal

Makeup Gain: When you want your raw audio file to sound louder
