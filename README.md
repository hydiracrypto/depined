### This project automates the registration and configuration process on https://app.depined.org/ by integrating token and proxy settings.

### Get Code Activavacy On
https://t.me/DePINedCommunity

## Features
- Automates registration on the DePINed application.
- Retrieves activation codes from the Telegram community.
- Automatically integrates proxy and application tokens.

...

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/hydiracrypto/depined.git
   cd depined
   ```
2. **Install Dependencies**
   ```
   npm install
   ```

   
3. **fill in proxy & Tokens**
   ```
   nano proxy.txt
   ```
   ctrl X Y Enter
   ```
   nano tokens.txt
   ```
   How to get Tokens?:
   F12 Or inspect look for the address prefix eyxx then paste it in the tokens.txt file
   
4. **Create and Use Screen**
   ```
   screen -S depined
   ```

5. **Run the Application**
   ```
    npm start
   ```

Detach from the screen session without closing it: Press Ctrl + A, then press D to detach from the screen session.

6. ***Reattach to the running screen session**:
   ```
    screen -r depined
   ```

