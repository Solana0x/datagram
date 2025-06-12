# Datagram Node 

![image](https://github.com/user-attachments/assets/727f2c92-7017-4e64-807f-6f643952f09f)

##  Step 1: Register for a Datagram Account

Before running the node, you need to register an account and obtain your API Key.

1. Visit the registration page:  
    **[https://dashboard.datagram.network?ref=183600408](https://dashboard.datagram.network?ref=183600408)**

2. Sign up using your **email address**.

3. After logging in, **copy your API Key** from the dashboard.

---

##  Step 2: Create Folder and Download Datagram CLI

1. Download the `datagram-cli` binary:

   ```bash
   wget -O datagram-cli https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux
   ```

2. Make the file executable:

   ```bash
   chmod +x datagram-cli
   ```

---

##  Step 3: Run Datagram CLI with Your API Key

1. Start a new `screen` session to keep the program running in the background:

   ```bash
   screen -S datagram
   ```

2. Run the CLI with your API Key (replace `YOUR_API_KEY`):

   ```bash
   ./datagram-cli run -- -key YOUR_API_KEY
   ```

3. To detach from the screen session without stopping the process:

   Press:
   ```
   Ctrl + A then D
   ```

4. To reattach to the screen session:

   ```bash
   screen -r datagram
   ```

---

##  Additional Notes

- Make sure your API Key is valid and active.
- Use `screen` so the node keeps running even after you log out.
- You can always reattach to the screen to monitor the node.

## FOR ANY KIND OF HELP CONTACT : ` 0xphatom ` on Discord  https://discord.com/users/979641024215416842

# Socials 

# Telegram - [https://t.me/phantomoalpha](https://t.me/phantomoalpha)
# Discord - [https://discord.gg/pGJSPtp9zz](https://discord.gg/pGJSPtp9zz)
