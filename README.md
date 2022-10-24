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
apt install -y build-essential libssl-dev cmake
```
*Rust Installation*

***Choose 1 from those options that will appear during installation***
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
![z1](https://user-images.githubusercontent.com/100621008/197636751-0132be53-ae44-48d3-944e-203ef7fcdd38.jpg)

*Bazuka Installation*
```
apt install git
git clone https://github.com/zeeka-network/bazuka
````
```
source "$HOME/.cargo/env"
```
*path installation*
```
cd bazuka
cargo install --path .
```
***edit and save the below (seed phrase) as you wish (this is your secret key to reach your wallet)***
```
bazuka init --seed (seed phrase) --network chaos --node 127.0.0.1:8765
```
**open screen**
```
screen -S bazuka
```
***edit the (your IP address) and (your discord handle) sections in the code below with your own information***
```
bazuka node --listen 0.0.0.0:8765 --external (your IP address):8765  --network chaos --db ~/.bazuka-chaos --bootstrap 144.91.101.166:8765 --bootstrap 45.67.228.84:8765 --bootstrap 152.228.155.120:8765 --bootstrap 80.87.202.42:8765 --bootstrap 148.251.1.124:8765 \ --discord-handle "(your discord handle)"
```



