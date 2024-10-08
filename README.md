<div align="center">
    <h3 style="margin-bottom:-55px;margin-left:55px;color:#6332e5">Chat with</h3>
    <img src="https://qianwen-res.oss-accelerate-overseas.aliyuncs.com/Qwen2-VL/qwen2VL_logo.png" width="400"/>
    <br/>
    <a target="_blank" href="https://lightning.ai/bhimrajyadav/studios/deploy-and-chat-with-qwen2-vl-using-litserve">
      <img src="https://pl-bolts-doc-images.s3.us-east-2.amazonaws.com/app-2/studio-badge.svg" alt="Open In Studio"/>
    </a>

<video src="https://github.com/user-attachments/assets/59939d19-384e-4966-a7f7-3e3e009b5177" 
       type="video/webm" 
       controls 
       style="max-width: 640px; width: 100%; height: auto;">
</video>
</div>

## Overview

[**Qwen2-VL**](https://huggingface.co/Qwen/Qwen2-VL-7B-Instruct) is the latest version of the vision language models in the Qwen model familities.

This model enables multi-frame image understanding, image comparison, multi-image summarization/storytelling, and video summarization, which have broad applications in office scenarios.

## Getting Started

Follow these steps to set up and run the project:

### 1. Install Dependencies

Ensure all necessary packages are installed by running:

```bash
pip install -r requirements.txt
```

### 2. Start the API Server

Launch the API server powered by [LitServe](https://github.com/Lightning-AI/LitServe):

```bash
python server.py
```

### 3. Launch the Streamlit App

Start the Streamlit application with the following command:

```bash
streamlit run app.py
```

## About

This project is developed and maintained with ❤️ by [Bhimraj Yadav](https://github.com/bhimrazy).

