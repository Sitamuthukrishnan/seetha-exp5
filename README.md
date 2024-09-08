# seetha-exp6
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\sita\Downloads\airline-passengers.csv')
print(series.head())
series.plot()
pyplot.show()
![Screenshot 2024-09-08 184905](https://github.com/user-attachments/assets/e5daee61-e566-4471-b260-4d791f13f27a)
series.plot(style='-.')
pyplot.show()
![Screenshot 2024-09-08 185018](https://github.com/user-attachments/assets/e01eab5f-3b93-41fb-8f52-e9e666677bc2)
series.hist()
pyplot.show()
![Screenshot 2024-09-08 185057](https://github.com/user-attachments/assets/60a076b0-fe91-4022-872d-96b111a75161)
series.plot(kind='kde')
pyplot.show()
![Screenshot 2024-09-08 185136](https://github.com/user-attachments/assets/699d3aac-fb93-4605-b669-e3d78b459229)




