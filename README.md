
```
https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_arm64-v8a.apk
```

```
pkg update && pkg upgrade -y
pkg install libjansson -y

pkg install wget -y

mkdir ccminer && cd ccminer

wget https://raw.githubusercontent.com/Septahadif/pre-compiled/generic/ccminer

wget https://raw.githubusercontent.com/Septahadif/pre-compiled/generic/config.json

wget https://raw.githubusercontent.com/Septahadif/pre-compiled/generic/start.sh

chmod +x ccminer start.sh

~/ccminer/start.sh
```

```
3. Close ccminer with:
```

```
CTRL + c
```

