# Shelly

**Automatic tool in `bash` to create `reverse shell`**

![](/1.png)

---

**Run**
```cmd
root@kali:~# Shelly eth0 443 bash
```
```cmd
root@kali:~# Shelly tun0 443 bash
```
```cmd
root@kali:~# Shelly enp0s3 443 bash
```

**Download / Install**
```cmd
root@kali:~# wget "https://raw.githubusercontent.com/d4t4s3c/Shelly/main/Shelly.sh" -O /opt/Shelly.sh
root@kali:~# chmod +x /opt/Shelly.sh
```

**Add Alias**
- Bash --------> `root@kali:~# echo "alias Shelly='/opt/Shelly.sh'" >> /root/.bashrc`
- Zsh ---------> `root@kali:~# echo "alias Shelly='/opt/Shelly.sh'" >> /root/.zshrc`
- Powerlevel --> `root@kali:~# echo "alias Shelly='/opt/Shelly.sh'" >> /root/.p10k.zsh`

(Close terminal and reopen again)

---