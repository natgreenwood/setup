```
sudo apt update && sudo apt upgrade -y && sudo apt autoremove -y
```

Install BitWarden Secrets Manager
```
sudo apt install curl -y
curl https://bws.bitwarden.com/install | sh
```

Optional: Install Claude Code
```
curl -fsSL https://claude.ai/install.sh | bash
source ~/.bashrc
claude /login
```

Optional: Install Codex
```
curl -fsSL https://chatgpt.com/codex/install.sh | sh
source ~/.bashrc
codex
```

Optional: Install Multica
```
curl -fsSL https://raw.githubusercontent.com/multica-ai/multica/main/scripts/install.sh | bash
source ~/.bashrc
multica setup
```


