# VAE-LSTM-code-and-data
## Project Overview
This project aims to predict spring flow by using Variational Autoencoder (VAE) for precipitation data augmentation and then inputting the enhanced data into deep learning models such as LSTM.
## Project Structure
### Directory Structure Explanation
- data folder: Contains original data, enhanced data, and specific calculation results for various figures and tables in the paper.
- Various formulas folder: Includes calculation formulas for various indicators.
- 3-6 folders:
    - VAE code: Contains code related to VAE.
    - other models: Contains code for other models.
    - VAE-LSTM End to end model: Contains the main logic code and pre-trained weights for the VAE-LSTM end-to-end model.
    - other dl model: Contains adjusted model logic code and pre-trained weights for other deep learning models.
### Important File Explanation
In the VAE-LSTM End to end model folder, the main code files are crucial for running the model and obtaining predictions.
## Installation and Configuration
### System Requirements
Compatible with common operating systems.
### Installation Steps
- Install the following dependencies:
numpy
torch
torch.nn
pandas
matplotlib
seaborn
sklearn
math
time
### Configuration Instructions
In the code under the path \VAE-LSTM End to end model, modify the data path in #filepath according to your local machine. Also, modify the generated image save address in #save_path.
Usage Instructions
### Basic Usage
Run the code directly to obtain spring flow prediction results and fitting images.
### Function Introduction
The model takes enhanced precipitation data and predicts spring flow using LSTM.
## Contribution Guidelines
### How to Contribute
Contributions are welcome in the form of bug reports, feature suggestions, and code submissions.
### Contribution Process
Fork the project, create a branch, make changes, and submit a pull request.
### Code Conventions
Follow the existing code style and naming conventions.
## License
[Specify the license here]
## Acknowledgments
The work of Yonghong Hao is partially supported by the National Natural Science Foundation of China 42072277, 41272245, 40972165, 42307088, and 40572150. Chunmei Ma is partially supported by the Scientific Research Project of the Tianjin Education Commission under Grant (No.2021KJ186). Yeh is partially supported by US NSF grant 000316729. Zhu is partially supported by US National Science Foundation Grant No (EAR-1933779).
## Contact Information
jhyandlyf@163.com
