# snippets

## Install No-IP DUC

```
#%BEGIN install-no-ip-duc
sudo apt-get install -y build-essential
pushd /usr/local/src
sudo wget http://www.no-ip.com/client/linux/noip-duc-linux.tar.gz
sudo tar xzf noip-duc-linux.tar.gz
cd noip-2.1.9-1
sudo make
sudo make install
popd
#%END
```
