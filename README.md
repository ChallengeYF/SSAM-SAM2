# SSAM‑SAM2

This is the code for **Hyperspectral Video Object Segmentation Based on Spectral–Spatial Interaction Enhancement and Adaptive Correlation Memory Selection**.

<p align="center">
<img src="SSAM-sam2.png" width="880"/>
<br>
<em>[Overall architecture of SSAM-SAM2. The SSIE and ACMS modules are incorporated into the SAM 2 framework. By integrating spectral priors from hyperspectral images with spatial priors from RGB images and dynamically selecting high-quality historical memory frames according to the target state, the network achieves accurate segmentation of target.]</em>
</p>

<br>

<p align="center">
<img src="SSIE-NEW.png" width="720"/>
<br>
<em>[Architecture of the SSIE module: (a) Overall architecture; (b) BandsGate module; and (c) Band Embedding module. BandsGate adaptively selects the core spectral bands, while Band Embedding maps the residual-band features, enabling the module to extract discriminative joint spectral–spatial representations from hyperspec-tral images.]</em>
</p>

<br>

<p align="center">
<img src="ACMS.png" width="720"/>
<br>
<em>[Architecture of the ACMS module.]</em>
</p>

> 📌 Note: The source code is currently under preparation for journal submission and will be publicly released upon acceptance.
