# LLM-for-Spatial-Time-Series
A list of Large Language Model (LLM) for Spatial Time Series, including papers, datasets and codes, which aims at summerizing recent studies to improve our corresponding knowledge.
We will continue to update the list of the resources and provide a comprehensive taxonomy in the future.

## Serial
### LLM as Encoder
- [Pre-training Enhanced Spatial-temporal Graph Neural Network for Multivariate Time Series Forecasting][[ACM SIGKDD 2022]](https://dl.acm.org/doi/10.1145/3534678.3539396)[[Code]](https://github.com/GestaltCogTeam/STEP)
- [DST-GTN: Dynamic Spatio-Temporal Graph Transformer Network for Traffic Forecasting][[arXiv]](https://arxiv.org/abs/2404.11996)
- [Spatio-Temporal Adaptive Embedding Makes Vanilla Transformer SOTA for Traffic Forecasting][[CIKM 2023]](https://dl.acm.org/doi/10.1145/3583780.3615160)[[Code]](https://github.com/XDZhelheim/STAEformer)
- [ImputeFormer: Low rankness-induced transformers for generalizable spatiotemporal imputation][[ACM SIGKDD 2024]](https://dl.acm.org/doi/10.1145/3637528.3671751)[[Code]](https://github.com/tongnie/ImputeFormer)
- [CrossST: An Efficient Pre-Training Framework for Cross-District Pattern Generalization in Urban Spatio-Temporal Forecasting][[ICDE 2025]](https://www.computer.org/csdl/proceedings-article/icde/2025/360300c935/26FZBkxez6w)[[Code]](https://github.com/Aoyu-Liu/CrossST)
- [STTF: A Spatiotemporal Transformer Framework for Multi-task Mobile Network Prediction][[IEEE TMC]](https://ieeexplore.ieee.org/document/10840287)
- [Navigating Spatio-Temporal Heterogeneity: A Graph Transformer Approach for Traffic Forecasting][[arXiv]](https://arxiv.org/abs/2408.10822)[[Code]](https://github.com/jasonz5/STGormer)
- [FSTLLM: Spatio-Temporal LLM for Few Shot Time Series Forecasting][[ICML 2025]](https://openreview.net/forum?id=oyoiHf51es)[[Code]](https://github.com/JIANGYUE61610306/FSTLLM)
### LLM as Decoder
- [GATGPT: A Pre-trained Large Language Model with Graph Attention Network for Spatiotemporal Imputation][[arXiv]](https://arxiv.org/abs/2311.14332)
- [MultiSPANS: A Multi-range Spatial-Temporal Transformer Network for Traffic Forecast via Structural Entropy Optimization][[WSDM 2024]](https://dl.acm.org/doi/10.1145/3616855.3635820)[[Code]](https://github.com/SELGroup/MultiSPANS)
- [Spatiotemporal Pretrained Large Language Model for Forecasting With Missing Values][[IEEE IOTJ]](https://ieeexplore.ieee.org/document/10833705)
- [How Can Large Language Models Understand Spatial-Temporal Data?][[arXiv]](https://arxiv.org/abs/2401.14192)
- [ST-LLM+: Graph Enhanced Spatio-Temporal Large Language Models for Traffic Prediction][[IEEE TKDE]](https://ieeexplore.ieee.org/document/11005661)[[Code]](https://github.com/kethmih/ST-LLM-Plus)
- [STGformer: Efficient Spatiotemporal Graph Transformer for Traffic Forecasting][[arXiv]](https://arxiv.org/abs/2410.00385)[[Code]](https://github.com/Dreamzz5/STGformer)
### LLM as Data Augmentation
- [CausalMob: Causal Human Mobility Prediction with LLMs-derived Human Intentions toward Public Events][[ACM SIGKDD 2025]](https://dl.acm.org/doi/10.1145/3690624.3709231)[[Code]](https://github.com/YangXiaojie1998/CausalMob)

## Interleaving
### LLM as Encoder
- [Context-Alignment: Activating and Enhancing LLMs Capabilities in Time Series][[ICLR 2025]](https://openreview.net/forum?id=syC2764fPc)[[Code]](https://github.com/tokaka22/ICLR25-FSCA)
- [PIGAT: Physics-Informed Graph Attention Transformer for Air Traffic State Prediction][[IEEE TITS]](https://ieeexplore.ieee.org/document/10505827)[[Code]](https://github.com/ymlasu/para-atm-collection/tree/master/air-traffic-prediction/PIGAT)
- [TLAST: A Time-Lag Aware Spatial-Temporal Transformer for Traffic Flow Forecasting][[IEEE TITS]](https://ieeexplore.ieee.org/document/11077815)

## Parallel
### LLM as Encoder
- [Scaling Up Multivariate Time Series Pre-Training with Decoupled Spatial-Temporal Representations][[ICDE 2024]](https://ieeexplore.ieee.org/document/10598155)
- [LLGformer: Learnable Long-range Graph Transformer for Traffic Flow Prediction][[WWW 2025]](https://dl.acm.org/doi/abs/10.1145/3696410.3714596)
- [PDFormer: propagation delay-aware dynamic long-range transformer for traffic flow prediction][[AAAI 2023]](https://dl.acm.org/doi/10.1609/aaai.v37i4.25556)[[Code]](https://github.com/BUAABIGSCity/PDFormer)
- [Spatial-Temporal-Decoupled Masked Pre-training for Spatiotemporal Forecasting][[IJCAI 2024]](https://www.ijcai.org/proceedings/2024/442)[[Code]](https://github.com/Jimmy-7664/STD-MAE)
### LLM as Decoder
- [TPLLM: A traffic prediction framework based on pretrained Large Language Models][[Applied Soft Computing]](https://www.sciencedirect.com/science/article/pii/S1568494625011536)
- [STD-PLM: Understanding Both Spatial and Temporal Properties of Spatial-Temporal Data with PLM][[AAAI 2025]](https://ojs.aaai.org/index.php/AAAI/article/view/33286)[[Code]](https://github.com/Hyheng/STD-PLM)
- [BERT4ST:: Fine-tuning pre-trained large language model for wind power forecasting][[Energy Conversion and Management]](https://www.sciencedirect.com/science/article/abs/pii/S0196890424002723)
- [STELLM: Spatio-temporal enhanced pre-trained large language model for wind speed forecasting][[Applied Energy]](https://www.sciencedirect.com/science/article/abs/pii/S030626192401417X)
- [NextLocLLM: Location Semantics Modeling and Coordinate-Based Next Location Prediction with LLMs][[arXiv]](https://arxiv.org/abs/2410.09129)[[Code]](https://github.com/liuwj2000/NexelocLLM)
- [Spatial-Temporal Large Language Model for Traffic Prediction][[MDM 2024]](https://www.computer.org/csdl/proceedings-article/mdm/2024/745500a031/1YEw6c6c6Vq)[[Code]](https://github.com/ChenxiLiu-HNU/ST-LLM)
- [ST-LINK: Spatially-Aware Large Language Models for Spatio-Temporal Forecasting][[CIKM 2025]](https://arxiv.org/abs/2509.13753)[[Code]](https://github.com/HyoTaek98/ST_LINK)
- [STCA-LLM: Spatial-Temporal Cross-Attention Large Language Model for Wind Speed Forecasting][[IEEE IOTJ]](https://ieeexplore.ieee.org/document/11129036)[[Code]](https://github.com/Justinzzcj/STCA-LLM)
### LLM as Aligner
-[K-Link: Knowledge-Link Graph from LLMs for Enhanced Representation Learning in Multivariate Time-Series Data][[arXiv]](https://arxiv.org/abs/2403.03645)


