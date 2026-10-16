# Signal Processing

The analysis pipeline combines spectral and cross-channel methods.

## Processing methods

The project uses frequency-domain analysis, candidate-frequency tracking, Welch coherence, signal-to-noise metrics and metadata describing proximity to known artifacts.

Parabolic sub-bin interpolation is used when tracking candidate peaks so that frequency evolution can be studied more precisely than simply selecting the largest FFT bin.

## Cross-channel coherence

Coherence between sensor channels is useful for asking whether two measurement points share a signal component. The analysis also accounts for the coherence bias floor associated with the number of Welch segments.

## Time trends

Long-running acquisition makes it possible to compare day/night behavior and responses around interventions such as watering. These trends are treated as hypotheses to test, not as biological attribution by themselves.
