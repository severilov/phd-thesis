# phd-thesis

# Decoding speech from non-invasive brain recordings

![logo](./audio_brain)

We aim to decode speech from the brain activity recorded with magnetoencephalography (MEG) or electroencephalography (EEG) while they listen to stories and/or sentences. For this, our model extracts the deep contextual representations of speech signals (Y) from a pretrained self-supervised model (wav2vec 2.0: Baevski et al. [2020]) and learns the representations Z of the brain activity on the corresponding window (X) that maximally align with these speech representations with a contrastive loss (CLIP: Radford et al. [2021])

