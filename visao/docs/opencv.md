## Instalação do Open CV


### Passo-a-passo

Instalação de pacotes necessários para o OpenCV:

```
sudo apt-get install -y build-essential cmake pkg-config
sudo apt-get install -y libjpeg-dev libtiff5-dev libjasper-dev libpng12-dev
sudo apt-get install -y libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
sudo apt-get install -y libxvidcore-dev libx264-dev
sudo apt-get install -y libgtk2.0-dev
sudo apt-get install -y libatlas-base-dev gfortran
sudo apt-get install -y python2.7-dev python3-dev

```

Download do código fonte do OpenCV 3.1.0:

```
cd ~
wget -O opencv.zip https://github.com/Itseez/opencv/archive/3.1.0.zip
unzip opencv.zip
wget -O opencv_contrib.zip https://github.com/Itseez/opencv_contrib/archive/3.1.0.zip
unzip opencv_contrib.zip
```


Instalação do NumPy (pacote do Python para operações com arrays e matrizes multidimensionais):

```
pip install numpy
```

Compilacao do OpenCV 3.1.0:

```
cd ~/opencv-3.1.0/
mkdir build
cd build
cmake -D CMAKE_BUILD_TYPE=RELEASE \
    -D ENABLE_PRECOMPILED_HEADERS=OFF \
    -D CMAKE_INSTALL_PREFIX=/usr/local \
    -D INSTALL_PYTHON_EXAMPLES=ON \
    -D OPENCV_EXTRA_MODULES_PATH=~/opencv_contrib-3.1.0/modules \
    -D BUILD_EXAMPLES=ON ..
make
```

Instalação do OpenCV 3.1.0:

```
sudo make install
```

Criação de links e cache para as bibliotecas:

```
sudo ldconfig
```

### Referências

https://www.youtube.com/watch?v=RE-p7GedP2Y&feature=youtu.be (Acesso em 20 de Outubro de 2019).