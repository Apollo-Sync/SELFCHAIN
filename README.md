
# 🧊 SELFChain

x: [https://twitter.com/selfchainxyz](https://twitter.com/selfchainxyz)\
website: [https://selfchain.xyz/](https://selfchain.xyz/)\


## **Building from source**

```
sudo apt update && sudo apt upgrade -y
sudo apt install curl tar wget clang pkg-config libssl-dev libleveldb-dev jq build-essential bsdmainutils git make ncdu htop lz4 screen unzip bc fail2ban htop -y
```
## **INSTALL GO**

```
cd $HOME
VER="1.20.5"
wget "https://golang.org/dl/go$VER.linux-amd64.tar.gz"
sudo rm -rf /usr/local/go
sudo tar -C /usr/local -xzf "go$VER.linux-amd64.tar.gz"
rm "go$VER.linux-amd64.tar.gz"
[ ! -f ~/.bash_profile ] && touch ~/.bash_profile
echo "export PATH=$PATH:/usr/local/go/bin:~/go/bin" >> ~/.bash_profile
source $HOME/.bash_profile
[ ! -d ~/go/bin ] && mkdir -p ~/go/bin
```

