<h1>MS-LKSeg: Enhancing Multi-semantic Synergistic Learning with Large Kernel Convolution for Medical Image Segmentation</h1>

<h2>Here, we provide a brief model diagram and visualization results of binary-class segmentation. Detailed supplements will be made after the paper is accepted.</h2>
<h2>Fig.1：The overall architecture of MS-LKSeg is shown in Figure (a). The rest are the key components of the network:(b) spatial attention-based Multi-semantic Information Extraction (MIE) module, (c) channel attention-based Multi-semantic Information Difference Mitigation (MIDM) module, and (d) Large Kernel Depthwise Separable convolution (LD) module.<h2>
<div align="center">
<img src="assets/Fig1.png" alt="Fig.1：The overall architecture of MS-LKSeg is shown in Figure (a). The rest are the key components of the network:(b) spatial attention-based Multi-semantic Information Extraction (MIE) module, (c) channel attention-based Multi-semantic Information Difference Mitigation (MIDM) module, and (d) Large Kernel Depthwise Separable convolution (LD) module." width="800"/>
</div>

<h2>Fig.2：Dual-dimensional Collaboration Module (DCM). Where MKS-DWConv denotes the Multi-Kernel Shared Depthwise Separable 1D Convolutions with Kernels of 3, 5, 7, and 9.</h2>
<div align="center">
<img src="assets/Fig2.png" alt="Fig.2：Dual-dimensional Collaboration Module (DCM). Where MKS-DWConv denotes the Multi-Kernel Shared Depthwise Separable 1D Convolutions with Kernels of 3, 5, 7, and 9." width="800"/>
</div>

<h2>An example of reparameterising a small kernel (3×3) into a large kernel (7×7), which in this paper has dimensions of 3×3 and 21×21 for the small and large kernels, respectively.</h2>
<div align="center">
<img src="assets/Fig3.png" alt="Fig.3：An example of reparameterising a small kernel (3×3) into a large kernel (7×7), which in this paper has dimensions of 3×3 and 21×21 for the small and large kernels, respectively." width="800"/>
</div>

<h2>Fig4：Visual comparison of UNet, EMCAD, LKSNeXt, and our proposed MS-LKSeg on three datasets.</h2>
<div align="center">
<img src="assets/Fig4.png" alt="Fig4：Visual comparison of UNet, EMCAD, LKSNeXt, and our proposed MS-LKSeg on three datasets." width="800"/>
</div>
