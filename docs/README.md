<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-29
- 运行时间：2026-09-29 23:18:04 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
- 今日共生成 17 篇推荐（精读 6 篇，速读 11 篇）
- 精读：《UnStep: Training-Free Acceleration of Causal Video Diffusion with Fewer Steps Than Distillation》（9.0/10）, 《DraftAttention2: Fast Video Diffusion with Low-Resolution-Guided Mixed-Precision Attention》（9.0/10）
- 速读：《Unlocking Few-Step Diffusion for Faithful Previews》（8.0/10）, 《LoCoVSR: Local Context Diffusion Posterior Sampling for Video Super-Resolution》（7.0/10）, 《TSGate: Timestep-Aware Gated Attention for Diffusion Transformers》（7.0/10）
- 这些结果覆盖了当下较热的方向，建议先看精读区论文的关键问题与方法。
- 详情：[/202609/29/README](/202609/29/README)

### 精读区论文标签
1. [UnStep: Training-Free Acceleration of Causal Video Diffusion with Fewer Steps Than Distillation](/202609/29/2609.32518v1-unstep-training-free-acceleration-of-causal-video-diffusion-with-fewer-steps-than-distillation)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：推理阶段免训练加速因果视频扩散
2. [DraftAttention2: Fast Video Diffusion with Low-Resolution-Guided Mixed-Precision Attention](/202609/29/2609.32628v1-draftattention2-fast-video-diffusion-with-low-resolution-guided-mixed-precision-attention)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：免训练框架，用混合精度注意力加速视频扩散
3. [GeoShrink: Accelerating Diffusion Transformers with Two Lines of Code](/202609/29/2609.33723v1-geoshrink-accelerating-diffusion-transformers-with-two-lines-of-code)  
   标签：评分：9.0/10、query:tfree-diff
   evidence：扩散变换器采样的免训练加速
4. [In-Flight KV Cache with Clean Anchors for Faster Autoregressive Video Diffusion](/202609/29/2609.32540v1-in-flight-kv-cache-with-clean-anchors-for-faster-autoregressive-video-diffusion)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：免训练复用KV缓存加速自回归视频扩散生成
5. [PulseQuant: Propagation-Guided Subspace Correction for 4-Bit Video Diffusion Transformers](/202609/29/2609.33384v1-pulsequant-propagation-guided-subspace-correction-for-4-bit-video-diffusion-transformers)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：面向视频扩散Transformer的训练后量化，无需重训练
6. [JIVE: Jacobian-Informed Volume Expansion for Diverse Generative Sampling](/202609/29/2609.33906v1-jive-jacobian-informed-volume-expansion-for-diverse-generative-sampling)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：免训练框架通过速度扰动提升生成多样性

### 速读区论文标签
1. [Unlocking Few-Step Diffusion for Faithful Previews](/202609/29/2609.34406v1-unlocking-few-step-diffusion-for-faithful-previews)  
   标签：评分：8.0/10、query:tfree-diff
   evidence：仅优化冻结少步采样器的初始噪声且无需重训练
2. [LoCoVSR: Local Context Diffusion Posterior Sampling for Video Super-Resolution](/202609/29/2609.32742v1-locovsr-local-context-diffusion-posterior-sampling-for-video-super-resolution)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：免训练的扩散后验采样视频超分
3. [TSGate: Timestep-Aware Gated Attention for Diffusion Transformers](/202609/29/2609.34539v1-tsgate-timestep-aware-gated-attention-for-diffusion-transformers)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：推理时门控注意力改进DiT图像与视频生成质量
4. [Domain-adaptive Zero-Shot Image Enhancement via Locality-Constrained Diffusion Guidance](/202609/29/2609.35289v1-domain-adaptive-zero-shot-image-enhancement-via-locality-constrained-diffusion-guidance)  
   标签：评分：7.0/10、query:tfree-diff
   evidence：免训练局部约束扩散采样引导用于图像增强
5. [Accurate Sampling from Diffusion Models](/202609/29/2609.29902v1-accurate-sampling-from-diffusion-models)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：无需重训，用序贯蒙特卡洛改进扩散模型采样精度
6. [An End-to-End Latent-Rollout Approach for Pushing Few-Step ImageNet-$256$ Generation to FID $1.11$ without Fréchet Losses](/202609/29/2609.32376v1-an-end-to-end-latent-rollout-approach-for-pushing-few-step-imagenet-256-generation-to-fid-111-without-frchet-losses)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：端到端展开优化的少步扩散图像生成
7. [RefAdapt-DiT: Adaptive Joint Attention for Reference-Conditioned Diffusion Transformers](/202609/29/2609.32415v1-refadapt-dit-adaptive-joint-attention-for-reference-conditioned-diffusion-transformers)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：自适应联合注意力减少扩散Transformer的冗余计算
8. [Simple Diffusion Language Models Are More Effective Few-Step Generators Than Reported](/202609/29/2609.33947v1-simple-diffusion-language-models-are-more-effective-few-step-generators-than-reported)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：无需重训练锐化采样器的扩散少步生成
9. [From Static to Dynamic: On-Policy Distillation from Image to Video Diffusion Models](/202609/29/2609.34371v1-from-static-to-dynamic-on-policy-distillation-from-image-to-video-diffusion-models)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：借助图像专家蒸馏改进视频扩散模型
10. [From Scores to Samples: Elastic Forcing for Autoregressive Video Generation](/202609/29/2609.35491v1-from-scores-to-samples-elastic-forcing-for-autoregressive-video-generation)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：无需分数模型改进少步自回归视频生成
11. [PDMD: Projected Distribution Matching Distillation for Video Diffusion Models](/202609/29/2609.35768v1-pdmd-projected-distribution-matching-distillation-for-video-diffusion-models)  
   标签：评分：6.0/10、query:tfree-diff
   evidence：面向视频扩散模型的分布匹配蒸馏，降低采样步数


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
