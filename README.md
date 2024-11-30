# DRIFA-Net
Multimodal fusion learning has shown significant
promise in classifying various diseases such as skin cancer, brain tumors, etc. However, existing methods for multimodal fusion learning have at least three problems. First,
they often lack generalization to other diagnosis tasks due to their focus on a particular disease. Second, they do not
fully leverage multiple health records from diverse modalities to learn robust complementary information. And, finally they rely on a single attention mechanism, missing the
benefits of multiple attention strategies within and across various modalities. To address these issues, this paper
proposes a dual robust information fusion attention mechanism (DRIFA) that leverages two attention modules – i.e.,
multi-branch fusion attention module and the multimodal information fusion attention module. DRIFA can be integrated with any deep neural network leading to framework
of multimodal fusion learning denoted as DRIFA-Net.We show in the paper that multi-branch fusion attention
of DRIFA learns enhanced representations for each modality, such as dermoscopy, pap smear, MRI, and CT-scan,
whereas multimodal information fusion attention module learns enhanced multimodal shared representations – improving the network’s generalization across multiple tasks
and enhancing overall performance. Furthermore, to estimate the uncertainty of DRIFA-Net predictions, we have
employed an ensemble Monte Carlo dropout strategy. Extensive experiments on five publicly available datasets with
diverse modalities demonstrate that our approach consistently outperforms existing state-of-the-art methods. 
