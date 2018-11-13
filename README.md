# MURKYWATERS

# IPS Testing

* MDR Fail-over
* HA Sensor Fail-over

## Custom Sigs

### UDS Signature Detection

### Snort Signature Detection

```snort
alert tcp any any -> any any (msg: "Development Mode Webserver Security Risk WEBBRICK"; flow:to_server,established; content:"WEBrick/1."; sid:1000001; rev:1)
```

# ATD Testing

### YARA BH Detection

- Identify Regex Key Read 
- Regex Key - 
`Software\DemonTatham`

### YARA BIN Detection

- Identify BIN String from Connection KeepAlive Option "EVIL_100001 option" 1..9 is stepped.
