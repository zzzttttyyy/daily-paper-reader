<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-17 ~ 2026-10-26
- 运行时间：2026-10-26 12:58:33 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
10月17日至26日共筛读17篇论文（精读6篇、速读11篇），重点关注扩散模型采样加速和视频生成优化。最值得看的是满分论文《LEAP: Accelerating ODE-based Diffusion Sampling with Optimal Linear Leaps》提出的ODE扩散采样加速方案，以及9.0分的《GeoART》用测试时缩放做相机条件视频扩散的几何精修。普通读者可以先读这两篇精读，再按兴趣翻看速读里的视频扩散缓存和编辑方向。
- 详情：[/20261017-20261026/README](/20261017-20261026/README)

### 精读区论文标签
1. [LEAP: Accelerating ODE-based Diffusion Sampling with Optimal Linear Leaps](/20261017-20261026/2610.25918v1-leap-accelerating-ode-based-diffusion-sampling-with-optimal-linear-leaps)  
   标签：评分：10.0/10、query:tfree-diff
   evidence：通过最优线性跳跃实现免训练扩散采样加速
2. [GeoART: Geometry-Aware Refinement via Test-Time Scaling for Camera-Conditioned Video Diffusion](/20261017-20261026/2610.25273v1-geoart-geometry-aware-refinement-via-test-time-scaling-for-camera-conditioned-video-diffusion)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：免训练测试时缩放框架，无需微调即提升相机条件视频扩散
3. [PoSTCache: From Forecasting to Postdictive Smoothing for Revisable Diffusion Caching](/20261017-20261026/2610.25664v1-postcache-from-forecasting-to-postdictive-smoothing-for-revisable-diffusion-caching)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：免训练即插即用的扩散缓存加速
4. [Sparsity Should Be ALLOTted by Output: Training-Free Allocation of Block-Sparse Attention for Video Diffusion Transformers](/20261017-20261026/2610.29441v1-sparsity-should-be-allotted-by-output-training-free-allocation-of-block-sparse-attention-for-video-diffusion-transformers)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：视频扩散Transformer的免训练稀疏分配
5. [Latent Space Jam: Layout Guided Video Synthesis](/20261017-20261026/2610.30390v1-latent-space-jam-layout-guided-video-synthesis)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：免训练的视频生成控制
6. [ParaLin++: Accelerating Parallel Diffusion Integrator via Intrinsic Partially Linear Structure](/20261017-20261026/2610.30704v1-paralin-accelerating-parallel-diffusion-integrator-via-intrinsic-partially-linear-structure)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：系统评估扩散模型的免训练少步采样加速方法

### 速读区论文标签
1. [Frequency-Step Cache: Separating Synchronization and Repair for Efficient Autoregressive Video Diffusion](/20261017-20261026/2610.15922v1-frequency-step-cache-separating-synchronization-and-repair-for-efficient-autoregressive-video-diffusion)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：面向高效自回归视频扩散的免训练缓存
2. [Risk-Averse Inference-Time Diffusion Model Alignment with Finite-Sample Guarantees](/20261017-20261026/2610.17579v1-risk-averse-inference-time-diffusion-model-alignment-with-finite-sample-guarantees)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：无需昂贵微调的推理时扩散模型对齐
3. [QK-Edit: Revisiting Attention-based Injection in MM-DiT for Image and Video Editing](/20261017-20261026/2610.17829v1-qk-edit-revisiting-attention-based-injection-in-mm-dit-for-image-and-video-editing)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：面向图像视频编辑的免训练注意力操控
4. [QK-Edit: Revisiting Attention-based Injection in MM-DiT for Image and Video Editing](/20261017-20261026/2610.17829v2-qk-edit-revisiting-attention-based-injection-in-mm-dit-for-image-and-video-editing)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：面向图像与视频编辑的免训练框架
5. [BridgeTwist: Twisting Schrödinger Bridges for Training-Free Conditional Sampling](/20261017-20261026/2610.18658v1-bridgetwist-twisting-schrdinger-bridges-for-training-free-conditional-sampling)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：预训练薛定谔桥模型的免训练条件采样器
6. [ReState: Noise-Level-Aware State Correction for Training-Free Object Removal in Few-Step Diffusion Models](/20261017-20261026/2610.21287v1-restate-noise-level-aware-state-correction-for-training-free-object-removal-in-few-step-diffusion-models)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：通过状态校正在少步扩散模型中免训练去除物体
7. [Negation without Confusion: Decomposing Bias and Recomposing Style in Text Embeddings for Negation-aware Image Generation](/20261017-20261026/2610.25645v1-negation-without-confusion-decomposing-bias-and-recomposing-style-in-text-embeddings-for-negation-aware-image-generation)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：面向否定感知图像生成的免训练文本嵌入分解重组
8. [Internal Guidance as a Sampling Method for Tilted Diffusion Models](/20261017-20261026/2610.29086v1-internal-guidance-as-a-sampling-method-for-tilted-diffusion-models)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：面向倾斜扩散模型的免训练内部引导采样
9. [Holo4D: Holistic 4D Reconstruction as Geometric Control for Video Diffusion](/20261017-20261026/2610.25276v1-holo4d-holistic-4d-reconstruction-as-geometric-control-for-video-diffusion)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：用四维重建脚手架引导预训练视频扩散模型，无需微调
10. [ATLAS: Attention-Guided Test-Time Latent Selection for Compositional Visual Autoregressive Generation](/20261017-20261026/2610.25390v1-atlas-attention-guided-test-time-latent-selection-for-compositional-visual-autoregressive-generation)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：面向图像生成的免训练测试时潜变量选择，但基于自回归而非扩散模型
11. [TamedFlow: Trajectory-Aware Distillation\\for Teacher-Assisted Diffusion Sampling](/20261017-20261026/2610.26025v1-tamedflow-trajectory-aware-distillationfor-teacher-assisted-diffusion-sampling)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：面向图像与视频生成的扩散采样加速，但依赖蒸馏训练


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
