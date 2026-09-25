Hi! I’m a third-year PhD researcher at the [Centre for Digital Music](https://c4dm.eecs.qmul.ac.uk/) at Queen Mary University of London.

My research focuses on **grey-box modelling of musical instruments**, particularly differentiable digital signal processing and the optimisation of digital waveguide models.

Also: I am currently doing a research visit the Aalto Acoustics Lab in Helsinki with Vesa Välimäki. I will be here until mid-November, so stay tuned for interesting collaborations :) 

## Selected research

- **[Differentiable Karplus–Strong — DMRN 2020](https://ptablasdpaula.github.io/DiffKarplusStrong_DMRN20/)**  
  A differentiable time-domain implementation of the Karplus–Strong algorithm. I optimised its parameters against real-world recordings using gradient descent and compared the results with a genetic algorithm.

- **[Four Decades of Digital Waveguide Synthesis — JAES](https://aes.org/publications/elibrary-page/?id=23382)**  
  A comprehensive review of the history and development of digital waveguide synthesis, co-authored with several pioneers of the field.

- **[Sound-Matching with a Differentiable Karplus–Strong — DAFx 2026](https://ptablasdpaula.github.io/DAFx26-Karplus/)**  
  An extension of my earlier Karplus–Strong work introducing an event-based DDSP architecture, in which individual notes have independently optimisable pitch and onset-time parameters.

- **[Cumulative Energy Losses — ICASSP 2027 submission](https://github.com/ptablasdpaula/ICASSP27-Phrase)**  
  A new family of loss functions—*Cumulative Energy Losses* (CeLs)—designed to provide well-behaved gradients for the joint optimisation of pitch, timing, and timbre. In our plucked-string phrase experiments, CeLs outperformed all evaluated alternatives while remaining computationally much closer to a single-scale STFT loss than to a multi-scale spectral loss.

Feel free to explore the projects, fork the code, or reach out if you’re interested in collaborating!
