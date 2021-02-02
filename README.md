**Requirements**

`Python 3.8`
`pip`
**Running**
1. Create a virtual environment with python3.8
   ```
   python3.8 -m venv venv
   source venv/bin/activate
   python detect.py
   ```
   
2. Install dependencies
   `pip install -r requirements.txt`

4. `python find_faces_in_picture.py`

**TODO**

1. time optimiztion

**Issues**
`1.Dlib installation error?`

  ` Make sure you have installed cmake and CMAKE_FOLDER\bin added it in environment varaible`
  ` Install anaconda`
 `  then run following commands in anaconda shell. `
     ` conda update conda`
     ` conda update anaconda`
   `create new environment conda create -n env_dlib python=3.8`
   `activate enviroment` `conda activate env_dlib`
   `install dlib conda install -c conda-forge dlib`
   `Verify your installation in python shell using`

  ` import dlib `
    `   dlib.__version__`
       
 2. how to run dlib face recognition with gpu?
   
     ` conda install pip`
     ` conda install tensorflow`
     ` conda install tensorflow-gpu`
     ` pip install imutils`
     ` pip install opencv-python`
     ` pip install opencv-contrib-python`
     ` pip install dlib`
     ` pip install face_recognition`
