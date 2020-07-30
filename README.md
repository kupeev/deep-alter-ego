
		
		

		<div class="container">
    		<div class="blurb">
        		## LongaSearch 
			
				 
&#10;				If to ask what a convenient search application should look like,
				one may observe several conflicting desires.
				
&#10;				  
&#10;				  
&#10;					
				On the one hand, a personalized search can be useful. For example, 
				if you are a data scientist working with computer vision
				and your search includes “encoder” you probably mean
				a deep learning auto encoder.
				If you are a video compression engineer, “encoder” in your
				search query probably means an MPEG-4 video encoder. 
				Personalized search should grasp the user's intensions.
				It may proceed through association with the user a personalized profile, 
				learnable at the search queries.
				The problem is that the user may want to avoid storing 
				personal preferences on search engine servers.
					
				  
&#10;				  
						
					
				The user may sometimes want to perform a personalized search, 
				and sometimes not, if he wants to search “from scatch”, 
				without being assiciated to previous searches, similarly to as Duck Duck Go does.
					
				  
	
				  
&#10;					
				The 'Longa' research application is an attempt to cope with these contradictory requirements.
				By analyzing the user's search history, we create a user-specific “deep profile” that allowing
				perform highly personalized searches. 
				The profile is encrypted, stored on the user's computer and is not sent to the outside.
				On the other hand, the user can control the personalization level his search 
				using a simple sliding panel (under impledmentation).
					
				  
		
				  
&#10;					
				Our deep profile is a light generative network associated with the user. 
				The neatwork is trained  by the user's searh history.	
				The network as an assistant created and stored on the user's device, 
				and the user fully controls the assistance.
					
				  
						
				  
&#10;					
				To download and test the application, send an email to longasearch@gmail.com,
				download and unzip longa.zip with the recieved pw, and proceed as described below.
				By using the application you comply with the desclaimer below. 
					
				  
	
				  
&#10;					
				Create a new folder in your Windows computer 
				will be a working directory for the application. 
				Let path_app the path to the folder, unzip there longa.exe application. 
				The application uses a Twitter nlp model (https://nlp.stanford.edu/projects/glove/).
				At the firs run of longa.exe a new folder <glove-twitter-25> and a file
				information.json are created in your working directory.  
				The folder will an nlp model used by Longa, the download
				(following https://radimrehurek.com/gensim/downloader.html),
				will take a few minutes. If you have the GENSIM_DATA_DIR environment variable, 
				the application mayredefine it to the path_app. 
				At running tne app, a file seData.npy is created in the working dir. 
				This is your deep profile stored at your computer.					
				</glove-twitter-25> 	
					

    		</div>
		</div>
		<footer>
    		
        	    	[github.com/kupeev](https://github.com/kupeev/deep-alter-ego)  
			--&gt;
			- [LongaSearch app ](https://github.com/kupeev/deep-alter-ego/releases/download/v1.0/longa.zip)			
			- [ Disclaimer ](https://github.com/kupeev/deep-alter-ego/blob/master/disclaimer.md)
			
		</footer>
	


 
