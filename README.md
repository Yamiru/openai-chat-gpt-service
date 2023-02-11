# Running your Node.js App(chat-gpt/OPENAI) With Systemd

Creating a Linux service with systemd 



## Documentation

[Install Documentation](https://medium.com/codingthesmartway-com-blog/creating-a-discord-chatbot-with-chatgpt-a-comprehensive-guide-for-beginners-eee2ffb18d73)


## Installation

Run npm with systemd service

```bash
  sudo nano /etc/systemd/system/openai.service
  -paste from my openai.service
  -edit user User=
  sudo systemctl daemon-reload 
  sudo systemctl status openai.service
  sudo systemctl enable openai.service
  sudo systemctl start openai.service
  
```
    
