# 🧬 Project Setup Guide
<div align="center">
  <img src="https://zindi-public-release.s3.eu-west-2.amazonaws.com/uploads/competition/image/591/thumb_f7f99618-bc3d-44db-acfa-39b971d7472f.png" alt="Description" style="width:50%;"/>
</div>

## 📍 Overview

All the core code for this project was originally developed and executed on **Kaggle**.  
However, if you’d like to **run the project on Google Colab**, you can follow the **Colab setup notebook** provided in this repository.

---

## 🚀 Running on Google Colab

If you’re using Colab, start by setting up the environment as follows:

```bash
# 🔧 Unzip the Pygenie Package
!unzip /content/pygenie.zip -d /content/pygenie/
!rm /content/pygenie.zip

# 🧩 Install Required System Libraries
!apt-get update && apt-get install -y libhts-dev zlib1g libzstd1 liblzma5

# 📦 Install Python Dependencies
!pip install /content/pygenie
!pip install Bio pyfiglet --quiet
```
