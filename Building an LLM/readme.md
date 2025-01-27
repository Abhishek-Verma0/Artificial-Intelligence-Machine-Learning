# PyTorch LLM Setup Guide

This guide will help you set up a Python virtual environment and install the necessary dependencies for working with PyTorch and large language models (LLMs). 
### This is just a blind work done by me while trying to understand how a model is made and trained this can be a bit messy If You think something can be improved feel free to contribute .. 

    

---

## **Prerequisites**

Before you begin, ensure you have the following installed on your system:

- **Python 3.8 or higher**: Download and install Python from [python.org](https://www.python.org/downloads/).
- **pip**: Python's package installer (usually comes pre-installed with Python).


---

## Step 1: Clone the Repository or fork it **

If you're working with a Git repository, clone it to your local machine:

```bash
git clone https://github.com/Abhishek-Verma0/Artificial-Intelligence-Machine-Learning.git
cd Artificial-Intelligence-Machine-Learning
```

## Step 2: Setup Python virtual environmnent 
```
python -m venv name -- to create a virtual environment
name\Scripts\activate - activates virtual environment

-  pip install --upgrade pip setuptools  --- upgrade tools  to latest version

```



Dependencies (assuming windows): pip install pylzma numpy ipykernel jupyter torch --index-url https://download.pytorch.org/whl/cu118

If you don't have an NVIDIA GPU, then the device parameter will default to 'cpu' since device = 'cuda' if torch.cuda.is_available() else 'cpu'. If device is defaulting to 'cpu' that is fine, you will just experience slower runtimes.





## Visual Studio 2022 (for lzma compression algo) 
 https://visualstudio.microsoft.com/downloads/





