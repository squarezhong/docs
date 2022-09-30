# 配置oh-my-zsh

1. **安装oh-my-zsh**

curl方式

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

或者使用wget：

`sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"`

1. **安装插件**

```shell
brew install zsh-syntax-highlighting
brew install zsh-autosuggestions
```

在 `～/.zshrc` 尾部，插入：

```shell
source /opt/homebrew/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh
source /opt/homebrew/share/zsh-autosuggestions/zsh-autosuggestions.zsh
```

1. **生效配置**

```shell
source ~/.zshrc
```