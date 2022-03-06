# Road Lane Detection


Detect road lane from input road image based on edge detection with Canny, ROI, and Hough Transform Line method. 

![src](https://user-images.githubusercontent.com/87270138/156916250-c318260d-f6d9-4f10-addc-9a5e2fa8c2ef.jpg)

![output_img](https://user-images.githubusercontent.com/87270138/156916265-33a7fa31-6a34-419c-88e1-ff40fa1e8650.jpg)


#### Pull from Docker : 
```python
docker pull zahraahnd/road-lane-detection:1.0 
```
#### Run : 
```python
docker run -p [localhost]:5000 zahraahnd/road-lane-detection:1.0 
```
#### Run from compose : <br>
In docker-compose.yml file, change the port into your localhost port
```python
ports:
      - "[localhost]:5000"
```
```python
docker compose run
```
