# Project_Images
A desktop software that applies the topics studied in class. 
The main idea is that the final user can select which algorithm 
he/she wants to apply to an image, shown in the UI.

# Con Docker

```
docker build --rm -f "Dockerfile" -t project_images:latest .

docker run -ti --rm -e DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix project_images
```
# Sin Docker

```
sudo apt-get install python3
sudo apt-get install python3-pip
sudo apt-get install python3-tk
```

con pip3

```
pip3 install pydicom
pip3 install numpy
pip3 install scikit-image
pip3 install matplotlib
```

 run
```
python3 main.py
```
