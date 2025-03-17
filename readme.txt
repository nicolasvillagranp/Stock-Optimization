modelosArima folder: Folder with the trained Arima modelosArima.

LSTM forlder: Folder with the actual values of stocks and predicted with LSTM in csv format.
calc_results.ipynb: File to calc the performance measured in profit of the whole process. Follow the instructions 
given in the markdown cell. 

arima_random_walk: File to show how arima predicts the prev day and its useless.
ejemplo.

lstm_example: file to show different examples of LSTM forecast

model_garch_EWSD: file to estimate the risk of each stock and plot the lstm prediction with interval confidence.

plot_riesgos: File to show the distribution of risk.

preparar_datos: File to convert LSTM predictions to something manageable by the optimizer.

programa_optimizador: File to design the investment portfolio using pyomo.

reales: File that contains the actual values in a desired way.

resultados_no_constraints.json: File that contains the investment design of model with no constraints.

resultados: File that contains the investment design of model with no constraints.

std: File that contains the risk related to each stock.

train_arima: File that trains different arima functions using autoarima.