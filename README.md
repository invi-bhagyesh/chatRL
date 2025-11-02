# Chatbot: Seq2Seq + Reinforcement Learning  
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

## 🧠 Overview
A chatbot trained using **Seq2Seq** (LSTM encoder-decoder) and **Reinforcement Learning** (policy gradient).  
Inspired by:  
- [Seq2Seq Learning with Neural Networks](https://arxiv.org/abs/1409.3215)  
- [Deep RL for Dialogue Generation](https://arxiv.org/abs/1606.01541)

---

## 💬 Example Dialog

> **A:** I didn't do it! I haven't got a gun!  
> **B:** You liar. You still want to get your money back.  
> **A:** Something wrong with the truth.  
> **B:** I don't want money, just peace.  

More samples in the [results folder](result).

---

## ⚙️ Run Pretrained Models
```bash
pip install -r requirements.txt
./script/download.sh
./script/simulate.sh <MODEL_PATH> <TYPE> <INPUT_FILE> <OUTPUT_FILE>
