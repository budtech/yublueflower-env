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

## License

`yublueflower` is made with ♥ and released under the MIT license.
