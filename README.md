# systemd-certbot-renew

Systemd unit configuration files which run `certbot renew` once a month.
Nginx will be paused during renew.

```sh
cd systemd/system/
sudo cp * /etc/systemd/system/

sudo systemctl start certbot.timer
sudo systemctl enable certbot.timer
```

## License

These configuration files are released into the public domain. You can freely
use them.
