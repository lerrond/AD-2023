# AD-2023 task from university data analysis course  
В задании представлена модель торгового робота, реагирующего на сигналы по методике скользящего среднего (продажа и покупка ценных бумаг на бирже). Также в учет бралось изначальное количество денег, имеющееся на балансе у лица и сигнал "стоп", означающий, что потери слишком велики. В качестве примера были взяты акции "Газпрома", для работы использовалась библиотека vectorbt. 

Для того, чтобы появилась визуализация - тепловые карты, графики кэш/активы, графики со свечами, необходимо скачать файл и запустить его - гитхаб плохо отображает графики из некоторых библиотек.

#### ex:

График покупок/продаж, полученный из пересечения скользящих средних с учетом стартового количества денег:
![newplot](https://github.com/user-attachments/assets/7874dd6d-35bc-4a63-8a6f-58bc9c58475b)


Тепловая карта, отражающая величину итогового заработка лица при выборе окон размера n и k:
![newplot (1)](https://github.com/user-attachments/assets/ae246240-fb62-4b39-b74c-469f8d58e2c2)
 
