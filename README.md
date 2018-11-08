# chainlink-hello-world
First Exploration into chainlink!
Chainlink is one of the most hyped cryptocurrencies because it offers API requests for smart contracts, first in Ethereum and possibly moving to other platforms like Hyperledger Fabric.
Chainlink can be tested in the Ropsten, Rinkeby, and Kovan testnets but we'll use Ropsten since it is most similar to the ethereum network. 
https://docs.chain.link/docs/assumptions
https://docs.chain.link/docs/install-metamask
https://docs.chain.link/docs/your-first-request

```
sudo apt update && sudo apt upgrade -y
sudo reboot
sudo apt install git make gcc g++ libltdl-dev curl python pkg-config nfs-common -y
curl -fsSL test.docker.com | sh
sudo usermod -aG docker $USER
exec sudo su -l $USER

sudo curl -L https://github.com/docker/compose/releases/download/1.23.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
wget https://nodejs.org/dist/v11.1.0/node-v11.1.0-linux-x64.tar.xz
tar -xf node-v11.1.0-linux-x64.tar.xz
mv node-v11.1.0-linux-x64/ .node/
echo 'export PATH=~/.node/bin:$PATH' >> ~/.profile
source .profile
wget https://dl.google.com/go/go1.11.linux-amd64.tar.gz
sudo tar -C /usr/local -xvf go1.11.linux-amd64.tar.gz
echo 'export GOPATH=/opt/go' >> ~/.profile
echo 'export GOBIN=/opt/go/bin' >> ~/.profile
echo 'export PATH=/usr/local/go/bin:$PATH' >> ~/.profile
source ~/.profile
sudo mkdir -p /opt/go/bin
sudo mkdir /opt/go/src
sudo chown -R $USER /opt/go

npm install -g npm
npm install -g solc
npm install -g truffle
npm install -g remix-ide
```