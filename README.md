# Hard-Hat-detection
The sole purpose of this project is to detect the  Hard-Hat of construction worker. 

# How to run
- Download this file and unzip it(7z recommended).
- make a seperate directory and paste the unzip file to that directory.
- Open Anaconda prompt->Copy the file path->use cd (File path) to locate the file through anacoda prompt.
- Create an environment using this command -> conda create -n envname
- Once environment is created activate it.
- In the zipped file the requirement.txt is there.
- run pip install -r requirements.txt in anaconda prompt
- Again run pip install torch==1.7.0+cpu torchvision==0.8.1+cpu torchaudio==0.7.0 -f  to install the torch and torchvision.
- If you're still facing any problem then download torch and torchvision through this link  https://download.pytorch.org/whl/torch_stable.html
- Now run python detect.py --weights weights/best.pt --source (images,videos or webcam=0) for real time detection.
