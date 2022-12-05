# identification-control-epileptiform-activity

This repository was created to meet the submission requirements of PLOS Computational Biology for the work entitled: "Epileptic seizure suppression: a computational approach for identification and control using real data".

It contains all codes written by the authors that generated the results present in the aforementioned paper, in .py format (developed in Python, on the Spyder plataform). A brief description is as follows:

i) epilepsy_signals.py: imports the signals used for analysis, applies both band and notch filters and plots both unfiltered and filtered activity; ii) AR_models_epilepsy.py: obtains autoregressive models for sequential windows of the previously imported signals and saves the coefficients in .txt files; iii) multiple_models_AR_epilepsy.py: imports the previously created .txt files and creates both discrete and continuous state-space models; iv) LMI_multiple_models_AR_epilepsy_obs.py: designs the state observer based on the gains of the multiple AR models; v) LMI_multiple_models_AR_epilepsy_ctrl.py: designs the controllers based on the gains of the multiple AR models; vi) epilepsy_rk4_feedback_control_baseline.py: imports both gains, applies both observer and controller to the previously imported signals and performs statistical analysis on the results.  

The real electrophysiological activity analyzed will be available upon request. 

For further information, please contact: jean.faber@unifesp.br or ferres.brogin@unesp.br.
