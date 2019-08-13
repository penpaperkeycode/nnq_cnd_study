## Neural Network Quantization & Model Compression Awesome Papers!
**0. Binarized Neural Network & Its Training**
 - *Courbariaux, Matthieu, et al. “Binarized neural networks: Training deep neural networks with weights and activations constrained to+ 1 or-1.” arXiv preprint arXiv:1602.02830 (2016).*
 - *Darabi, Sajad, et al. “BNN+: Improved binary network training.” arXiv preprint arXiv:1812.11800 (2018).*
 - Galloway, Angus, Graham W. Taylor, and Medhat Moussa. “Attacking binarized neural networks.” arXiv preprint arXiv:1711.00449 (2017).
 - *Zhou, Shuchang, et al. “Dorefa-net: Training low bitwidth convolutional neural networks with low bitwidth gradients.” arXiv preprint arXiv:1606.06160 (2016).*  
 - Wang, Ziwei, et al. “Learning Channel-Wise Interactions for Binary Convolutional Neural Networks.” Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2019.
 - Hou, Lu, Quanming Yao, and James T. Kwok. "Loss-aware binarization of deep networks." Proceedings of the Fifth International Conference on Learning Representations (ICLR), Toulon, France, Apr 2017.

**1. Hardware for BNN (Edge device)**
 - *Yonekawa, Haruyoshi, and Hiroki Nakahara. “On-chip memory based binarized convolutional deep neural network applying batch normalization free technique on an fpga.” 2017 IEEE International Parallel and Distributed Processing Symposium Workshops (IPDPSW). IEEE, 2017.* 
 - *Umuroglu, Yaman, et al. “Finn: A framework for fast, scalable binarized neural network inference.” Proceedings of the 2017 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays. ACM, 2017.*

**2. Multi-bit Quantization** 
 - Jung, Sangil, et al. “Learning to quantize deep networks by optimizing quantization intervals with task loss.” Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2019.
 -  Chen Xu, Jianqiang Yao, et al. “Alternating Multi-bit Quantization for Recurrent Neural Networks” International Conference on Learning Representations (ICLR), 2018
 - Zhang, Dongqing, et al. “Lq-nets: Learned quantization for highly accurate and compact deep neural networks.” Proceedings of the European Conference on Computer Vision (ECCV). 2018.
 - Lee, Dongsoo, Parichay Kapoor, and Byeongwook Kim. “Deeptwist: Learning model compression via occasional weight distortion.” arXiv preprint arXiv:1810.12823 (2018).
 - Hou, Lu, and James T. Kwok. "Loss-aware weight quantization of deep networks." Proceedings of the Sixth International Conference on Learning Representations (ICLR), Vancouver, BC, Canada, Apr 2018.
 - Lu Hou, Ruiliang Zhang, James T. Kwok. "Analysis of Quantized Models" Proceedings of the Seventh International Conference on Learning Representations (ICLR), New Orleans, USA, May 2019.

**3. Neural Network Model Compression &Hardware Aware Neural Network Architectures**
 - Naver techtalk : https://www.slideshare.net/mobile/NaverEngineering/designing-more-efficient-convolution-neural-network-122869307
 - Song Han, Huizi Mao, William J. Dally. "Deep Compression :Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding"
 - Junho Yim1 Donggyu Joo1 Jihoon Bae2 Junmo Kim1 "A Gift from Knowledge Distillation: Fast Optimization, Network Minimization and Transfer Learning"
 
 Residual Connection
 - "Residual Networks Behave LIke Ensembles of Relatively Shallow Networks"
 Dilated Convolution
 Point-wise Convolution
 Grouped Convolution
 Depth-wise (Seperable) Convolution
 
 Quantization
 
 
 Prunning
 
  
 - Jacob, Benoit, et al. "Quantization and training of neural networks for efficient integer-arithmetic-only inference." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018.
 - Zhu, Chenzhuo, et al. “Trained ternary quantization.” arXiv preprint arXiv:1612.01064 (2016).
 - Iandola, Forrest N., et al. “SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and< 0.5 MB model size.” arXiv preprint arXiv:1602.07360 (2016).
 - Gholami, Amir, et al. “Squeezenext: Hardware-aware neural network design.” Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops. 2018.
 - Tan, Mingxing, and Quoc V. Le. “EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks.” arXiv preprint arXiv:1905.11946 (2019). + EfficientNet-EdgeTPU: Creating Accelerator-Optimized Neural Networks with AutoML (https://ai.googleblog.com/2019/08/efficientnet-edgetpu-creating.html)
 - Polino, Antonio, Razvan Pascanu, and Dan Alistarh. “Model compression via distillation and quantization.” arXiv preprint arXiv:1802.05668 (2018).
 - Howard, Andrew G., et al. “Mobilenets: Efficient convolutional neural networks for mobile vision applications.” arXiv preprint arXiv:1704.04861 (2017).
 - Zhuang, Zhuangwei, et al. “Discrimination-aware channel pruning for deep neural networks.” Advances in Neural Information Processing Systems. 2018.
 - *He, Yihui, et al. “Amc: Automl for model compression and acceleration on mobile devices.” Proceedings of the European Conference on Computer Vision (ECCV). 2018.*

**4. Hardware for Quantized Neural Network**
 - Lee, Jinmook, et al. “Unpu: An energy-efficient deep neural network accelerator with fully variable weight bit precision.” IEEE Journal of Solid-State Circuits 54.1 (2018): 173-185.
 - Han, Song, Huizi Mao, and William J. Dally. "Deep compression: Compressing deep neural networks with pruning, trained quantization and huffman coding." arXiv preprint arXiv:1510.00149 (2015).
 - Yu, Jiecao, et al. "Scalpel: Customizing dnn pruning to the underlying hardware parallelism." ACM SIGARCH Computer Architecture News 45.2 (2017): 548-560.

 **5. Accelerating (NPU (혹은 Neural Network Framework) 컴파일러(+ 컴파일러 레벨의 딥러닝 관련 최적화))**
- DLVM- A modern compiler framework for neural network DSLs
- DLVM- A MODERN COMPILER INFRASTRUCTURE FOR DEEP LEARNING SYSTEMS
-  A modern compiler infrastructure for deep learning systems with adjoint code generation in a domain-specific IR
- Compiling machine learning programs via high-level tracing
- A Neural Network Accelerator Exploiting Both Inter-and Intra-Neuron Parallelism
- TVM- An Automated End-to-End Optimizing Compiler for Deep Learning
- Halide- A Language and Compiler for Optimizing Parallelism, Locality, and Recomputation in Image Processing Pipelines
- Glow: Graph Lowering Compiler Techniques for Neural Networks
- TensorFlow XLA compiler and the NNVM compiler (논문 아님) 
- Cambricon: An Instruction Set Architecture for Neural Networks
