# MURKYWATERS

# IPS Testing

* MDR Fail-over
* HA Sensor Fail-over

## Telemetry Test

NSM Manager -> Inegration -> GTI -> test Connection

1.80.0.0 -	1.95.255.255 China 

1.80.1.1 China

## Custom Sigs

Identify the usage of WebBrick, and carve the download from the server.

![Screenshot](meta/webbrick.png?raw=true "Screenshot")

### UDS Signature Detection

### Snort Signature Detection

```snort
alert tcp any any -> any any (msg: "Development Mode Webserver Security Risk WEBRICK"; flow:to_server,established; content:"WEBrick/1."; sid:1000001; rev:1)
```

# ATD Testing

### YARA BH Detection

- Identify Regex Key Read 
- Regex Key - 
`Software\DemonTatham`

### YARA BIN Detection

- Identify BIN String from Connection KeepAlive Option "EVIL_100001 option" 1..9 is stepped.
