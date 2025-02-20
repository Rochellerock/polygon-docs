
This document provides a comprehensive list of seeds and bootnodes for both the Mainnet and Amoy Testnet, including Bor and Heimdall.


!!! info
    
    You don't need to configure seeds separately for the Amoy Testnet, as they are already included in the genesis file. However, if you're having trouble connecting to peers, feel free to use them.

## PoS mainnet

!!! info "Selecting a URL"

    Triple-click a URL to select it, and then copy it using the appropriate keyboard shortcut.

### Bor

```bash
enode://b8f1cc9c5d4403703fbf377116469667d2b1823c0daf16b7250aa576bacf399e42c3930ccfcb02c5df6879565a2b8931335565f0e8d3f8e72385ecf4a4bf160a@3.36.224.80:30303

enode://8729e0c825f3d9cad382555f3e46dcff21af323e89025a0e6312df541f4a9e73abfa562d64906f5e59c51fe6f0501b3e61b07979606c56329c020ed739910759@54.194.245.5:30303
```

### Heimdall

```bash
1500161dd491b67fb1ac81868952be49e2509c9f@52.78.36.216:26656

dd4a3f1750af5765266231b9d8ac764599921736@3.36.224.80:26656

8ea4f592ad6cc38d7532aff418d1fb97052463af@34.240.245.39:26656

e772e1fb8c3492a9570a377a5eafdb1dc53cd778@54.194.245.5:26656

6726b826df45ac8e9afb4bdb2469c7771bd797f1@52.209.21.164:26656
```

## Amoy testnet

### Bor

```bash
enode://383ec39eb7f7e23538ea846f502602632110a6bcfc7521bfc2b8833f5a190779507d006b28650d83674b75d188cb36bcb3c3e168a0f2b3d98f9a651cc6603146@52.214.229.208:30303

enode://bce861be777e91b0a5a49d58a51e14f32f201b4c6c2d1fbea6c7a1f14756cbb3f931f3188d6b65de8b07b53ff28d03b6e366d09e56360d2124a9fc5a15a0913d@54.217.171.196:30303

enode://a4a387ad423a2fd0d652808b270082250d3c616b7e8537209584ebad4806dd50ef8dc66a371c85c7f55e6c1f53747edbb11055c8073cfacf312047eaeb328f58@54.171.220.164:30303

enode://4a3dc0081a346d26a73d79dd88216a9402d2292318e2db9947dbc97ea9c4afb2498dc519c0af04420dc13a238c279062da0320181e7c1461216ce4513bfd40bf@13.251.184.185:30303

enode://e8fe33b52f90d4bc7a4e75800945df449d1a091bd347c9f11cd1dbcd98ea28cb4c231cb3b1c6feacdabca2aa91f1a6744724b44edc9382c107968792abdef261@52.74.18.182:30303

enode://b240f1f18e8f3cc61df96a164ba215ea6fc3f00717e4300da6283362a0438bda53f81ecc24c575ff130066d42096319fa027c952681bbb4f003e0bdd5d5b4e61@52.76.37.145:30303

enode://de55d16b6e1fca28cdd3d11eb0dd89e3b77b96d4722172bd5e04ac255922324076a87748e97bc021af2307dccbb5ef8062389cfcba1845f77219eee7935dea9f@52.74.125.36:30303

enode://7f2272685fc3e31c8e43c7687dda43ea3192fd310ba01efcb7811d5dc7ad5a64402ea8cd827650e573a174cf29bb69331dffcca6f0b9894ef17eeafabd97a41d@47.128.184.10:30303

enode://c66e12243b425b63528dd8b1ce87f2f7fbc85f35485e2d8bf6bbf0ec0dcd05b3a582ef62daadbde061b58058735788335d09ed972a451242b9943b85d323c239@63.32.214.97:30303

enode://bd56c0f00dd37e14ae2b84f5eb50e357d3a2d326bdbb0cbb987411268b3f132288f6c86157fc132c6902d18b9be0de8bbdcd12d926e16232ebadd8e274aae780@52.208.81.179:30303

enode://2f015d5b1571165975382281a2117a9b514e1b38e87a8116596fc9b3b121a93cfb238eb6f7b3ae30cf9c0154384372745ce9edc09cbc30526ab7e2059f57ddee@54.74.160.230:30303
```

### Heimdall

```bash
9b62e5df9711ff0124774295c3a0159a829a9ea8@52.214.229.208:26656

eb57fffe96d74312963ced94a94cbaf8e0d8ec2e@54.217.171.196:26656

b217aaadef7a5f409722e03c5c3b463b48fbb1f3@54.171.220.164:26656

080dcdffcc453367684b61d8f3ce032f357b0f73@13.251.184.185:26656

3fde1fba0bba390fa79bef2393104758b302bf5a@52.74.18.182:26656

7cd4b5fd12c1c7debb7dc9938013b4e9470a5add@52.76.37.145:26656

a4601f540c901112e3c718dd834de5537d8343e8@52.74.125.36:26656

bda8943b47d96ccf8f36dc5d306450926906571b@47.128.184.10:26656

21029acc7239d622019a4213ba9c58aa862b762d@63.32.214.97:26656

46ee7b8d33ade8aa41fd1b96f26a1f275721ee49@52.208.81.179:26656
```

Alternatively, you can find more seeds [here](https://docs.stakepool.dev.br/polygon/live-peers).

## Enhancing Bor Peering with DNS Discovery

To further enhance bor peering capabilities, the DNS discovery flag can be utilized. The ENR trees for the mainnet and Amoy testnet are provided below:

* **Mainnet** - `enrtree://AKUEZKN7PSKVNR65FZDHECMKOJQSGPARGTPPBI7WS2VUL4EGR6XPC@pos.polygon-peers.io`
* **Amoy Testnet** - `enrtree://AKUEZKN7PSKVNR65FZDHECMKOJQSGPARGTPPBI7WS2VUL4EGR6XPC@amoy.polygon-peers.io`

### Configuration Steps

To configure DNS discovery, follow these steps:

1. Edit your `config.toml` file:
   * Locate the `[p2p]` section.
   * Set `maxpeers` to:
       * 2000 for Mainnet
       * 500 for Amoy Testnet
   * Set `maxpendpeers` to:
       * 500 for Mainnet
       * 100 for Amoy testnet
2. Add the DNS under `[p2p.discovery]` section.

!!! note

    Increasing the number of peers can significantly enhance node connectivity, enabling connection to hundreds of peers almost instantly. However, please be aware that this adjustment may lead to increased bandwidth usage. Adjusting maxpeers and maxpendpeers is optional but can improve peering efficiency. Read more [here](https://forum.polygon.technology/t/introducing-our-new-dns-discovery-for-polygon-pos-faster-smarter-more-connected/19871).
