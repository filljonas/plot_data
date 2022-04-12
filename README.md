# Plot data

This repository contains the data needed to create the plots of
*Producing accurate hydrological distributional predictions using Bayesian long-short term memory networks* in order to
enable reviewers and readers to reproduce the plots.

## Usage

One can load the data into a Python-dictionary named *data* using the following code:

```
file_name = 'fig05.pickle'
    with (open(file_name, 'rb')) as f:
        data = pickle.load(f)
```

This dictionary contains descriptive key names for various data contained in the plots. We present the different
dictionary keys per plot:

### fig04

- *date_range*: x-axis (dates in daily resolution)
- *obs*: Observations
- *preds_means*: Model predictions
- *lower_bound*: Lower bounds of prediction interval
- *upper_bound*: Upper bounds of prediction interval

### fig05

- *steps*: x-axis (training steps)
- *p_factor*: average P-factor-values for training steps

### fig07

- *date_range*: x-axis (dates in hourly resolution)
- *obs*: Observations
- *preds_means*: Model predictions
- *lower_bound*: Lower bounds of prediction interval
- *upper_bound*: Upper bounds of prediction interval
- *larsim*: LARSIM-simulations

### fig08

- *date_range*: x-axis (dates in daily resolution)
- *obs*: Observations
- *preds_means*: Model predictions
- *lower_bound*: Lower bounds of prediction interval
- *upper_bound*: Upper bounds of prediction interval
- *larsim*: LARSIM-simulations