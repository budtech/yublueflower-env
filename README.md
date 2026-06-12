## Required

- **Operating System**: Linux x86_64 (WSL with Kali Linux)
- **Dependencies**: wget, tar, bash

## Installation

```bash
git clone https://github.com/budtech/yublueflower-env.git
cd yublueflower-env
chmod +x init-env
./init-env
source ~/.profile
```

## Usage

### init-env

```bash
bash ./init-env
```

### vscn

```bash
bash ./vscn
```

```bash
vscn --url https://example.com
```

### xast

```bash
bash ./xast
```

```bash
xast --url https://example.com
```

```bash
xast --url https://example.com --live-session "Cookie: session=xxx"
```

```bash
xast --url https://example.com --extended-workflows
```

### template-sync

```bash
bash ./template-sync
```

### Log

```bash
tail -f ~/template-sync.log
```

### Schedule

The tool automatically creates a cron job that synchronizes templates every day at **01:00 JST**.

```bash
crontab -l
```

Example:

```cron
0 1 * * * /home/<user>/.local/bin/template-sync >/dev/null 2>&1
```

## License

`yublueflower` is made with ♥ and released under the MIT license.
