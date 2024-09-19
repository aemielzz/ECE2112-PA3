## Experiment 3
### PYTHON DATA ANALYSIS (PANDAS)
##### Amiel Elestin M. Cruz
##### 2ECE-D

![image](https://github.com/user-attachments/assets/43d556ee-6e0a-4d08-abb4-b8235cb6d48b)

When using pandas, it is mandatory to input "Import pandas as pd" to access pandas lib

__PROBLEM 1:__

__a. Load the corresponding .csv file into a data frame named cars using pandas__

![image](https://github.com/user-attachments/assets/c9762195-3546-44d9-bf69-14b76e75e1b0)

for Problem A. I declared the cars as pd.read_csv('cars.csv') to read the cars file that I downloaded and for me to use it to declare for our next codes. commanding pd.read_csv(file) will automatically read the file in the same folder with the same format and encoded 'cars' to print the file which is in tabular form.

__b. Display the first five and last five rows of the resulting cars.__
![image](https://github.com/user-attachments/assets/223e8fad-5f9d-4e6a-9b05-203b27de707b)

To display the first five rows of the resulting cars, I used "cars.head" to show the upper part of the table and "(5)" since in the instructions the first five rows is what we are looking for.

![image](https://github.com/user-attachments/assets/ebe0b396-4f96-4722-b027-32b50abfbf3d)

On the other hand, to display the last five rows of the resulting cars, I used "cars.tail" to show the lower part of the table and "(5)" since in the instructions the last five rows is what we are looking for.

____PROBLEM 2:____

![image](https://github.com/user-attachments/assets/51002f1c-39e0-4b49-9b25-e9b4ebe0dc0c)

I input "import pandas as pd" again since we are going to access pandas library and this is in another file.

![image](https://github.com/user-attachments/assets/26069f7b-9527-4ac6-8cff-2939baa88da7)

I declared the cars as pd.read_csv('cars.csv') to read the cars file that I downloaded and use it for the following codes that I am going to execute

![image](https://github.com/user-attachments/assets/a69acb60-f200-4ffd-853a-80908211bb7f)

I used "c" to represent as cars which represents as the file that I downloaded.

__a. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7…) of cars.__
![image](https://github.com/user-attachments/assets/a7dcd507-3962-42e1-8401-0efd0b2657c3)

To display the first five rows with odd-numbered columns of cars, I used c.loc which is used to locate and I encoded "[0,1,2,3,4]" manually to locate the first five rows. For me to display the odd-numbered columns I manually counted the columns for me to know the odd columns and inputted it as ['Model','cyl','hp','wt','vs','gear']. 
So all in all, my entire code for that is c.loc [[0,1,2,3,4],['Model','cyl','hp','wt','vs','gear']]  

__b. Display the row that contains the ‘Model’ of ‘Mazda RX4’.__
![image](https://github.com/user-attachments/assets/af531316-ecef-416b-ac4c-faba173e45ce)

For me to display the row that contains the model of Mazda RX4, I used "c[0:1]." Since we are looking for Mazda RX4 its number is 0 and I used 1 for it to stop before the 2nd row which is number 1

__c. How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?__
![image](https://github.com/user-attachments/assets/76b1210d-8723-435f-87cf-8252ae6e321b)

To know how many cylinders does the camaro Z28 have is I used c.loc to locate and [23] because Camaro Z28 is the 23rd car in the table. I also inputted ['Model','cyl'] to locate the model name, to know that it is the Camaro Z28 and how many cylinders it has
all in all my code is c.loc [[23],['Model','cyl']] to locate the 23rd car, the model, and how many cylinder it has.

__d. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4 Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.__

![image](https://github.com/user-attachments/assets/402b9a96-88f1-4daa-9cb4-2253ac7ec270)

To know how many cylinders and what gear type the car models ‘Mazda RX4 Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have, I first locate or know whats their number in the table provided.  I used c.loc to locate and [1,18,28] because that is their respective number, I organized them numerically because from the question honda civic comes last but its the number 18th from the table. After that I encoded ['Model','Cyl','gear'] since we are looking for cylinders and geartype for a specific model.
All in all my code for that is  c.loc [[1,18,28],['Model','cyl','gear']] and the picture above is the outcome.







