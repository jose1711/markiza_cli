# markiza_cli

Play live video stream from Markiza TV (www.markiza.sk) using mpv player

# Setup

Playback requires free registration at www.markiza.sk. After registraion place your credentials
to .markizarc in your home directory as described below:

```
markiza_mail=user@mail
markiza_pass=password
```

# Invocation:
```
markiza_cli [-url] [channel_name] [optional mpv parameters]
```
 
`channel_name` may be:
 ```
 markiza (default if not specified)
 dajto
 doma
 ```
