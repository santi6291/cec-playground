# cec-playground
cec-command that have worked

## turn tv on

```
echo 'on 0' | cec-client -s RPI
```

## turn tv off

```
echo 'standby 0' | cec-client -s RPI
```

## change input
change `30` to desire hdmi port 

```
echo 'tx ff:82:30:00' | cec-client -s RPI
```

## change input
List connected devices

```
echo 'scan' | cec-client -s -d 1
```
