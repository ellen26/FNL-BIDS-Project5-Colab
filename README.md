# NIH
repo for NIH summer project

Goal:
1: Understand how to connect Github (open source) to Google Colab
2: Compare usage between two platforms

Two Github provided by professor: 
https://github.com/ravichas/ML-TC1 (Machine Learning)
https://github.com/ravichas/ML-predict-drugclass (Deep Learning)

Advantage 1: 
Using Google Colab, it only takes one step to link with Github. 
For example: 
Original Github notebook link: https://github.com/ravichas/ML-predict-drugclass/blob/master/predict-drugclass.ipynb
Change to Colab link:  https://colab.research.google.com/github/ravichas/ML-predict-drugclass/blob/master/predict-drugclass.ipynb
Create a text box and put in the colab link into it.
Then when you click on it, it will show as ML.ipynb in this repo. 
The link for that page will change to: https://colab.research.google.com/github/ravichas/ML-predict-drugclass/blob/master/predict-drugclass.ipynb#scrollTo=Sj8qV5neKSd1

Advantage 2:
When saving the files, here I download the ipynb from Google Colab and , because here I am using other people's Github.
However, when linking with code from my own Github, I can simply make changes from within Colab and save the file by choosing File ---> Save a Copy to Github and follow the resulting prompts.
OR:
using !git config - global user.email"You@Your.com" method referenced to https://medium.com/@navan0/how-to-push-files-into-github-from-google-colab-379fd0077aa8

Advantage three:
Google Colab can directly show the output for Github notebook, unlike other platforms.

Performance:
Overall, Google Colab performs really well in using and linking Github resources. Even though for some graphs, their size need to be resize. It does not need to rerun the code to see the outputs, but if you need to make changes to code you need to download every data and packages included in original Github's notebook. 

Next step:
Using the configuration file provided, test how many and how long does it take to install all needed packages, via changing environment.

Related reference: https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb
