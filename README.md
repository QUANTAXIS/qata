# QATA: Data Maintainance for Quantitative Investment

Auto updates stock/future data on your raspberry pi

## systemd service and timer

```
cp qata.service /etc/systemd/system/
cp qata.timer /etc/systemd/system/
systemctl enable qata.timer
systemctl start qata.timer
```
