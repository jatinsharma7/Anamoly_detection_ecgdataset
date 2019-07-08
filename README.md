# Anamoly Detection using ECG dataset

Electrocardiogram (ECG) anomaly detection is an important technique for detecting dissimilar heartbeats which helps identify abnormal ECGs before the diagnosis process. Currently available ECG anomaly detection methods, ranging from academic research to commercial ECG machines, still suffer from a high false alarm rate because these methods are not able to differentiate ECG artifacts from real ECG signal, especially, in ECG artifacts that are similar to ECG signals in terms of shape and/or frequency.

Consider our 32-dimensional waveform space. Each point in this space represents a possible waveform segment. Similar segments will cluster together. The middle of each cluster (the centroid) will provide some measure of the prototypical waveform pattern that all those segments are specific instances of. (If this is difficult to visualise, the other way to consider it is that the centroid is simply an average of all waveform samples in that cluster.)
