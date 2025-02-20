# ᝰ.ᐟ TENEO-NODE

Tool được phát triển bởi nhóm tele Airdrop Hunter Siêu Tốc (https://t.me/airdrophuntersieutoc)

## 🚨 Attention Before Running Teneo Cli Version

I am not `responsible` for the possibility of an account being `banned`, due to running node in the CLI, because Officially `Teneo Node Beta` does not provide an option for the CLI version, only with the Chrome extension.
but `I think` there is no reason to ban the account, because this is not cheating, I didn't change anything in the script (Heartbeats 15 minutes, maximum teneo points 25, maximum points per day 2400)

## 📎 Teneo Node cli version Script features

- Auto Register (auto ref)
- AutoLogin (get token)
- Auto verify emails (need get 6 digits code)
- Auto claim ref reward
- Running Node (ping each 15 minutes)
- AutoReconnect

## ✎ᝰ. RUNNING

- Clone Repository

```bash
git clone https://github.com/Hunga9k50doker/teneo.git
cd teneo
```

- Install Dependency

```bash
npm install
```

- Run the script

```bash
node main.js
```

## run for multy accounts:

- Manual put token in `tokens.txt` 1 line 1 token
  ```bash
  nano tokens.txt
  ```
- proxy (optional) in `proxies.txt`
  ```bash
  nano proxies.txt
  ```

### Auto get tokens:

- fill `accounts.txt` format : `test@gmail.com|password123` 1 line 1 account
  ```bash
  nano accounts.txt
  ```
- run to get tokens, register, verify

  ```bash
  node setup.js
  ```
