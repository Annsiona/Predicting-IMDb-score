This is a Machine Learning Model to predict the IMDb of Films,Dramas,Documemtry etc..
This model can be Implemented using  IDE's Like VS Code,PyCharm,ananconda,etc..
To Run this model Install the Following Python Packages:
    1)numpy
    2)pandas
    3)Sklearn
    
How To install these packages:

In VS Code:
          To install Python libraries in Visual Studio Code, create a virtual environment using "python -m venv" command, copy the project folder path, create a virtual environment using "v env", download the required library using "pip install", and run the code. 

Another Method:
          To install a package that includes a setup.py file, open a command or terminal window and: cd into the root directory where setup.py is located. Enter: python `m pip install package name.

In PyCharm:
          Install a package on a virtual environment.  Press Ctr+Alt
          To open the IDE settings and then select Project <project name> | Python Interpreter.
          Expand the list of the available interpreters and click Show All. Show all available interpreters
          Locate the target interpreter and press edit interpreter.
          Discover the interpreter path for the selected venv.Copy or memorize the path of the virtual environment and close the dialogs.
  
  Open the terminal and run the following commands:
  
  source <venv path>/bin/activate
  pip install <package name>
  Installing a Python package on a virtual environment
  Inspect and parse the results.

After Installing the required Packages,Load the Dataset into the ML Model.

An example Dataset:
link:https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores.

Description:
        This dataset contains 6 columns ,584 rows which have unique values. It comprises of Documentary,Drama,Films in different genre with when they are premeired . It includes movies of various languages such as English, Hindi and foreign languages. 

Then the model will analyse the given dataset.whether the given data are correlated or uncorrelated.If the dataset is uncorrelated IMDb score can't be predicted.

If the dataset is correlated,Then it will check for any duplicate data is present in data set.

If any data is missed,then the model will predict it. 

Linear regressionn method is used to predictive analysis and Gradient Boosting Regression Mthods is used to decerease the bias error.

Then the model Evaluation is evaluated by MAE(Mean Absolute Error),MSE(Mean Squared Error) and R Squared Error.

Finally The Predicted IMDb Scores of Films,Dramas etc.. are displayed in the Terminal as the Output of the Machine Learning Model. 
