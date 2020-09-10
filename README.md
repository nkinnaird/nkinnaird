### Welcome!

My name is Nick Kinnaird. I am a physics PhD working as Postdoctoral Research Associate at Boston University. I have a large amount of data analysis experience which I've gained as a graduate student and now postdoc while working on the Fermilab Muon <i>g − 2</i> physics experiment. I've worked on all stages of the experiment, all the way from commissioning the experiment when gathering the first data, to processing and cleaning the data, and finally to analyzing the data and reporting the results.

Below you'll find some links to repositories for a couple of key projects I developed within the experiment. My [`Dissertation`](https://github.com/nkinnaird/Dissertation) in particular includes the results of much of my work. Please feel free to reach out to me if you have any questions or just want to chat about the work I've done.

#### [`PrecessionFrequencyAnalysis`](https://github.com/nkinnaird/PrecessionFrequencyAnalysis) is the codebase (C++, C, bash) for a high precision frequency analysis project, and associated systematic and statistical evaluations.

One primary component of the Fermilab Muon Muon <i>g − 2</i> experiment is the extraction of a specific so-called 'precession' frequency from large amounts (PBs) of data to high precision. As one of the lead analyzers for the first data-taking period of the experiment, I developed code which fit the data with physical and mathematical models in a specific way which reduced systematic biases. As part of the project I conducted many statistical and systematic evaluations on the data and the results of the fits. As part of the project I also conducted many smaller toy Monte Carlo simulations in order to help develop my understanding of the real, sometimes messy, data in a clean environment.

Below is an image containing the final (blinded) fits to the four datasets gathered in the first data-taking period of the experiment, where the precisions on the extracted frequncies are sub-parts-per-million (ppm). Also included is a plot of the fit residuals and associated FFT for one of the datasets.

<!--
<div style="text-align:left"><img src="https://github.com/nkinnaird/PrecessionFrequencyAnalysis/blob/master/PlotsForReadme/DatasetRatioFits.png" height="400" /></div> 
-->

<p float="left">
  <img src="https://github.com/nkinnaird/PrecessionFrequencyAnalysis/blob/master/PlotsForReadme/DatasetRatioFits.png" height="250" />
  <img src="https://github.com/nkinnaird/PrecessionFrequencyAnalysis/blob/master/PlotsForReadme/FitResidualFFT.png" height="250" />
</p>



#### [`GeaneTracking`](https://github.com/nkinnaird/GeaneTrackingCode) is the codebase (primarily C++) for a track fitting algorithm utilizing <img src="https://render.githubusercontent.com/render/math?math=\chi^{2}"> minimization and error propagation.

I developed a track fitting algorithm and implemented it into a larger track reconstruction framework as one of the first members of the 'Tracking Team' on the Fermilab Muon Muon <i>g − 2</i> experiment. This track fitting algorithm essentially combines separate hits across a detector into a single fitted track. The track fitting algorithm then fits large amounts (TBs) of incoming data for many tracks with high fidelity to provide vital telemetry for the experiment, and is still in use today. The algorithm was developed and tested with Monte Carlo simulations, and statistically verified before its implementation into the larger framework and put into production. A separate repository containing the [`Documentation`](https://github.com/nkinnaird/Geane-Documentation) can be found which details the algorithm and it's implementation.


The main infrastructure and flow of the track fitting code is shown below, along with a sample fitted track that the algorithm was successfully applied to.

<p float="left">
  <img src="https://github.com/nkinnaird/Geane-Documentation/blob/master/Images/TrackingFlow/NewGeaneFittingFlow.png" height="225" />
  <img src="https://github.com/nkinnaird/Dissertation/blob/master/KinnairdThesis/Body/Figures/TrackingFigures/Tracks/SampleTrack.png" height="225" />
</p>




<!--
**nkinnaird/nkinnaird** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
