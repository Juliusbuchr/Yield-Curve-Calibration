# Yield Curve Calibration and Interpolation

This repository contains a Python script designed to calibrate the continuous term structure of zero-coupon bond (ZCB) spot rates using market data from instruments like EURIBOR, Forward Rate Agreements (FRA), and interest rate swaps. The calibration is performed with the **Fixed Income Derivatives** local library, and the results are visualized through plots of the spot and forward rates.

## Features

- **Calibration of Zero-Coupon Bond Spot Rates**: The script fits the ZCB curve based on market data.
- **Interpolation of Rates**: The ZCB curve is interpolated to obtain spot and instantaneous forward rates.
- **Visualization**: Plots of the calibrated spot and forward rates are generated.

## Requirements

- **FIDLIB**: A local financial library used for curve fitting and interpolation.
- Python packages:
  - `numpy`
  - `matplotlib`
  - `pandas`
