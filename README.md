## EoCD: Encoder only Remote Sensing Change Detection
[![arXiv](https://img.shields.io/badge/arXiv-paper-blue.svg)](https://arxiv.org/abs/2602.05882)


> [!NOTE]
> Code will be released soon

### Overview
EoCD is a simple yet effective method for remote sensing change detection. It is based on early fusion of bi-temporal images and replaces the decoder with a parameter-free multiscale feature fusion module thereby significantly reducing the overall complexity of the model. EoCD demonstrate the optimal balance between the change detection performance and the prediction speed across a variety of encoder architectures. Additionally, EoCD demonstrate that the performance of the model is predominantly dependent on the encoder network.

<img width="1024" alt="EoCD Framework" src="images/eocd_architecture.png">


### See Also
- [ELGCNet](https://github.com/techmn/elgcnet) &nbsp; Efficient Local-Global Context Aggregation for Remote Sensing Change Detection (TGRS 2024)
- [ChangeBind](https://github.com/techmn/changebind) &nbsp; ChangeBind: A Hybrid Change Encoder for Remote Sensing Change Detection (IGARSS 2024)
- [ScratchFormer](https://github.com/mustansarfiaz/ScratchFormer) &nbsp; Remote Sensing Change Detection With Transformers Trained from Scratch (TGRS 2024)


### Citation
```
@misc{eocd2026,
      title={EoCD: Encoder only Remote Sensing Change Detection}, 
      author={Mubashir Noman and Mustansar Fiaz and Hiyam Debary and Abdul Hannan and Shah Nawaz and Fahad Shahbaz Khan and Salman Khan},
      year={2026},
      eprint={2602.05882},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2602.05882}, 
}```
