---
caption:
  title: "AnyTalk: Speech Animation for Arbitrary Characters Leveraging a Video Generation Model"
  subtitle: |
    IEEE Transactions on Visualization and Computer Graphics (TVCG) 2026
  thumbnail: assets/img/publications/2026_TVCG_th.png


title: |
  AnyTalk: Speech Animation for Arbitrary Characters Leveraging a Video Generation Model
authors: |
  Kwan Yun\*, Serin Yoon\*, Sunjin Jung, Jung Eun Yoo, Inyup Lee, Junyong Noh <br>
  <i>\* Equal contribution</i>
journal: "IEEE Transactions on Visualization and Computer Graphics (TVCG), 2026 (Early Access)"
paper_url: "https://www.computer.org/csdl/journal/tg/5555/01/11659104/2j4PxBEKbM4"

image: assets/img/publications/2026_TVCG.png

abstract: |
  We present AnyTalk, a novel method for generating 3D speech animations for arbitrary characters without requiring any animation data. While existing audio-driven 3D speech animation methods rely on character-specific training data or laborious rigging/re-meshing, AnyTalk circumvents these limitations by leveraging recent video diffusion models trained on extensive video datasets. We first adapt a pre-trained video diffusion model to a target character through our Character-specific Fine-tuning (CsF) technique. By fine-tuning on rendered images of the 3D character paired with zeroed-out audio embeddings (representing "no motion"), we eliminate the need for animation data while preserving the motion prior of large-scale video diffusion model. We then uplift the resulting talking-head video into a 3D speech animation by estimating blendshape parameters through a proposed optimization process. AnyTalk enables lip-synced animations across diverse face meshes and blendshape configurations, significantly reducing manual effort and data requirements. We further enhance usability by distilling AnyTalk into a streamlined network, AnyTalk_RT, thereby enabling real-time performance. By leveraging talking-head video generation, our method broadens access to audio-driven speech animation technology for arbitrary characters. The code will be made publicly available.
---
