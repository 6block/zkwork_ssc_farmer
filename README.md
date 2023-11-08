# ZKWork Subspace farmer

A git repository for ZKWork Subspace farmer release versions

* Download releases : https://github.com/6block/zkwork_ssc_farmer/releases
* Discord Group :  https://discord.com/invite/pKufwyjGFF
* Twitter : https://x.com/ZKWorkHQ

### We are on Gemini-3g incentivized testnet with official version `gemini3g-nov-07`

### Start Farming

#### 1. Choose and download your cpu version on release page

#### 2. Unzip

#### 3. Start farming

`./subspace-farmer farm --reward-address <YOURADDRESS> --pool ws://ssc.hk.zk.work:50002 --worker-name myfarmer path=./store,size=5T`

### General Options

 Parameter                   | Description                                               
|-----------------------------|-----------------------------------------------------------|
| -h [ --help ]               | Help screen                                               |
| --reward-address arg               | Subspace testnet Address  |
| --pool arg               | ZKWork Subspace pool (ws://ssc.hk.zk.work:50002)             |                                            |
| --worker-name arg | Worker name                                               |
| -v [ --version ]            | Print ZKWork Subspace farmer version number                          |

