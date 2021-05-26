## darknet-dataset-2020
This dataset contains **user behavior** traffic in Tor, I2P, ZeroNet and Freenet.

<img src="pic\fig1.png" alt="image" width="100" />         <img src="pic\fig3.png" alt="image" width="100" /> <img src="pic\fig2.png" alt="image" width="100" /> <img src="pic\fig4.png" alt="image" width="100" /> 

We divide darknet user behaviors in 8 categories: Browsing, Chat, E-mail, Audio-streaming, Video-streaming, File Transfer, P2P and VoIP.  We investigated the commonly used applications in Tor, I2P, ZeroNet, Freenet to simulate various user behaviors.

After capturing pcap,  we use CICFlowMeter for feature extraction. Since our user behavior hierarchical classifier consists of 6 local classifiers, we divide the dataset into 6 csv files. The statistics of traffic data are shown in the following table.

|         | Browsing | Chat | Email | File Transfer | P2P  | Audio | Video | VoIP | Total |
| :-----: | :------: | :--: | :---: | :-----------: | :--: | :---: | :---: | :--: | :---: |
|   Tor   |   1281   | 841  |  553  |     1077      | 1018 | 1567  | 1703  | 592  | 8632  |
|   I2P   |   1921   | 442  | 1084  |     1791      | 2910 |   -   |   -   |  -   | 8148  |
| ZeroNet |   7972   | 1531 |  352  |     2157      | 1394 |  820  | 1251  |  -   | 15477 |
| Freenet |   4990   | 1123 | 2980  |     4897      |  -   |   -   | 2397  |  -   | 16387 |

The original pcap file was not uploaded due to the large file size.  If you need original pcap file for research, please contact us.

## Contact Info

Yuzong Hu

huyz97@sjtu.edu.cn



## Research paper
We present our approach and the findings of this work in the following research paper:

Y. Hu, F. Zou, L. Li and P. Yi, "Traffic Classification of User Behaviors in Tor, I2P, ZeroNet, Freenet," *2020 IEEE 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom)*, 2020, pp. 418-424, doi: 10.1109/TrustCom50675.2020.00064.

If you use our work in a scientific publication, we would appreciate citations using this Bibtex entry:
``` tex
@INPROCEEDINGS{9343185,
  author={Hu, Yuzong and Zou, Futai and Li, Linsen and Yi, Ping},
  booktitle={2020 IEEE 19th International Conference on Trust, Security and Privacy in Computing and Communications (TrustCom)}, 
  title={Traffic Classification of User Behaviors in Tor, I2P, ZeroNet, Freenet}, 
  year={2020},
  volume={},
  number={},
  pages={418-424},
  doi={10.1109/TrustCom50675.2020.00064}}
```