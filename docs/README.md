<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-07
- 运行时间：2026-09-07 22:58:13 UTC
- 运行状态：成功
- 本次总论文数：4
- 精读区：3
- 速读区：1

### 今日简报（AI）
今日聚焦视频生成与视觉合成，精读两篇9分论文，另速读一篇新视图合成研究。  
最值得关注的是视频生成中的“冻结世界模型”引导：一篇做离流形细化提升质量，另一篇用预测式潜引导实现无需训练的目标/效果移除。  
建议熟悉视频编辑的读者优先看 PredErase 的引导机制，或结合 Off-Manifold 思路探索更可控的生成后处理流程。
- 详情：[/202609/07/README](/202609/07/README)

### 精读区论文标签
1. [Off-Manifold Refinement: Guiding Video Generators with a Frozen World Model](/202609/07/2608.29904v1-off-manifold-refinement-guiding-video-generators-with-a-frozen-world-model)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：利用冻结世界模型的推理阶段免训练视频生成器精化方法
2. [PredErase: Training-Free Object-and-Effect Removal with Predictive Latent Guidance](/202609/07/2609.00956v1-prederase-training-free-object-and-effect-removal-with-predictive-latent-guidance)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：冻结扩散模型上的免训练预测性潜在引导，直接用于图像对象与效果移除，强匹配免训练图像生成优化
3. [ReaDiT Guidance: Control for Image and Video Generation using Diffusion Transformer Features](/202609/07/2609.04649v1-readit-guidance-control-for-image-and-video-generation-using-diffusion-transformer-features)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：利用DiT内部特征在测试时同时控制图像与视频生成，无需训练或额外适配器，是典型的免训练扩散优化方法

### 速读区论文标签
1. [Reflection-aware Generative Novel View Synthesis](/202609/07/2609.05382v1-reflection-aware-generative-novel-view-synthesis)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：无需训练的反射感知多视角扩散生成，用于镜面场景新视角合成


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
