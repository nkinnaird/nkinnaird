### Welcome!

My name is Nick Kinnaird. I am a physics PhD working as Postdoctoral Research Associate at Boston University. I have a large amount of data analysis and software development experience which I've gained as a graduate student and now postdoc while working on the Fermilab Muon <i>g − 2</i> physics experiment. Below you'll find some links to repositories for code I've written for various projects within the experiment. My [`Dissertation`](https://github.com/nkinnaird/Dissertation) in particular includes the results of much of my work. Please feel free to reach out to me if you have any questions or just want to chat about the work I've done!

#### 1. [`PrecessionFrequencyAnalysis`](https://github.com/nkinnaird/PrecessionFrequencyAnalysis) is the codebase (C++, C, bash) for a high precision frequency analysis project and associated systematic and statistical evaluations.

One primary component of the Fermilab Muon Muon <i>g − 2</i> experiment is the extraction of a specific so-called 'precession' frequency from large amounts (PBs) of data to high precision. As one of the lead analyzers for the first data-taking period of the experiment, I developed code which fit the data in a specific way which reduced systematic biases, while including physical and mathematical models. As part of the project I conducted many statistical and systematic evaluations on the data and results of the fits in order to verify the understanding of the data and provide an understanding of any errors in the extracted frequency. Lastly, I conducted many smaller toy Monte Carlo projects in order to develop my understanding of the real, sometimes messy, data in a clean environment.

Below is an image containing the final (blinded) fits to the four datasets gathered in the first data-taking period of the experiment, where the precision on the extracted frequncies are sub-parts-per-million (ppm), as well as a plot of the fit residuals and associated FFT for one of the datasets.

<!--
<div style="text-align:left"><img src="https://github.com/nkinnaird/PrecessionFrequencyAnalysis/blob/master/PlotsForReadme/DatasetRatioFits.png" height="400" /></div> 
-->

<p float="left">
  <img src="https://github.com/nkinnaird/PrecessionFrequencyAnalysis/blob/master/PlotsForReadme/DatasetRatioFits.png" height="250" />
  <img src="https://github.com/nkinnaird/PrecessionFrequencyAnalysis/blob/master/PlotsForReadme/FitResidualFFT.png" height="250" />
</p>



#### 2. [`GeaneTracking`](https://github.com/nkinnaird/GeaneTrackingCode) is the codebase (primarily C++) for a track fitting algorithm utilizing <img src="https://render.githubusercontent.com/render/math?math=\chi^{2}"> minimization and error propagation.

I developed a track fitting algorithm and implemented it into a larger track reconstruction framework as one of the first members of the 'Tracking Team' on the Fermilab Muon Muon <i>g − 2</i> experiment. This track fitting algorithm essentially combines separate hits across a detector into a single track, and then uses that information to relay information about the performance and conditions of the experiment. The track fitting algorithm fits large amounts (TBs) of incoming data with high fidelity to provide vital telemetry for the experiment, and is still in use today. The algorithm was developed and tested with Monte Carlo simulations and statistically verified before its implementation into the larger framework and put into production. A separate repository containing the [`Documentation`](https://github.com/nkinnaird/Geane-Documentation) can be found which details the algorithm and it's implementation.

The main infrastructure and flow of the track fitting is shown below, along with a sample fitted track that the algorithm was successfully applied to.

<p float="left">
  <img src="https://github.com/nkinnaird/Geane-Documentation/blob/master/Images/TrackingFlow/NewGeaneFittingFlow.png" height="250" />
  <img src="https://github.com/nkinnaird/Dissertation/blob/master/KinnairdThesis/Body/Figures/TrackingFigures/Tracks/SampleTrack.png" height="250" />
</p>




<!--
**nkinnaird/nkinnaird** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

<div style="text-align:left"><img src="https://github.com/nkinnaird/Geane-Documentation/blob/master/Images/TrackingFlow/NewGeaneFittingFlow.png" height="250" /></div> 



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
