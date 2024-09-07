# Jagadha-Exp---4
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\rjaga\Downloads\daily-total-female-births.csv')
print(series.head())
series.plot()
pyplot.show()
![Screenshot 2024-09-07 145958](https://github.com/user-attachments/assets/1c14655e-bc38-4a2d-b345-73fbdd690045)
series.plot(style='-.')
pyplot.show()
![Screenshot 2024-09-07 145601](https://github.com/user-attachments/assets/11c84644-6a04-416d-ba8f-0beebc74e602)
series.hist()
pyplot.show()
![Screenshot 2024-09-07 145703](https://github.com/user-attachments/assets/424fd504-4560-4d38-8406-0136b07791b4)
series.plot(kind='kde')
pyplot.show()
![Screenshot 2024-09-07 145746](https://github.com/user-attachments/assets/a9704388-5601-421c-9ef3-3a94a9416994)



