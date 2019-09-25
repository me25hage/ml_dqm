This is a collection of Jupyter Notebooks to test various models and normalization strategies to monitor trigger rates as a signal of detector health.

## Old
Outdated models that are replaced in other folders.

## average
Models that take single HLT paths as input and normalize the rates to the average in the entire run.

## cnorm
Models that take single HLT paths as input and normalize the rates by a constant to make all of the rates have approximately the same value.

## normedWindow
Models that use the model format but normalize all trigger rates to be between 0 and 1.

## pileupInput
Models that include pileup number as an input along with the trigger rates.

## pileupNorm
Data is normalized to the pileup number at that moment in data collection.

## rateAverage
Data is normalized to the average of the rate of the specific HLT paths. This also includes Pileup being added as an input in the bottleneck and inner layers.

## unscaledWindow
Data is unnormalized and uses the window of time method.
