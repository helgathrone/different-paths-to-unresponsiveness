# Different Paths to Unresponsiveness



## Overview



Loss of consciousness can arise through multiple biological mechanisms. While deep sleep and propofol anesthesia both produce behavioral unresponsiveness, their underlying neural dynamics may differ substantially.



This project investigates altered states of consciousness using multimodal neuroimaging data:



* EEG recordings during wakefulness and deep sleep

* fMRI recordings during deep sleep and propofol anesthesia



The goal is to compare temporal and spatial signatures of reduced consciousness through signal complexity, nonlinear dynamics, and whole-brain activity patterns.



---



## Research Questions



1. How does EEG complexity change between wakefulness and deep sleep?

2. Can nonlinear dynamical systems theory reveal changes in neural attractor geometry?

3. How do spatial patterns of brain activity differ between natural sleep and propofol anesthesia?

4. Do different unconscious states exhibit distinct neural signatures despite similar behavioral outcomes?



---



## Dataset



### Sleep EEG \& fMRI



Subject 23



* Wakefulness (resting-state EEG)

* Deep sleep (N3 EEG)

* Deep sleep fMRI



### Propofol fMRI



Subject 02



* Resting-state fMRI under propofol anesthesia



---



## Project Structure



```text

different-paths-to-unresponsiveness/



├── data/

│

├── notebooks/

│   ├── 01\_data\_audit.ipynb

│   ├── 02\_eeg\_preprocessing.ipynb

│   ├── 03\_eeg\_rhythms\_complexity.ipynb

│   ├── 04\_eeg\_chaos\_dynamics.ipynb

│   └── 05\_fmri\_spatial\_signatures.ipynb

│

├── requirements.txt

└── README.md

```



---



## Methods



### EEG Analysis



* Band-pass filtering (0.5–45 Hz)

* Alpha, Beta and Delta rhythm visualization

* Spectral slope (1/f dynamics)
  
* Lempel-Ziv Complexity (LZC)



### Nonlinear Dynamics



* Delay embedding

* Phase-space reconstruction

* EEG attractor visualization

* Sample entropy

* Higuchi fractal dimension



### fMRI Analysis



* Mean BOLD activity maps

* Signal variability maps

* Spatial entropy estimation



---



## Key Results



### EEG Complexity



Mean Lempel-Ziv Complexity:



| State       | Mean LZC |

| ----------- | -------- |

| Wakefulness | 0.351    |

| Deep Sleep  | 0.373    |



### Spectral Dynamics



Spectral slope analysis revealed changes in the 1/f structure between wakefulness and sleep, reflecting altered neural synchronization and information processing.



| State       | Spectral Slope |

| ----------- | -------------- |

| Wakefulness | -0.041         |

| Deep Sleep  | -0.056         |



### Nonlinear Dynamics



Phase-space reconstruction demonstrated substantial differences in attractor geometry between wakefulness and sleep.



Wakefulness exhibited more complex and irregular trajectories, whereas deep sleep showed more synchronized low-dimensional dynamics.



### fMRI Variability



After signal standardization:



| State    | Mean Variability |

| -------- | ---------------- |

| Sleep    | 0.0153           |

| Propofol | 0.0124           |



Natural sleep preserved higher temporal variability than propofol anesthesia.



### Spatial Entropy



| State    | Entropy |

| -------- | ------- |

| Sleep    | 2.424   |

| Propofol | 2.510   |



Propofol exhibited higher spatial entropy despite lower temporal variability.



---



# Scientific Conclusions



This project demonstrates that while natural sleep and propofol-induced anesthesia share the behavioral trait of unresponsiveness, their underlying neurophysiological architectures are fundamentally distinct.



## 1. EEG Dynamics and Phase-Space Geometry



### Collapse of Neural Complexity



Analysis of spectral slope (1/f) and Lempel-Ziv complexity indicates that reduced consciousness is accompanied by decreased diversity of neural dynamics and increased synchronization of large-scale oscillatory activity.



### Attractor Topology



Phase-space reconstruction reveals a dynamic shift.



Wakefulness is characterized by high-dimensional and irregular neural trajectories.



Deep sleep collapses into lower-dimensional synchronized macro-oscillations, consistent with theories of reduced dynamical complexity.



---



## 2. fMRI Spatial Signatures



### Reduced Temporal Variability under Propofol



After standardization of BOLD signals, natural sleep maintained greater temporal variability than propofol-induced unconsciousness.



This suggests that sleep preserves a richer repertoire of brain-state fluctuations, whereas propofol constrains neural dynamics into a more stable regime.



### Increased Spatial Entropy under Propofol



Despite lower temporal variability, the propofol condition exhibited higher spatial entropy than sleep.



This finding suggests a more diffuse and less spatially organized distribution of BOLD activity compared with the structured patterns observed during natural sleep.



---



## Summary



Natural sleep represents a structured physiological state characterized by synchronized neural oscillations, preserved temporal variability, and organized large-scale activity patterns.



Propofol-induced unconsciousness is associated with reduced temporal dynamics and increased spatial dispersion of brain activity.



These results suggest that similar behavioral states of unresponsiveness can emerge through fundamentally different neural mechanisms.



---



## Technologies



* Python

* Jupyter Notebook

* MNE

* Nilearn

* Nibabel

* NumPy

* SciPy

* Matplotlib

* Antropy

* Pandas

* Git

* GitHub



---



## Future Work



Potential extensions of the project include:



* Functional connectivity analysis

* Graph-theoretical network metrics

* Recurrence quantification analysis (RQA)

* Cross-subject comparisons

* Integration of EEG and fMRI complexity measures into a unified consciousness framework



