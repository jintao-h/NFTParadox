## Abstract

Unlike fungible tokens (e.g., cryptocurrency), a Non-Fungible Token (NFT) is unique and indivisible. As such, they can be used to authenticate ownership of digital assets (e.g., a photo) in a decentralized fashion. Given that NFTs have generated significant media attention since 2021, we perform a large-scale measurement study of the NFT ecosystem. We collect over 242M transfer logs and over 97M marketplace transactions until Aug 1st, 2023, by far the largest NFT dataset, to the best of our knowledge.  We characterize the on-chain behavior of NFTs and their trading across five major marketplaces. We find that, although the NFT ecosystem is growing rapidly, it is driven by a relatively small set of dominant centralized players, with suspicious trades activities, e.g., over 23\% of the monetary volume is generated by malicious wash trading and the ecosystem has experienced over 157K cases of NFT arbitrage, with a total sum of over \$25M USD profit. Our observations motivate the need for more research efforts in the NFT security analysis.

## About the Dataset

There are 2,722 seller and buyer pairs in wash_trading_users.csv in total. The dataset includes the addresses of the sellers and buyers, separately. Also, we record the trading volumes for each pair.

There are 629 arbitrage bots in arbitrage.csv in total. And the dataset includes contract addresses of the arbitrage bots, the total arbitrage profits of per bot, and the total arbitrage volumes of per bot. 

## Citation

If you use our dataset in your research, please cite our paper: 

```
@inproceedings{huang2024unveiling,
  title={Unveiling the Paradox of NFT Prosperity},
  author={Huang, Jintao and Xia, Pengcheng and Li, Jiefeng and Ma, Kai and Tyson, Gareth and Luo, Xiapu and Wu, Lei and Zhou, Yajin and Cai, Wei and Wang, Haoyu},
  booktitle={Proceedings of the ACM on Web Conference 2024},
  pages={167--177},
  year={2024}
}
```

