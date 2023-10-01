This Vocal Tract Length Perturbation (VTLP) algorithm is adopted from Edward Ma’s python library in natural language processing augmentation (https://nlpaug.readthedocs.io/en/stable/_modules/nlpaug/augmenter/audio/vtlp.html). 

This augmenter applied VTLP to all .wav files in the directory path folder with warp factor between 0.9 and 1.1 with the whole duration being augmented. 

The trial with a warping factor of 1.1 resulted to a WER of **16.00%** and was proven to be effective in addressing the issue of speaker variability.
