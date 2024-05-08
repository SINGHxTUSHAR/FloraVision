[![GitHub license](https://img.shields.io/github/license/SINGHxTUSHAR/FloraVision.svg)](https://github.com/SINGHxTUSHAR/FloraVision/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/SINGHxTUSHAR/FloraVision.svg)](https://GitHub.com/SINGHxTUSHAR/FloraVision/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/SINGHxTUSHAR/FloraVision.svg)](https://GitHub.com/SINGHxTUSHAR/FloraVision/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/SINGHxTUSHAR/FloraVision.svg)](https://GitHub.com/SINGHxTUSHAR/FloraVision/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


[![GitHub watchers](https://img.shields.io/github/watchers/SINGHxTUSHAR/FloraVision.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/FloraVision/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/SINGHxTUSHAR/FloraVision.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/FloraVision/network/)
[![GitHub stars](https://img.shields.io/github/stars/SINGHxTUSHAR/FloraVision.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/FloraVision/stargazers/)

[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/SINGHxTUSHAR/FloraVision)


# FloraVision 🌷:
Flower-Image-Classification-Streamlit-TensorFlow
![Designer (1)](https://github.com/SINGHxTUSHAR/FloraVision/assets/113624520/9cd300a2-cb1b-4f63-bf3c-8d72428bd6e4)

A basic web-app for image classification using Streamlit and TensorFlow.

It classifies the given image of a flower into one of the following five categories :-  
1. Daisy
2. Dandelion
3. Rose
4. Sunflower
5. Tulip

### `Notes:`
* A simple flower classification model was trained using TensorFlow.  
* The weights are stored as `flower_model_trained.hdf5`.  
* The code to train the modify and train the model can be found in `model.py`.  
* The web-app created using Streamlit can be found in `app.py`

## Commands ✍️:

To run the app locally, use the following command :-  
`streamlit run app.py`  

The webpage should open in the browser automatically.  
If it doesn't, the local URL would be output in the terminal, just copy it and open it in the browser manually.  
By default, it would be `http://localhost:8501/`  

Click on `Browse files` and choose an image from your computer to upload.  
Once uploaded, the model will perform inference and the output will be displayed.  

## Output 📁:
For more output images visit: <a href="https://github.com/SINGHxTUSHAR/FloraVision/tree/main/Output"> Link </a>
![out_1](https://github.com/SINGHxTUSHAR/FloraVision/assets/113624520/26275ee5-63f1-4c22-bdc9-0f77b4ccd368)


## Reference 🧧:
* Image classification <a href="https://www.tensorflow.org/tutorials/images/classification"> Documentation </a>
* Streamlit <a href="https://docs.streamlit.io/"> Documentation </a>

## Requirements💻 :

Ensure you have the following dependencies installed:

- Python (version 3.9.x || 3.12.x)
- IDE: VS-CODE or collab
- Virtual-environment(venv)
- Other dependencies (refer to the requirements.txt)

You can install the required Python packages using:

```bash
pip install -r requirements.txt
```

## Setup 💿:

- Clone the repository:
```bash
git clone https://github.com/SINGHxTUSHAR/FloraVision.git
cd FloraVision
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## Contributing 📌:
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## Suggestion 🚀: 
If you have any suggestions for me related to this project, feel free to contact me at tusharsinghrawat.delhi@gmail.com or <a href="https://www.linkedin.com/in/singhxtushar/">LinkedIn</a>.

## License 📝:
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/FloraVision/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.
