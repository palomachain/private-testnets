# Install Binaries

## `paloma`

```bash
cd ~
mkdir paloma_0.0.1_linux_amd64
cd paloma_2.0.01_linux_amd64
wget https://github.com/palomachain/paloma/releases/download/v0.0.1-alphawasmd3/paloma_0.0.1-alphawasmd3_Linux_x86_64.tar.gz
tar -xvf paloma_0.0.1-alphawasmd3_Linux_x86_64.tar.gz
sudo cp paloma /usr/bin/palomad
cd ~
```

## install libwasmvm.x86_64.so

```bash
wget -O /usr/lib/libwasmvm.x86_64.so https://github.com/CosmWasm/wasmvm/raw/main/api/libwasmvm.x86_64.so
```
