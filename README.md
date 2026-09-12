# ASPGD
SLM phase optimization code used in Complex wavefront engineering via a dual-plane architecture. 
Paper link: https://arxiv.org/abs/2605.14468

The ASPGD algorithm is an implementation of Adaptive Stochastic Parallel Gradient Descent (ASPGD) algorithm from T. Shi, Y. Cheng, X. Du, J. Chen, and C. Ji, “Improved SPGD algorithm for optical phased array chip phase error correction in Lidar applications,” Appl. Opt., AO, vol. 64, no. 5, pp. 1206–1215, Feb. 2025, doi: 10.1364/AO.541168.

Dependencies:
>= Python v3.11.5

Install time:
< 1 hour

Run time:
< 5 minutes

Instructions:
Run all the cells in the notebook to generate a far-field hologram of a letter given in HOLOGRAM_LETTER.

By default HOLOGRAM_LETTER is set as ’T’. Therefore program will generate a far-field hologram of the letter ’T’ using the ASPGD algorithm.

How to run this in your experiment:
Presently the code uses a dummy function propagate_beams, which for real-world applications should be replaced with your camera’s capture function.
