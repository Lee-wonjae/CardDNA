How_to_use
================================
< 1. Use Colab >

step1. Run Colab
	: Launch a Colab notebook and navigate to the desired directory.
Step2. Check for Git Installation
	: Typically, Git is already installed in Colab. However, if it's not, you can install it using the following command: 

          !apt-get install -y git
Step3. Mount Google Drive
	: Mount Google Drive using the following code.
	
	  from google.colab import drive drive.mount('/content/drive')
Step4. Change to Working Directory:
	: Move to the directory where you want to perform your work cd /content/drive/My Drive/
Step5. Clone the GitHub Repository
	: Clone the GitHub repository using the following command
	
          git clone https://github.com/Lee-wonjae/CardDNA.git
By following these steps, you can successfully clone a GitHub repository in Jupyter Notebook.


< 2. Use Jupyter Notebook >

step1. Run Jupyter NotebooK 
	: Start Jupyter Notebook and navigate to the desired directory.
Step2. Check for Git Installation
	: Verify if Git is already installed, or install it if not. 
         
          !apt-get install -y git
Step3. Navigate to the Working Directory
	: Move to the directory where you want to clone the repository. cd /path/to/your/directory
Step4. Clone the GitHub Repository
	: Use the following command to clone the GitHub repository.
	
          git clone https://github.com/Lee-wonjae/CardDNA.git
Following these steps, you should be able to successfully clone a GitHub repository in Jupyter Notebook
