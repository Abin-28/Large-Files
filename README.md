# Large-Files

First copy the large file in separate folder

Then do the below command in cmd by opening insame path where the file is located after that a hidden git folder is created
git init

Copy the remote link from the newly created repository
for Example
git remote add origin https://github.com/Abin-28/Large-Files.git

then install lfs if not 
git lfs install

After installing track the lage file .extension for example here similarity.pkl is the large file so track ".pkl"
git lfs track "*.pkl"

Then do : git lfs push -all origin main

then do : git add .

then do : git commit -m "Message"

then do : git push -u origin master or # git push -u origin main

In this way the lage files will be uploaded to the github repository
