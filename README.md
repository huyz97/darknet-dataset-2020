## darknet-dataset-2020
This dataset contains **user behavior** traffic in Tor, I2P, ZeroNet and Freenet.

<img src="pic\fig1.png" alt="image" style="zoom:10%;" />         <img src="pic\fig3.png" alt="image" style="zoom:10%;" /> <img src="pic\fig2.png" alt="image" style="zoom:10%;" /> <img src="pic\fig4.png" alt="image" style="zoom:10%;" /> 

We divide darknet user behaviors in 8 categories: Browsing, Chat, E-mail, Audio-streaming, Video-streaming, File Transfer, P2P and VoIP.  We investigated the commonly used applications in Tor, I2P, ZeroNet, Freenet to simulate various user behaviors.

After capturing pcap,  we use CICFlowMeter for feature extraction. Since our user behavior hierarchical classifier consists of 6 local classifiers, we divide the dataset into 6 csv files. The statistics of traffic data are shown in the following table.

|         | Browsing | Chat | Email | File Transfer | P2P  | Audio | Video | VoIP | Total |
| :-----: | :------: | :--: | :---: | :-----------: | :--: | :---: | :---: | :--: | :---: |
|   Tor   |   1281   | 841  |  553  |     1077      | 1018 | 1567  | 1703  | 592  | 8632  |
|   I2P   |   1921   | 442  | 1084  |     1791      | 2910 |   -   |   -   |  -   | 8148  |
| ZeroNet |   7972   | 1531 |  352  |     2157      | 1394 |  820  | 1251  |  -   | 15477 |
| Freenet |   4990   | 1123 | 2980  |     4897      |  -   |   -   | 2397  |  -   | 16387 |

The original pcap file was not uploaded due to the large file size.  If you need original pcap file for research, please contact us.

### Contact Info

Yuzong Hu

huyz97@sjtu.edu.cn