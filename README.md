# ML-RandomForestRegressor

In my current job, I created applications in tinker using the RandomForestRegressor model, which predicts the number of cartons that will be prepared for the next day.
First, I properly prepared and formatted the test.xlsx file on which the book1.xlsx was based.
Next, I uploaded the file to pandas, made the appropriate calculations, added a few additional features, and created the RandomForestRegressor model.
Then I created the application code in tinker. The code is in the Aplikacja_global.
Finally, using pyinstaller, I converted the code into an executable executable file.


To make the calculations, we need to enter the data from the last 7 days, such as: real, prognoza, palety załadowane od 6:00 do 6:00.
Then the prediction date.

![image](https://github.com/user-attachments/assets/8c125a90-42c6-4675-b011-71760bfc3a88)
