# EMOT
A new way to analyse computer mouse trajectories

# Publication
Calcagnì, A., Lombardi, L., & Sulpizio S. (2017). Analysing spatial data from mouse tracker methodology: An entropic approach. Behavior Research Methods, 49(6), 2012-2030

# About
EMOT is a Matlab package implementing a new methodology for modeling computer-mouse trajectories in a data-driven perspective and allows researchers to analyse raw x-y trajectories in terms of dynamic and static components.  It is based on an information-theoretic framework, where a set of entropy-based measures is used to quantify the spatial information in the empirical data. Movement features present in empirical trajectories, such as location, direction, and space exploration are extracted adopting an original entropy decomposition.  EMOT offers a robust methodology in case of noisy trajectories due to uneven movements of the cursor and can work with raw x-y trajectories registered with any recording software. 

EMOT analyses the spatial information of computer-mouse trajectories conveyed by cognitive processes in choice/decision tasks. Unlike other methodologies, EMOT extracts dynamic features of the hand-movement by looking at trajectories in terms of fast movements and motor pauses.

In a two-choice categorization task hand-movements reveal several scenarios involving different cognitive processes. Fast movements represent those motor sub-processes executed after a decision has been made. By contrast, motor pauses unfold sub-processes related with decisional conflicts in categorization, decisional uncertainty, goal formulation and/or reformulation.

EMOT analyses trajectories in a single-trial fashion. The noisy x-y trajectory is initially transformed into distances and angles. Next, movement features like location, directions, and amplitudes are modeled in terms of a histogram model.

The histogram model is used to determine a quantification of spatial events involved in the original movement path (e.g., competition between competing and target cues, attraction of competing cue) in terms of fast movements and motor pauses. The quantification is solved adopting a Non-linear Programming (NLP) approach with a Cumulative Residual Entropy (CRE) decomposition.
