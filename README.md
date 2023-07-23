# AutoGPT_app-
# YouTube GPT Creator
   This is webapp which takes your topic of interest as prompt and outputs 
   video title according to the topic and also writes a script related to the topic 
   leveraging wikipedia research . 
## Download 
  clone the repository to local machine .  
      
      $ git clone https://github.com/xorsuyash/AutoGPT_app-.git

## How to run 
 create a new conda enviroment:
 
         $ conda create --name Langchain python=3

 Activate your conda enviroment: 

        $ conda activate Langchain 

 Install the required dependencies:

        $ pip install streamlit langchain openai chromadb wikipedia tiktoken 

 After installing the required dependency navigate to apikey.py file and enter your openai api key:

        $ cd AutoGPT_app-
        $ vim apikey.py 
        ~ apikey = 'sk ....'
 After inserting the api key run following command on terminal : 

        $ streamlit run app.py 


 
      
     
