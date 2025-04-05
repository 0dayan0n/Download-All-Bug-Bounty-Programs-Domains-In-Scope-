#### Commands:

```shell
cat domains.txt | awk -F '.' '{print $(NF-1)"."$NF}' | grep -Eo '([a-zA-Z0-9-]+\.)+[a-zA-Z]{2,}' | sort -u > main_domains
```
```shell
 grep -Eo '\b([0-9]{1,3}\.){3}[0-9]{1,3}\b' domains.txt > ips.txt
```

# Watch video and lookup for mass scans you can perform on this
Full Video:

[![Youtube Video](http://img.youtube.com/vi/8kOMwPGWXbU/0.jpg)](https://www.youtube.com/shorts/8kOMwPGWXbU)

#### This repository is for educational purposes only

# DISCLAIMER 📛 
- This repository is for ethical purposes and to use the scripts to learn and improve in python :)
- I am not responsible for any damage that may be done with this.

# 🛠️ Coding Services - Contact 🛠️
- **Telegram:** https://t.me/zer0dayanon
- **Discord:** @0dayanon
