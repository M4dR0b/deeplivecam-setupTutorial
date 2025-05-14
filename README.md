# DeepLiveCam Setup Tutorial

Complete guide for installing and running **DeepLiveCam**, a real-time face injection tool powered by Python, ONNX models, and GPU acceleration.
https://github.com/hacksider/Deep-Live-Cam
---

## 📦 Requirements

- Python 3.10 (recommended via Anaconda)
- FFmpeg
- Visual Studio 2022 Runtime
- CUDA Toolkit (for NVIDIA GPU acceleration)
- DeepLiveCam repository
- Pretrained models

---

## 🔧 Step-by-Step Setup

### 1. Install Anaconda  
Download and install:  
[https://www.anaconda.com/](https://www.anaconda.com/)

Create environment:
```bash
conda create --name deeplivecam python=3.10
```
Activate environment (for later use):
```bash
conda activate deeplivecam
```
Install project requirements (for later use):
```bash
pip install -r requirements.txt
```
Directory to project folder (for later use):
```bash
cd C:\yourPathToProjectFolder
```
Install correct runtime version (for later use):
```bash
pip uninstall onnxruntime onnxruntime-gpu
pip install onnxruntime-gpu==1.16.3
```
Run Deep Live Cam (for later use):
```bash
python run.py --execution-provider cuda
```


### 2. Download DeepLiveCam source code  
Download as zip and extract folder:
[https://github.com/hacksider/Deep-Live-Cam](https://github.com/hacksider/Deep-Live-Cam)

### 3. Download ffmpeg  
Download full version:  
[https://ffmpeg.org/](https://ffmpeg.org/)

### 4. Download and install Visual studio Build Tools  
Download:  
[https://visualstudio.microsoft.com/visual-cpp-build-tools/](https://visualstudio.microsoft.com/visual-cpp-build-tools/)

### 5. Download the models in the models project folder  
Download:  
[https://huggingface.co/hacksider/deep-live-cam/resolve/main/GFPGANv1.4.pth](https://huggingface.co/hacksider/deep-live-cam/resolve/main/GFPGANv1.4.pth)  
[https://huggingface.co/hacksider/deep-live-cam/resolve/main/inswapper_128_fp16.onnx](https://huggingface.co/hacksider/deep-live-cam/resolve/main/inswapper_128_fp16.onnx)

### 6. Download and install CUDA  
Download:  
[https://developer.nvidia.com/cuda-11-8-0-download-archive](https://developer.nvidia.com/cuda-11-8-0-download-archive)
