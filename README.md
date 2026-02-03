# OpenClaw Whatapp Assistant

## Description:

## Installation:

I flashed a Raspberry Pi 5 with Ubuntu Server, using the rpi-imager. This will be the OpenClaw server, the hardware requirements aren't high because the only thing being hosted on our machine is the AI Agent (OpenClaw). the AI model (ChatGPT 5.2) itself will be accessed via API.

After setting up the Raspberry Pi with Ubuntu + SSH I remoted-in and proceeded to install OpenClaw (ClawdBot/MoltBot) according to the [documentation](https://docs.openclaw.ai/install) on there website:

```bash
curl -fsSL https://openclaw.ai/install.sh | bash
```
> This might change in the future, please check the documentation.

At the end of the installation process we are greeted with a configuration window. Read the warning and accept the security risk (I will touch on security concerns at the end). Then continue to select your AI of choice and communication channel -- Whatsapp -- in our case.

## Configuration:

~
*I highly recommend using a password manager to store and manage all the accounts and API keys you are going to create. It's not necessary, but will save time and energy.*
~
### Model Setup:

This is where you decide which AI model to use, basically picking the 'brain' of your AI assistant. If your in doubt or can't decide which one I recommend going with the latest openAI ChatGPT model, it will most likely be a well rounded model -- average at everything.

1. Create a [OpenAI Platform](https://platform.openai.com/apps-manage) account.
2. Create an API Key for OpenClaw.
3. Add credits to account.
### Channel Setup (Whatsapp):

### Web Tools Setup:

Enable your AI assistant to do Web Searches.

1. Create a [Brave account](https://brave.com/search/api/) and subscribe to the free API.
![[Pasted image 20260203171804.png]]
2. Add API key to 

### Skills Setup:

#### Google Calendar Integration: 