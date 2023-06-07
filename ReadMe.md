# Cost-Controllable Ultra-Large-Scale Sign Language (CCUL) Dataset
## Tianjin University
### <u>Dataset Information:</u>
&emsp; Lacking a large-scale dataset is the major obstacle limiting sign language recognition (SLR). To solve above problem, we propose a novel way to construct a SL dataset, called cost-controllable ultra-large-scale sign language (CCUL). We disassemble the sentence into a template part and an entity part. We collect template videos and entity videos, respectively. Then template videos and entity videos are reassembled to produce more combined videos, which serve as the training set. Meanwhile, we collect complete videos as a test set to verify the performance of the SLR model.

&emsp; The CCUL contains 297 entity sentences, 60 template sentences and 3,004 complete sentences. Each entity/template component is performed by 10 signers for 10 times. Therefore, the number of entity videos is 297×10×10=29,700, and the number of template videos is 60×10×10=6,000. For complete component, 5 signers participate in the collection, and each complete sentence is collected for 2 times. Hence, the number of complete videos is 3,004×5×2=30,040. All videos have the resolution of 1280 × 720 and a frame rate of 30 FPS (frames per second). The videos are collected under a natural background. 

&emsp; The contents of the dataset cover three scenarios, i.e., diet, travel, and accommodation. The entity and template sentences are derived from the CrossWOZ corpus. The CCUL dataset contains 654 Chinese sign words. The entity videos and template videos are used to produce 300,400 combined videos, which are viewed as the training set. And the complete videos are viewed as the test set. The table 1 shows the details of the CCUL dataset.
| Name      | Associated task |Vocabulary |Country |
| ----------- | ----------- |----------- |----------- |
| CCLS     | CSLR/SLT/ISLR       |654       |China       |
| Language level      | Signer |Entity video |Template video |
| Word/Sentence   | 10        |29,700        |6,000        |
| Complete video      | Total number of samples |Training videos (combined) |Testing videos |
| 30,040   | 19,700        |300,400      |300,400       |

### <u>Download:</u>
&emsp;The CCLS dataset is released to universities and research institutes for research purpose only. To request the access right to the data resources, please follow the link below:

**Baidu Netdisk:** https://pan.baidu.com/s/1iKrnyiE_OsKtvjeF1FdHdg [password: g546]

**OneDrive:** https://tjueducn-my.sharepoint.com/:f:/g/personal/lqgao_tju_edu_cn/ElP33W20u2BAr_Kbx5Ngz94ByFsGtBVH1X8GySgTCgUfBA?e=irzOaQ
### <u>Contact:</u>

If you have any questions about the dataset, please feel free to contact us:

Wei Feng, Professor, Tianjin University, wfeng@ieee.org

Liqing Gao, Ph.D Candidate, Tianjin University, lqgao@tju.edu.cn