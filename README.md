# Krea 2 (K2)

Krea 2 - an image generation model from [Krea AI](https://www.krea.ai).

---

<div align="center">


# DON'T CLONE THIS REPO, IT WON'T WORK AS IT ALL DEPENDS ON THE PYTHON_EMBEDED 3.12.10 TO WORK! 


## I made this Krea 2 Portable 1 click install for Windows that uses Nvidia GTX 10XX, 16XX, RTX Quadro, 20XX, 30XX, 40XX, 50XX GPU. Installs Torch with Cuda, Sage Attention, Triton & all other requirements also creates Launch Krea 2 & Image Desktop Shortcuts. Automatically saves generations into "outputs" folder. Automatically saves last used settings in .json file & loads them automatically on startup.


## Click here to jump to Install 👉 [Installation](#-Installation) 👈


![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/redtash1/stable-audio-3-Windows-1-Click-Install/total?style=for-the-badge&labelColor=orange&color=0000ff)



</div> 


---


<img width="1920" height="1080" alt="Krea 2" src="https://github.com/user-attachments/assets/69e16c11-1f1a-4fa3-a9aa-c4417e898118" />


----

<p align="center">
<a href="https://docs.krea.ai/api-reference/introduction">API Docs</a> •
<a href="https://huggingface.co/krea/krea-2-raw">Hugging Face (RAW)</a> •
<a href="https://huggingface.co/krea/krea-2-turbo">Hugging Face (TURBO)</a> •
<a href="https://www.krea.ai/blog/krea-2-technical-report">Technical Blog</a>
</p>


---

### Features your choice of models
* Krea2 Raw BF16 
* Krea2 Raw INT8
* Krea2 Turbo BF16
* Krea2 Turbo INT8

### Features Krea 2 original LoRAs
* Dark Brush
* Dot Matrix
* Kids Drawing
* Neon Drip
* Rainy Window
* Retro Anime
* Soft Watercolor
* Sunset Blur
* Vintage Tarot

### Custom LoRA Downloader

### Real-ESRGAN Upscaler with 2X-4X & Anime
* Single image, batch or folder upscaling

### Image Metadata Viewer
* All images are saved with all the Metadata embedded in PNG like ComfyUI.

### Models, LoRA & Upscale Model Managers

---


# 📦 Installation

## Nvidia GTX 10XX, 16XX, RTX Quadro, 20XX, 30XX, 40XX, 50XX  

## GTX 10XX-RTX 30XX will have torch 2.6.0+cu126 installed for compatibility. RTX 40XX & 50XX will have torch 2.7.1+cu128.


1. Make sure you have Git installed, if not download the Git Standalone Installer and click on Git for Windows/x64 Setup. 👉 [Git Standalone Installer Download](https://git-scm.com/downloads/win) 👈 To install Git, double click Git.exe and just keep clicking next until it's installed, you don't need to change anything.


2. Make sure your Nvidia graphics drivers are up-to-date. If they are not or if your not sure, please click on the following link to download Nvidia graphics drivers. 👉 [Nvidia Drivers](https://www.nvidia.com/en-us/software/nvidia-app/) 👈

3. Make sure that you have NVIDIA's [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit) version **12.8** (or newer) installed on your system.

4. Make sure you have FFMPEG Shared downloaded & on PATH. Download 👉 [ffmpeg-release-full-shared.7z](https://www.gyan.dev/ffmpeg/builds/) 👈

5.  Now after you have made sure Nvidia GPU drivers are up to date and Git is installed, download Krea 2 Windows 1 Click Install
 from here 👉 [Stable Audio 3 Windows 1 Click Install](https://github.com/Redtash1/stable-audio-3-Windows-1-Click-Install/releases) 👈 or from the Releases section at the top right of this page.

6. After downloading, extract Krea 2 Windows 1 Click Install ZIP file and pick where you would like to extract the zip files too.

7. Then open Krea 2 Windows 1 Click Install main folder, you will see this in the root
----

<img width="511" height="110" alt="Screenshot 2026-07-29 204733" src="https://github.com/user-attachments/assets/971e00f2-d3b8-4459-a07a-49707744d3b9" />

----
8. Then double click on Install_Krea_2.bat to start the installation. It will install everything.  After installation is finished, slowly scroll back up to the top to make sure everything installed correctly.

9. To launch Stable Audio 3 double click the Launch_Krea_2.bat & it will automatically open in your default Internet Browser.

---

## Troubleshooting

If you have problems after a successful installation, please go to the Official Krea 2 Github to report problems. [Krea 2](https://github.com/krea-ai/krea-2). Thank you.

### If this worked for you, Please give it a Star ⭐. Thank you.


## Documentation

- [Prompting Guide](docs/prompting.md)
- [Safety Guide](docs/safety.md)


## FAQ

**Which model I should use?**

Use the **Turbo** model for fast inference with high quality results. The **Raw** model is an undistilled checkpoint without any step / cfg guidance distillation and posttraining. It is a highly finetunable base model that can be used to train LoRAs for the Turbo model as well as posttraining research. In short, **TRAIN on Raw and RUN on Turbo**.

**What license is this model released under?**

Both model weights are under our [community license](https://www.krea.ai/krea-2-licensing) with permissive use. To purchase a commercial license, please contact us at [opensource@krea.ai](mailto:opensource@krea.ai).


## Thanks to:
DeepBeepMeep for models, some Krea 2 code & MMGP for the GPU Poor. [Hugging Face](https://huggingface.co/DeepBeepMeep) [Github](https://github.com/deepbeepmeep)

Xintao for [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)


## Citation
```
@misc{krea-2-2026,
    author={Sangwu Lee, Erwann Millon, Le Zhuo, Matthew Newton, Andrei Filatov, Abhinay Devarinti, Dazhi Zhong, Avram Djordjevic, Gabriel Menezes, Will Beddow, Titus Ebbecke, Mihai Petrescu, Owen Fahey, Gian Saß, Felix Gil, Victor Perez},
    title={{Krea 2}},
    year={2026},
    howpublished={\url{https://www.krea.ai/blog/krea-2-technical-report}},
}
```
