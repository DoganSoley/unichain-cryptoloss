![image](https://github.com/user-attachments/assets/3d5a3c7a-b85e-48ab-8209-d1a98a796a97)


# Unichain Node Kurulumu

## Minimum Sunucu Gereksinimleri

8 GB RAM

6 GB CPU

100 GB SSD

Ubuntu 22.04

[Contabo](https://contabo.com/en/vps/)'nun Cloud VPS 2'yi alabilirsiniz.

![image](https://github.com/user-attachments/assets/27d3564b-de47-4835-afd1-e1307539d3df)


Ben [Hetzner](https://console.hetzner.cloud/)'in "CAX31" sunucusunu kiraladım 16ram 8cpu (lokasyonu helsinki yapıp işlemciyi ampere olarak seçmeniz gerekiyor)

![image](https://github.com/user-attachments/assets/6cce0142-6953-4f1c-ad75-eaf4a325916e)

Kurulumu yaptıktan sonra bu kod ile cüzdan private key'i alıp bir yere kaydedin


Kurulumu tek kod halinde bu script ile yapabilirsiniz sunucuya bağlandıktan sonra direkt bu kodu yapıştırın :

```
wget https://raw.githubusercontent.com/DoganSoley/unichain-cryptoloss/refs/heads/main/script.sh && chmod +x script.sh && ./script.sh
```

Yükleme bittikten sonra log kontrol için :

```
docker logs -f unichain-node-execution-client-1
```

# ÖNEMLİ !

## Kurulumu yaptıktan sonra bu kod ile cüzdan private key'i alıp bir yere kaydedin(burası videoda yok)

```
nano /root/unichain-node/geth-data/geth/nodekey
```
