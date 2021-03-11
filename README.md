# deepfake_detection

University of Chicago Master's of Science in Analytics Winter 2021 Capstone
This web dashboard processes videos using a custom pipeline to analyze sequences of video frames for deepfake media.  The model powering the detection consists of two image classifiers ensembled with a meta-learner which then pass embedding vectors into an LSTM model for real/fake classification along with classification probabilities.  Additionally, GradCAM is offered to the user for model interpretability.
