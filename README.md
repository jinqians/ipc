# ipc
定时更换家宽ip，检测是否被墙

## 使用
- `wget https://raw.githubusercontent.com/jinqiannan/ipc/main/ipc.sh `
- `chmod +x ipc.sh`
- `vi ipc.sh` **#填入自己的telegram api，chatID，更换IP的api**
- `./ipc.sh`
## 设置定时任务
- `crontab -e`
- `*/30 * * * * /bin/bash /root/ipc.sh` **每30分执行一次**
