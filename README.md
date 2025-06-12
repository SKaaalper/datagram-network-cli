## 📡 Datagram Network — Node Setup Guide (Early Alpha)

![image](https://github.com/user-attachments/assets/2134be74-1523-4fc1-999f-897c2fa0cbb2)

**Datagram is an AI-powered Hyper-Fabric Network that connects DePINs (Decentralized Physical Infrastructure Networks), enabling real-time data processing and intelligent bandwidth allocation across industries like telecom, gaming, and AI.**

This guide helps you install and run a **Datagram Node CLI** as an **Early Alpha Tester**.

📝 Requirements:

✅ **Linux VPS** (Ubuntu 20.04 or newer)

✅ **Basic terminal access**

✅ **Discord**, **Telegram**, and **X** accounts

✅ [Register Datagram Dashboard account](https://dashboard.datagram.network?ref=427744600)

✅ Your **Datagram API Key** from **Wallet** > [Licenses tab](https://dashboard.datagram.network/wallet?tab=licenses)


## Step-by-Step Installation:

### 1. Complete Community Tasks
- To qualify as an Early Alpha Tester:
- Follow [@DGramNetwork](https://x.com/DGramNetwork) on X and Retweet/Like the [Alpha Testnet video](https://x.com/DGramNetwork/status/1932786372613734602 ).
- Join [Telegram Group](https://t.me/datagramnetwork)
- Join [Discord](https://discord.gg/dcM6PF33fu) Server and refer 5 friends.
- Make sure to run your node before submitting the **Early Alpha Tester** [Form](https://docs.google.com/forms/d/e/1FAIpQLSevC3QjAx4xdNysKoRtCSR_5cAUtVBhoNu3XoCrQBIOYVQN8A/viewform)

### 2. Register Your Account:
- Sign up and access your dashboard here: [https://dashboard.datagram.network/](https://dashboard.datagram.network?ref=427744600)
- Go to **Wallet** > **Licenses** and copy your **API Key**

![image](https://github.com/user-attachments/assets/ef15ffd6-0c45-4284-880b-567562730636)

### 3. Install Datagram CLI:
- Run the following command to install the CLI tool:
```
wget https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux && \
sudo mv datagram-cli-x86_64-linux /usr/local/bin/datagram-cli && \
sudo chmod +x /usr/local/bin/datagram-cli
```

### 4. Run the Node:
- Replace `YOUR_API_KEY` with the actual key from your dashboard:
```
screen -dmS datagram datagram-cli run -- -key YOUR_API_KEY
```

### 5. Check Node Logs:
```
screen -r datagram
```
- To detach the screen without stopping the process, Press: `Ctrl + A`, then `D`
  
![image](https://github.com/user-attachments/assets/ed81859d-6eca-4e6c-9ceb-7f4c61c951c5)

### 6. For Windows and MAC:

![image](https://github.com/user-attachments/assets/b4e053d2-7720-434a-b5b8-774fbbdde32f)

### 7. Confirm Participation
- Submit the [Early Alpha Form](https://docs.google.com/forms/d/e/1FAIpQLSevC3QjAx4xdNysKoRtCSR_5cAUtVBhoNu3XoCrQBIOYVQN8A/viewform) with your X and Discord info.

![image](https://github.com/user-attachments/assets/95fb4d52-aa4b-491e-8cb7-ed1d0dc9586f)

### Rewards Note:
- After ~6 hours of uptime, your node starts earning points.
- Keep it running 24/7 to maximize rewards!

### FAQ
- Q: Where do I find the API Key?
- A: Go to **Dashboard** > **Wallet** > **Licenses** and copy the **key**.

- Q: Does the **node** need to run **24/7**?
- A: Yes, for **optimal rewards**.
