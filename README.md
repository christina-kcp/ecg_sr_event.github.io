In general, the preferred sampling rate for recording
the Electrocardiogram(ECG) data as per industry standards is
roughly around 100 Hz to 400 Hz. Such high-resolution data is
critical considering the field of health and medicine. However,
high-resolution data is not always fit for direct transmission.
This is because the setup for high-resolution transmission is
quite expensive. Hence, it is always advised to transmit data in
compressed form. Once we have sent the data in compressed
format, the challenging task is at the receiver side of signal
reconstruction. This is because the receiver generally does not
have the information of the original sampling rate of the received
data. A network called as ECG-SRCNN is proposed here that is
used to reconstruct high-resolution ECG signal from it’s low-
resolution counterpart using the super-resolution concept. This
network performs fairly well upto an upscaling ratio of five,
with a Pearson Correlation Coefficient of 97%. Considering
the advantages of Deep Learning(DL) methods, deep-learning-
based approach was preferred for building a system for effective
reconstruction of ECG from low-resolution versions. In addition
to this, a 1-dimensional Convolutional Neural Network(1D-CNN)
is also proposed here to cater to the problem of cardiac
arrhythmia classification. This network performed quite well with
an accuracy of 99%. Here, this network has been able to classify
nine Cardiac Arrhythmia(CA) classes efficiently.
