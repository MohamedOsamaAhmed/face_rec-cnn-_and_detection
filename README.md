**Requirements**

`Python 3.8`

**Running**

1. Download training model

   ```
   mkdir model
   wget -P model https://github.com/OlafenwaMoses/ImageAI/releases/download/essentials-v5/resnet50_coco_best_v2.1.0.h5/
   ```

2. Create a virtual environment with python3.8
   ```
   python3.8 -m venv venv
   source venv/bin/activate
   python detect.py
   ```
   
3. Install dependencies
   `pip install -r requirements`

4. `python detect.py`

**TODO**

1. Bulk images
2. GPU acceleration
