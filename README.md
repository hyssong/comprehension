# comprehension

**Song, H., Park, B.-Y., Park, H., Shim, W.M. (2020) Cognitive and neural state dynamics of narrative comprehension**

Data repository for two behavioral experiments and movie annotation (saved in .mat files).<br>
Raw FMRI data lies in openneuro.org/XX.

**1. "ahaoops": Behavioral experiment 1: Reports on the subjective moments of comprehension**
  - time of button press: 0-600s
  - participant ID: N=20 per movie
  - response type: 1=aha, 2=oops

**2. "causalrelationship": Behavioral experiment 2: Rating causal relationship between narrative events**
  - causal_mat: all participants' sum of causal relationship scores of the scrambled movie (N=12 per movie, 600s)
  - id: scene ID from physical scrambling
  - scram2raw: un-scrambling index (i.e., causal_mat(scram2raw, scram2raw) = causal relationship of the original movie)

**3. "annotation": Movie annotation**
  - 300 sentences: annotation per 2 sec of the scrambled movie
  - minimally processed: lemmatized, stop words removed, punctuations removed, lowercased

**Movie stimuli**<br>
  Three 10 min movies that were segmented (36+/-4s) and scrambled in their temporal sequence
  - *Cops* (1922, Keaton & Cline)
  - *The Kid* (1921, Chaplin)
  - *Mr. Bean: The Animated Series, Art Thief* (season 2, episode 13; 2003, Fehrenbach)
