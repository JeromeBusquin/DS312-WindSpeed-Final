# DS312-WindSpeed-Final

# Wind Speed Prediction

This repository provides a quick demonstration of retrieving a small ERA5 dataset, preprocessing it, and training a simple LSTM model for next-day wind speed prediction over a small region in Arizona.

## Requirements

- Python 3.x
- [CDS API](https://cds.climate.copernicus.eu/api-how-to) (requires registration)
- pip packages:  
  - `os`
  - `cdsapi`
  - `xarray`
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `tensorflow` (including `tensorflow.keras`)
  - `matplotlib`
  - `math`

You can install these by running:
```bash
pip install cdsapi xarray numpy pandas scikit-learn tensorflow matplotlib
