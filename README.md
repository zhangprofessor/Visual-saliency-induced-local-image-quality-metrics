# Visual-saliency-induced-local-image-quality-metrics
The full reference image quality assessment usually includes two stages: local image quality measurement and pooling. The classical
assessment algorithm based on visual saliency (VS) applies VS in the pooling stage and uses VS to weighted average the similarity
map. It emphasizes that the region with strong significance has a large contribution to the overall image quality, while the region with
weak significance has a small contribution to the overall image quality. Different from the classical method, VS is used in the
measurement stage of local image quality in this paper, and VS is used to adjust the calculation of local image quality adaptively,
emphasizing that the local quality degradation perceived by human visual system is jointly determined by objective degradation
degree and significance. The main contributions of this paper include: (1) propose a local image quality measurement framework
guided by visual saliency; (2) within this framework, we further improve the ESSIM (edge strength similarity) algorithm previously
published on IEEE Signal Processing Letters, and propose the VS-guided ESSIM algorithm (VS-ESSIM). The experimental results
on TID2013, TID2008 and CSIQ show that the proposed algorithm can improve the prediction accuracy of image quality and achieve
better consistency with the subjective evaluation results.
