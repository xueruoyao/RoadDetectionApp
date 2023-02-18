# RoadDetectionApp

This is a web application to perform real-time road detection task worldwide.

Server: Python Fastapi

Client: vue3 + vite

<p align="center">
  <img src="./example.gif">
</p>

## 1 Server

### 1.1 Configure Python Virtual Environment

First, we create a new virtual environment under the project directory

```apache
cd RoadDetector-server
virtualenv --python=python3.9.7 project-env
```

Then, activate the env and install the required packages

```
source project-env/Scripts/activate
pip install -r requirements.txt
```

### 1.2 Run server

````apache
cd src
python run.py
````

### 1.3 Download pretrained model

BaiduNetDisk: https://pan.baidu.com/s/1a8FyYPiqgqcnOShszeCLpw
Code: f1gd

## 2 Client

### 2.1 Prepare environment

```apache
cd RoadDetector-client
npm install
```

### 2.2 Run client

```apache
npm run dev
```

> Reference: https://github.com/AliFlux/MapTilesDownloader