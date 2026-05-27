# TAG: Tangential Amplifying Guidance

> **TAG: Tangential Amplifying Guidance for Hallucination-Resistant Diffusion Sampling**
>
> [Hyunmin Cho](https://github.com/hyeon-cho)<sup>1\*</sup>, [Donghoon Ahn](https://sunovivid.github.io/)<sup>2\*</sup>, [Susung Hong](https://susunghong.github.io/)<sup>3\*</sup>, [Jee Eun Kim](https://github.com/jeeeun-k)<sup>1</sup>, [Seungryong Kim](https://cvlab.kaist.ac.kr/)<sup>4†</sup>, [Kyong Hwan Jin](https://ipa.korea.ac.kr/)<sup>1†</sup>
>
> <sup>1</sup>Korea University &nbsp;·&nbsp; <sup>2</sup>UC Berkeley &nbsp;·&nbsp; <sup>3</sup>University of Washington &nbsp;·&nbsp; <sup>4</sup>KAIST AI
>
> <sup>\*</sup>Equal contribution &nbsp;·&nbsp; <sup>†</sup>Corresponding authors
>
> **ICML 2026**

[![arXiv](https://img.shields.io/badge/arXiv-2510.04533-b31b1b.svg)](https://arxiv.org/abs/2510.04533)
[![HF Paper](https://img.shields.io/badge/HF-Paper-FFD21E.svg)](https://huggingface.co/papers/2510.04533)
[![HF Demo](https://img.shields.io/badge/HF-Demo-FF7C00.svg)](https://huggingface.co/spaces/hyeoncho01/Tangential-Amplifying-Guidance)
[![Code](https://img.shields.io/badge/Code-GitHub-181717.svg?logo=github)](https://github.com/hyeon-cho/Tangential-Amplifying-Guidance)
[![Project Page](https://img.shields.io/badge/Project-Page-2563eb.svg)](https://hyeon-cho.github.io/TAG/)

This repository hosts the **project page** for TAG — a training-free, plug-and-play diffusion guidance method that amplifies the tangential component of the score, steering samples toward the data manifold and reducing hallucinations with negligible overhead.

## Authors

| Author | Affiliation |
| --- | --- |
| [Hyunmin Cho](https://github.com/hyeon-cho)<sup>\*</sup> | Korea University |
| [Donghoon Ahn](https://sunovivid.github.io/)<sup>\*</sup> | UC Berkeley |
| [Susung Hong](https://susunghong.github.io/)<sup>\*</sup> | University of Washington |
| [Jee Eun Kim](https://github.com/jeeeun-k) | Korea University |
| [Seungryong Kim](https://cvlab.kaist.ac.kr/)<sup>†</sup> | KAIST AI |
| [Kyong Hwan Jin](https://ipa.korea.ac.kr/)<sup>†</sup> | Korea University |

<sup>\*</sup>Equal contribution &nbsp;·&nbsp; <sup>†</sup>Corresponding authors

## Links

- **Project page** (live): https://hyeon-cho.github.io/TAG/
- **Paper** (arXiv): https://arxiv.org/abs/2510.04533 &nbsp;·&nbsp; [PDF](https://arxiv.org/pdf/2510.04533.pdf)
- **Hugging Face Paper**: https://huggingface.co/papers/2510.04533
- **Interactive Demo**: https://huggingface.co/spaces/hyeoncho01/Tangential-Amplifying-Guidance
- **Code**: https://github.com/hyeon-cho/Tangential-Amplifying-Guidance

## Deploying

The page is a single static `index.html` plus self-contained assets under `static/` (CSS, JS, fonts, images). **No build step is required** — push this directory to a GitHub repo, enable GitHub Pages on the branch, and it serves directly. A `.nojekyll` file is included so GitHub does not run Jekyll on the contents.

```bash
# preview locally
python3 -m http.server 8000
# then open http://localhost:8000
```

Only MathJax is loaded from a CDN (`cdn.jsdelivr.net`) since the full self-hosted bundle is ~50 MB; everything else (Bulma, FontAwesome, Academicons, jQuery, Inter font) is vendored under `static/`.

## BibTeX

```bibtex
@inproceedings{cho2026tag,
  title     = {TAG: Tangential Amplifying Guidance for Hallucination-Resistant Diffusion Sampling},
  author    = {Cho, Hyunmin and Ahn, Donghoon and Hong, Susung and Kim, Jee Eun and Kim, Seungryong and Jin, Kyong Hwan},
  booktitle = {Proceedings of the International Conference on Machine Learning (ICML)},
  year      = {2026},
  url       = {https://arxiv.org/abs/2510.04533}
}
```

## Acknowledgements

Built on the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template) by Eliahu Horwitz, adapted from the [Nerfies](https://nerfies.github.io) project page.

## License

The website source is released under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
