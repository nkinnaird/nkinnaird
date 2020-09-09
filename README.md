### Welcome!

My name is Nick Kinnaird. I am a physics PhD working as Postdoctoral Research Associate at Boston University. I have a large amount of data analysis and software development experience which I've gained as a graduate student and now postdoc while working on the Fermilab Muon <i>g − 2</i> physics experiment. Below you'll find some links to repositories for code I've written for various projects within the experiment. My [`Dissertation`](https://github.com/nkinnaird/Dissertation) in particular includes the results of much of my work. Please feel free to reach out to me if you have any questions or just want to chat about the work I've done!



#### 2. [`GeaneTracking`](https://github.com/nkinnaird/GeaneTrackingCode) is the codebase (primarily C++) for a track fitting algorithm utilizing $\chi^{2}$ minimization and error propagation.

I developed a track fitting algorithm and implemented it into a larger track reconstruction framework as one of the first members of the 'Tracking Team' on the Fermilab Muon Muon <i>g − 2</i> experiment. This track fitting algorithm essentially combines separate hits across a detector into a single track, and then uses that information to relay information about the performance and conditions of the experiment. The track fitting algorithm fits large amounts (TBs) of incoming data with high fidelity to provide vital telemetry for the experiment, and is still in use today. The algorithm was developed and tested with Monte Carlo simulations and statistically verified before its implementation into the larger framework and put into production. A separate repository containing the [`Documentation`](https://github.com/nkinnaird/Geane-Documentation) can be found which details the algorithm and it's implementation.

The main infrastructure and flow of the track fitting is shown below, along with a sample fitted track that the algorithm was successfully applied to.

<div style="text-align:left"><img src="https://github.com/nkinnaird/Geane-Documentation/blob/master/Images/TrackingFlow/NewGeaneFittingFlow.png" height="250" /></div> <div style="text-align:right"><img src="https://github.com/nkinnaird/Dissertation/blob/master/KinnairdThesis/Body/Figures/TrackingFigures/Tracks/SampleTrack.png" height="250" /></div>




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
