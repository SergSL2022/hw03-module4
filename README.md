# hw03-module4

### 1. Add your user to EKS and create namespace for your test
![alt text](<screenshots/1/Знімок екрана з 2024-06-28 00-30-59.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-28 00-31-29.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-28 00-33-59.png>)
![alt text](<screenshots/1/Знімок екрана з 2024-06-28 00-36-46.png>)


### 2. Create PVC(1Gb) for your deployment
![alt text](<screenshots/2/Знімок екрана з 2024-06-28 14-38-32.png>)
![alt text](<screenshots/2/Знімок екрана з 2024-06-28 14-39-36.png>)
![alt text](<screenshots/2/Знімок екрана з 2024-06-28 14-42-13.png>)


### 3. Create deployment with nginx and mount PVC to it
![alt text](<screenshots/3/Знімок екрана з 2024-06-28 14-44-55.png>)
![alt text](<screenshots/3/Знімок екрана з 2024-06-28 14-46-45.png>)
![alt text](<screenshots/3/Знімок екрана з 2024-06-28 14-50-34.png>)


### 4. Config nginx to get files from this PVC
![alt text](<screenshots/4/Знімок екрана з 2024-06-28 14-57-42.png>)
![alt text](<screenshots/4/Знімок екрана з 2024-06-28 15-04-44.png>)

### 5. Copy test html to volume
![alt text](<screenshots/5/Знімок екрана з 2024-06-28 21-39-17.png>)


### 6. Check that nginx return test html
![alt text](<screenshots/6/Знімок екрана з 2024-06-28 21-34-37.png>)
![alt text](<screenshots/6/Знімок екрана з 2024-06-28 21-42-28.png>)
![alt text](<screenshots/6/Знімок екрана з 2024-06-28 21-42-59.png>)


### 7. Delete pod with nginx


### 8. Make sure that nginx return test html