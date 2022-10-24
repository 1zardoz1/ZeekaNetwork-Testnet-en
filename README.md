<h1 align="center">ZeekaNetwork-The Chaos Testnet-1</h1>

![zeeka picture y](https://user-images.githubusercontent.com/100621008/197632354-51d0476c-39d3-4168-89c3-ea088634c60e.jpg)

*System Requirements*
|  CPU  |  RAM  |
|-------|-------|
|   2   |   4   |

*Installation*
```
apt update && apt upgrade -y 
```
```
apt install git
```
```
apt install screen 
```
```
apt install -y libssl-dev cmake
```
*Rust Installation*

***Choose 1 from those options that will appear during installation***
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
![z1](https://user-images.githubusercontent.com/100621008/197636751-0132be53-ae44-48d3-944e-203ef7fcdd38.jpg)

*Clone bazuka*
```
git clone https://github.com/zeeka-network/bazuka
````
```
source "$HOME/.cargo/env"
```
*path installation*

***takes a long time and will look like below***
```
cd bazuka
apt install -y g++
cargo install --path .
```
![z3](https://user-images.githubusercontent.com/100621008/197649567-c4afb444-25e4-42c1-93b3-07fefdb50055.jpg)

**open screen**
```
screen -S bazuka
```
***edit and save the below (seed phrase) as you wish (this is your secret key to reach your wallet)***
```
bazuka init --seed (seed phrase) --network chaos --node 127.0.0.1:8765
```
***edit the (your IP address) and (your discord handle) sections in the code below with your own information***
```
bazuka node --listen 0.0.0.0:8765 --external (your IP address):8765  --network chaos --db ~/.bazuka-chaos --bootstrap 144.91.101.166:8765 --bootstrap 45.67.228.84:8765 --bootstrap 152.228.155.120:8765 --bootstrap 80.87.202.42:8765 --bootstrap 148.251.1.124:8765 \ --discord-handle "(your discord handle)"
```
***You will see wallet address and wallet zk address and don't forget to save them***

![z4](https://user-images.githubusercontent.com/100621008/197651409-36ddc021-462c-4261-9d16-e561280c2e0e.jpg)

* [Explorer linki](http://152.228.155.120:8000/)
* [Web Site](https://zeeka.network/)
* [Discord](https://discord.com/channels/923604493378154496/923604493843697698)





