# Welcome to My GitHub Profile 👋  

## Multimodal Fusion Learning for Disease Classification  

Multimodal fusion learning has shown significant promise in classifying various diseases such as skin cancer and brain tumors. However, existing methods face three key limitations:  

1. **Lack of Generalizability**: Existing methods often fail to generalize across diagnosis tasks due to their focus on a specific disease.  
2. **Limited Use of Diverse Modalities**: They do not fully leverage multiple health records from diverse modalities to learn robust complementary information.  
3. **Single Attention Mechanism**: Relying on a single attention mechanism misses the benefits of combining multiple attention strategies within and across various modalities.  

### Our Proposed Approach: **DRIFA**  

To address these challenges, we propose:  
**A Dual Robust Information Fusion Attention Mechanism** (**DRIFA**)  

### Key Features of DRIFA:  

- **Multi-Branch Fusion Attention Module**: Enhances representations for each modality, such as dermoscopy, pap smear, MRI, and CT scans.  
- **Multimodal Information Fusion Attention Module**: Learns refined multimodal shared representations, improving the network's generalization across multiple tasks.  

DRIFA can be integrated with any deep neural network, forming a multimodal fusion learning framework known as **DRIFA-Net**.  

### Performance Highlights:  

- **Uncertainty Estimation**: Using an ensemble Monte Carlo dropout strategy, DRIFA-Net provides reliable predictions with uncertainty estimates.  
- **State-of-the-Art Results**: Extensive experiments on five publicly available datasets demonstrate consistent performance improvements over existing methods.  

### Technologies and Applications:  
- **Applications**: Disease classification (e.g., skin cancer, brain tumors).  
- **Modalities**: Dermoscopy, pap smear, MRI, and CT scans.  


![image](https://github.com/user-attachments/assets/183e6cfa-c351-4fac-a2ee-5058c5a3a883)
Figure 1. Detailed architecture of DRIFA-Net. Key components include: (A) the target-specific multimodal fusion learning (TMFL)
phase, followed by (B) an uncertainty quantification (UQ) phase. TMFL phase comprises a robust residual attention (RRA) block, shown
in (C), and utilizes multi-branch fusion attention (MFA), an additional MFA module for further refinement of local representations, a
multimodal information fusion attention (MIFA) module for improved multimodal representation learning, and multitask learning (MTL)
for handling multiple classification tasks. During (UQ) phase, the reliability of DRIFA-Net predictions are assessed.


![image](https://github.com/user-attachments/assets/5bb28a78-1f8a-4036-9ed0-0a43e1c854f9)

Figure 2. (a) Multi-branch fusion attention (MFA) module.Key components include hierarchical information fusion attention (HIFA) for diverse 
local information enhancement and channelwise local information attention (CLIA) for improved channelspecific representation learning.


![image](https://github.com/user-attachments/assets/89a9e27f-dcb2-4c4a-8533-d0e5a7852cda)

Figure 3. (a) Multimodal information fusion attention (MIFA) module. This module includes multimodal global information fusion attention (MGIFA) (shown in b) and multimodal local information fusion attention (MLIFA) (shown in c).


![image](https://github.com/user-attachments/assets/6fb43d09-7df3-47af-919d-9c3cfc03ca24)

Figure 4. Visual representation of the important regions highlighted by our proposed DRIFA-Net and four SOTA methods using the
GRAD-CAM technique on two benchmark datasets D1 and D3. (a) and (g) display the original images, while (b) and (h) present results for
Gloria, (c) and (i) for MTF with MA, (d) and (j) for CAF, (e) and (k) for MTTU-Net, and (f) and (l) for our proposed DRIFA-Net.


![image](https://github.com/user-attachments/assets/45530e92-f739-420c-bdea-85996dbf9712)

Figure 5. T-SNE visualization of different models applied to the dermoscopy images of the D1 dataset, where (a) represents the T-SNE visualization of Gloria, (b) of MTTU-Net, and (c) of our proposed DRIFA-Net.


### Citation:  

If you find this work useful, please cite:  
```bibtex
@inproceedings{dhar2025multimodal,
  title={Multimodal Fusion Learning with Dual Attention for Medical Imaging},
  author={Dhar, Joy and Zaidi, N. and Haghighat, M. and Goyal, P. and Roy, S. and Alavi, A. and Kumar, V.},
  booktitle={IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)},
  year={2025},
  url={https://arxiv.org/abs/2412.01248}
}







