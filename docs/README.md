<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-09
- 运行时间：2026-09-09 22:07:31 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：6
- 速读区：7

### 今日简报（AI）
今日精读6篇、速读7篇，聚焦扩散模型的对齐与可控编辑领域。最值得关注的是两篇9.0分工作：测试时弱到强对齐以转移隐式奖励，以及基于加权速度引导的对象感知背景控制编辑。建议普通读者优先精读这两篇；对效率或视频感兴趣的，可速读RoLA线性注意力与SignRefine手语生成。
- 详情：[/202609/09/README](/202609/09/README)

### 精读区论文标签
1. [Test-Time Weak-to-Strong Alignment: Transferring Implicit Rewards from Weak to Strong Flow Models](/202609/09/2609.05968v1-test-time-weak-to-strong-alignment-transferring-implicit-rewards-from-weak-to-strong-flow-models)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：测试时对冻结的文生图流模型进行采样期引导，无需奖励梯度或额外训练
2. [Object-Aware Background-Controlled Editing via Weighted Velocity Guidance](/202609/09/2609.06288v1-object-aware-background-controlled-editing-via-weighted-velocity-guidance)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：面向扩散/流匹配图像编辑的免训练物体感知速度控制方法
3. [SwiftExplorer: Training-free Diffusion Model Alignment with Swift Diversity Exploration](/202609/09/2609.06651v1-swiftexplorer-training-free-diffusion-model-alignment-with-swift-diversity-exploration)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：提出无需训练的即插即用模块，在扩散模型采样中引入目标引导并保持多样性，直接命中免训练扩散优化
4. [Temporal State Transport in Video Generation: Diagnosing and Correcting Spectral Imbalance](/202609/09/2609.08505v1-temporal-state-transport-in-video-generation-diagnosing-and-correcting-spectral-imbalance)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：为视频生成中的时序状态失衡提供无需训练的谱张力诊断与纠正方法，直接回答免训练提升视频生成的问题
5. [ToPO: Token-Conditioned Preference Routing for Attention-Based Latent Diffusion Models](/202609/09/2609.03688v1-topo-token-conditioned-preference-routing-for-attention-based-latent-diffusion-models)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：用令牌级偏好路径优化潜在扩散模型图像生成，提高人类偏好对齐
6. [Multi-History-Step SDE Inversion for Image Editing with Superior Regional Awareness](/202609/09/2609.06602v1-multi-history-step-sde-inversion-for-image-editing-with-superior-regional-awareness)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：基于SDE反演的免训练图像编辑框架，引入多历史步采样预测-校正机制

### 速读区论文标签
1. [RoLA: Rotary-Positioned Low-Rank Linear Attention for Efficient Diffusion Transformers](/202609/09/2609.06712v1-rola-rotary-positioned-low-rank-linear-attention-for-efficient-diffusion-transformers)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：面向视频扩散Transformer的高效低秩注意力，改进视频生成推理效率
2. [SignRefine: Adapting Foundational Video Models for Sign Language Generation](/202609/09/2609.08496v1-signrefine-adapting-foundational-video-models-for-sign-language-generation)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：视频扩散模型用于手语视频生成
3. [Step Back to Move Forward: Reflection-Aware Preference Optimization for Visual Generation](/202609/09/2609.04282v1-step-back-to-move-forward-reflection-aware-preference-optimization-for-visual-generation)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：面向扩散图像生成的强化学习偏好优化
4. [ParetoTransport: Generative Optimization by Mass Transport Toward The Pareto Front](/202609/09/2609.07706v1-paretotransport-generative-optimization-by-mass-transport-toward-the-pareto-front)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：面向预训练流匹配模型的免训练群体级引导，推动样本走向帕累托前沿
5. [Geodesic-informed Generative Diffusion Model For Topology-preserved Image Video Generation](/202609/09/2609.08153v1-geodesic-informed-generative-diffusion-model-for-topology-preserved-image-video-generation)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：面向图像与视频生成的扩散模型，聚焦生成过程中的拓扑结构保持
6. [Let It Go or Learn to Self-Correct: Continuous Diffusion for Constrained Discrete Tasks](/202609/09/2609.09009v1-let-it-go-or-learn-to-self-correct-continuous-diffusion-for-constrained-discrete-tasks)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：面向扩散模型的免训练采样优化改动
7. [Revisiting Spectral Representations in Generative Diffusion Models](/202609/09/2609.08253v1-revisiting-spectral-representations-in-generative-diffusion-models)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：从谱表示与扰动核视角研究生成扩散模型中的隐状态对齐机制，涉及图像和视频生成


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
