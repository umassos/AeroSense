# AeroSense: Sensing Aerosol Emissions from Indoor Human Activities

Paper (IMWUT 2024): https://dl.acm.org/doi/10.1145/3659593

Authors: Bhawana Chhaglani, Camellia Zakaria, Richard Peltier, Jeremy Gummeson, Prashant Shenoy

## Abstract
The types of human activities occupants are engaged in within indoor spaces significantly contribute to the spread of airborne diseases through emitting aerosol particles. Today, ubiquitous computing technologies can inform users of common atmosphere pollutants for indoor air quality. However, they remain uninformed of the rate of aerosol generated directly from human respiratory activities, a fundamental parameter impacting the risk of airborne transmission. In this paper, we present AeroSense, a novel privacy-preserving approach using audio sensing to accurately predict the rate of aerosol generated from detecting the kinds of human respiratory activities and determining the loudness of these activities. Our system adopts a privacy-first as a key design choice; thus, it only extracts audio features that cannot be reconstructed into human audible signals using two omnidirectional microphone arrays. We employ a combination of binary classifiers using the Random Forest algorithm to detect simultaneous occurrences of activities with an average recall of 85%. It determines the level of all detected activities by estimating the distance between the microphone and the activity source. This level estimation technique yields an average of 7.74% error. Additionally, we developed a lightweight mask detection classifier to detect mask-wearing, which yields a recall score of 75%. These intermediary outputs are critical predictors needed for AeroSense to estimate the amounts of aerosol generated from an active human source. Our model to predict aerosol is a Random Forest regression model, which yields 2.34 MSE and 0.73 r2 value. We demonstrate the accuracy of AeroSense by validating our results in a cleanroom setup and using advanced microbiological technology. We present results on the efficacy of AeroSense in natural settings through controlled and in-the-wild experiments. The ability to estimate aerosol emissions from detected human activities is part of a more extensive indoor air system integration, which can capture the rate of aerosol dissipation and inform users of airborne transmission risks in real time.


## Reference

BibTeX Reference:
```
@article{chhaglani2024aerosense,
  title={AeroSense: Sensing Aerosol Emissions from Indoor Human Activities},
  author={Chhaglani, Bhawana and Zakaria, Camellia and Peltier, Richard and Gummeson, Jeremy and Shenoy, Prashant},
  journal={Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies},
  volume={8},
  number={2},
  pages={1--30},
  year={2024},
  publisher={ACM New York, NY, USA}
}
```



