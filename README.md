# FED-NeRF: Achieve High 3D Consistency and Temporal Coherence for Face Video Editing on Dynamic NeRF
## Abstract
The success of the GAN-NeRF structure has enabled face editing on NeRF to maintain 3D view consistency. However, achieving simultaneously multi-view consistency and temporal coherence while editing video sequences remains a formidable challenge. This paper proposes a novel face video editing architecture built upon the dynamic face GAN-NeRF structure, which effectively utilizes video sequences
to restore the latent code and 3D face geometry. By editing the latent code, multi-view consistent editing on the face can be ensured, as validated by multiview stereo reconstruction on the resulting edited images in our dynamic NeRF.
As the estimation of face geometries occurs on a frame-by-frame basis, this may introduce a jittering issue. We propose a stabilizer that maintains temporal coherence by preserving smooth changes of face expressions in consecutive frames. Quantitative and qualitative analyses reveal
that our method, as the pioneering 4D face video editor, achieves state-of-the-art performance in comparison to existing 2D or 3D-based approaches independently addressing identity and motion. Codes will be released.


https://github.com/ZHANG1023/FED-NeRF/assets/55280162/73e7aa2a-43f0-4793-a0a9-995d0acd49aa

## Paper & Citation
Link to [**Paper**](https://arxiv.org/abs/2401.02616) 

If you find this work useful for your research, please cite our paper:

```bibtex
@misc{zhang2024fednerf,
      title={FED-NeRF: Achieve High 3D Consistency and Temporal Coherence for Face Video Editing on Dynamic NeRF}, 
      author={Hao Zhang and Yu-Wing Tai and Chi-Keung Tang},
      year={2024},
      eprint={2401.02616},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
