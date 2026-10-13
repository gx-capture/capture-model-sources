# pyannote speaker-diarization-community-1

This directory redistributes, unmodified, the model files of
[pyannote/speaker-diarization-community-1](https://huggingface.co/pyannote/speaker-diarization-community-1)
at revision `3533c8cf8e369892e6b79ff1bf80f7b0286a54ee`.

The pipeline is released by pyannote under the Creative Commons Attribution 4.0
International License (CC-BY-4.0); the license text is in
`LICENSE-CC-BY-4.0.txt`. The upstream model card and the component notes are
kept unchanged under `../upstream/`.

| File | Origin | SHA-256 |
| --- | --- | --- |
| `config.yaml` | pyannote pipeline configuration | `5ce2bfa9a938dc132cec1172592d65173cbb8f444ea1e4133f10f9391de155be` |
| `segmentation/pytorch_model.bin` | pyannote segmentation model | `7ad24338d844fb95985486eb1a464e32d229f6d7a03c9abe60f978bacf3f816e` |
| `embedding/pytorch_model.bin` | WeSpeaker ResNet34-LM trained on VoxCeleb, copied by pyannote from `pyannote/wespeaker-voxceleb-resnet34-LM`; CC-BY-4.0 per its upstream note | `6f10ff60898a1d185fa22e1d11e0bfa8a92efec811f11bca48cb8cafebefd929` |
| `plda/plda.npz` | PLDA model trained by the BUT Speech@FIT group | `9b77bcd840692710dd3496f62ecfeed8d8e5f002fd991b785079b244eab7d255` |
| `plda/xvec_transform.npz` | PLDA transform by the BUT Speech@FIT group | `325f1ce8e48f7e55e9c8aa47e05d2766b7c48c4b25b8de8dd751e7a4cc5fbe8f` |

## Citations

- Alexis Plaquet and Hervé Bredin. "Powerset multi-class cross entropy loss for
  neural speaker diarization." Proc. INTERSPEECH 2023.
- Hongji Wang et al. "Wespeaker: A research and production oriented speaker
  embedding learning toolkit." ICASSP 2023.
- Federico Landini, Ján Profant, Mireia Diez and Lukáš Burget. "Bayesian HMM
  clustering of x-vector sequences (VBx) in speaker diarization: theory,
  implementation and analysis on standard tasks."

The full BibTeX entries are in `../upstream/README.md`.
