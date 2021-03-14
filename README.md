# CoronaVirusPrediction

The project is the simple prediction of the Dortmund city. We have used Time series analysis to predict the corona virus infection rate.

For the prediction we have used MA and AR method initially but due to non stationary data we have intergrate and use ARIMA model forpredicting the forecast.


Import the project using using below command 

1) git clone https://github.com/krupa1106/CoronaVirusPrediction.git

2) Import the .ipynb to Google colab or Jyupter notebook

3) change the dataset storage path in line 2 or inline "df = pd.read_excel('/content/drive/MyDrive/SICO2/Book1.xlsx', index_col='Datum', usecols=['Datum', 'Dortmund'])".

4) Instead of Dortmund you can also check for the data of other cities in NRW region.

