# AeonLabs Ghost Writer GPT-3  ![](https://views.whatilearened.today/views/github/aeonSolutions/AeonLabs_Ghost_Writer_GPT_3.svg)
 This is a small piece of python code to evaluate GPT-3 capabilities for assisted writing.

## Setup
### 0- download this github repository
![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/github_download.png)

### 0.1 - Extract Zip file contents
- Create a new directory named "Jupyter" inside the directory c:\users\\%userName%
- Create a new directory named "GPT3" inside the directory c:\users\\%userName%\Jupyter

where %userName% is your windows account username

Extract Zip files contents a to the Directory c:\users\\%userName%\\Jupyter\GPT3

In the end, should be look like this
![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/windows_explorer.png)

### 1- Install Anaconda distro
Goto Anaconda website here: https://www.anaconda.com , download and install. The instalation is simple and strait forward
![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/anaconda_website.png)

### 2- Open Anaconda App and select "Lauch" in CMD.exe prompt
![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/anaconda_cmd.png)

### 3- Install python libraires
Next a command prompt windows opens. And then you need to install the following python libraries by typing and hit enter each one below

- pip install openai
- pip install python-docx
- pip install python-dotenv
 
![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/cmd_prompt.png)

### 4- Go to Anaconda App and select "Lauch" Jupiter Notebooks
![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/anaconda_jupyter.png)

this is how Jupiter Nobooks looks like in a browser (i'm using brave browser)

![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/jupyter_folder.png)

### 5 - Open a Jupyer Notebook
In the Tab with the jupyter notebooks files and folders click to open the "Jupyter" folder (created earlier). Next click to open the "GPT3" folder (created earlier).

The last step is to open the jupyter notebook "*OpenAI Essay Writer.ipynb*". Double click an a new tab will open in the browser.

The code open should look something like the one in the snapshot below.
![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/jupyter_notebooks.png)

### 6- Get a API KEY from Open AI website
In order GPT-3 algorithm to work you need to have an API KEY made available at Open AI website here: https://beta.openai.com/signup

Sign up for a new account. And whem you're done , login and goto the page USERS >> API KEY by clicking on the left side menu.

A new page will open where you can create a new API KEY and copy.

![](https://github.com/aeonSolutions/AeonLabs-Ghost-Writer-GPT-3/blob/main/img/open_ai_website.png)

Next goto windows explorer folder "c:\users\\%userName%\\Jupyter\GPT3" and open with the notepad the file named ".ENV". Paste inside that file the API Key you copied from the website next to the = sign , where it says: 

OPENAI_KEY="paste your api key where" (without the qoute marks)

Now , got back to the browser with the jupyter notebook "*OpenAI Essay Writer.ipynb*" open and click run to see the GPT-3 provide text paragraph sugestions.

