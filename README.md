# Sovereign-Rollup-Greetings
Today, I'm gonna show how you can create a Greetings module on Sovereign Rollup with Python

**Firstly, we start with system updates**

```
sudo apt update && sudo apt upgrade -y

sudo apt install curl tar wget clang pkg-config libssl-dev jq build-essential \
git make ncdu -y
```

**Continue with Go download/update**

```
ver="1.18.2"
cd $HOME
wget "https://golang.org/dl/go$ver.linux-amd64.tar.gz"
sudo rm -rf /usr/local/go
sudo tar -C /usr/local -xzf "go$ver.linux-amd64.tar.gz"
rm "go$ver.linux-amd64.tar.gz"
echo "export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin" >> $HOME/.bash_profile
source $HOME/.bash_profile
go version
```


**Then, you need to create a main.go file on your server**

```
mkdir my_rollup
cd my_rollup
touch main.go
```

** Open "winscp" connect your server, and follow this path <code>/root/my_rollup</code>

 <img src="(https://www.hizliresim.com/p99ouq7)" width="320" height="180">
