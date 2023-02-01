# Rock5B Naive Pwm Fan
For official fan from allnet installed on Rock Pi 5 Model B

## How to use
1. Clone or download this repo
1. Ensure you are at root shell
1. Copy file 'fan_pwm' to '/usr/local/bin/.': `cp fan_pwm /usr/local/bin/.`
1. Allow executable if needed: `sudo chmod +x /usr/local/bin/fan_pwm`
1. Copy service file 'fan_pwm.service' to '/etc/systemd/system/.': `cp fan_pwm.service /etc/systemd/system/.`
1. Reload service: `systemctl daemon-reload`
1. Start service: `systemctl start fan_pwm`
1. Enable service to start after boot: `systemctl enable fan_pwm`
```
git clone https://github.com/FantasyGmm/Rock5B_Pwm_Fan
cd Rock5B_Pwm_Fan
cp fan_pwm /usr/local/bin/
sudo chmod +x /usr/local/bin/fan_pwm
cp fan_pwm.service /etc/systemd/system/.
systemctl daemon-reload
systemctl start fan_pwm
systemctl enable fan_pwm
cd ..
```
