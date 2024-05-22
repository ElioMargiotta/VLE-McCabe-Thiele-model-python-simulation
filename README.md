# VLE-McCabe-Thiele-model-python-simulation
The model utilizes CSV files as input to plot the VLE. The parameters include Murphree efficiency, bottom, feed, and distillate compositions, as well as the R factor. The output is a McCabe-Thiele plot, which allows you to determine the number of stages and the molar composition at each stage.

## How to Use 
Download to McCabe-Thiele.ipynb file. Open it in vscode. 
First, add your path to the CSV file. 
Next, change the separatof if necessary here : df = pd.read_csv(file_path,sep=';')

Then Replace 'x_data' and 'y_data' with your actual column names here:

x_data_column_name = 'x_data' 

y_data_column_name = 'y_data'  

Finally, run with python 3.12.0 kernel.

