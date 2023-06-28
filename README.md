# PyOpenTS
PyOpenTS is a library specifically designed to integrate methods and modules for time series. Its purpose is to allow users of this library to call and modify time series modules in a simpler and more convenient way. By using PyOpenTS, you can simplify the time series code process and reliably provide time series related module functions.  

## Our Goal
Our goal is to simplify the process of handling time series code so that users can more easily tackle various time series problems. Whether you are a data scientist, an engineer, a researcher, or someone interested in time series, PyOpenTS will be a powerful tool for you.  

## Features
* A clean API for quickly calling and modifying time series modules
* Provides a range of methods and models for time series analysis, including but not limited to forecasting, clustering, classification, etc. 
* Continuous updates and improvements to meet user needs  

## example 

```
from opents.data import datasets

# load ucr and generate dataloader
ucr_dataset = datasets.UCRDataset(dataset_name="Chinatown",dataset_root_path='UCR')
train, train_label, test, test_label = ucr_dataset.load()
```

## Future Plans
We will continue to update and improve PyOpenTS and gradually add some demo usage methods to show how to use this library. Please stay tuned for our updates.

## How to Get Help
If you encounter any problems during use, feel free to submit them to Issues. We also welcome your suggestions for improving PyOpenTS. We hope that PyOpenTS can become a powerful assistant for you in dealing with time series problems.