# Echolalia_detection
Repository for my Master's Thesis 'Automatic detection of echolalic speech in children with Autism Spectrum Disorder'
1.A: Transcription models, adapted from Whisper Timestamped (with and without prior speaker diarization) (cf. Section 4.3.2)
1.B: Transcription-based echolalia and self-repetition detection models (cf. Section 4.4.1)
1.C: Audio-based echolalia and self-repetition detection models (cf. Sections 4.4.2+ 4.5):
  •	Training and testing procedures of both models, on the basis of extracted features (for procedure of feature extraction: see final models)
  •	Final models, that include feature extraction, classification by the trained classifier and output of predictions in pandas DataFrame + .TextGrid
