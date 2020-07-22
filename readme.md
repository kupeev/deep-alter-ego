
Create a new folder which will be a working 
directory for the application. Let path_app the paath to tne folder,
Unziping longa.zip to the folder creates longa.exe application.
The application uses a Twitter model (https://nlp.stanford.edu/projects/glove/) 
the model is downloaded to working 
directory at the first run of longa.exe.
At this run there is created a new folder <glove-twitter-25> containgin the donloaded 
nlp model (will take a few minutes), and information.json file (is not used).
Also, if yoy have the GENSIM_DATA_DIR environment variable, the application may 
redefine it to the path_app.
At running tne app, a file seData.npy  is created in the working 
directory. This is the deep profile, derived from the search history
of your browser, and stored at yor computer.
