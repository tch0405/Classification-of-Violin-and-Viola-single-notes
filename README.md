# Classification-of-Violin-and-Viola-single-notes

The purpose of this small project is to find whether additional audio features such as zero crossing rate, spectral bandwidth, spectral centroid, spectral rolloff as well as spectral flatness will increase the accuracy of classifying violin and viola single notes to some extent. 

The dataset used is the sound samples from [Philharmonia](https://philharmonia.co.uk/resources/sound-samples/). The selected files used consist of the overlapping notes of both violin and viola, ranging from G3 to D sharp 4 with different dynamics such as vibrato, staccato, and so on. The selected audio files can be accessed via [here](https://drive.google.com/drive/folders/1RHzjLUj4yVSEXTNVCpCcgJW5w00lX1G4?usp=sharing).

The result has shown the additional features adopted will increase the classification accuracy to a small extent. The accuracy of using merely MFCCs is <strong>0.9669421487603306</strong> while the accuracy of using MFCCs and other features is <strong>0.9724517906336089</strong>.
