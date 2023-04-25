# TODO

## Issues

Stuff to be fixed...

- ClipSkip not updated on read gen info
- Run VAE with hires at 1280
- Transformers version
- Move Restart Server from WebUI to Launch and reload modules
- gr.Dropdowns with None selected

## Features

Stuff to be added...

- Add Gradio theme maker
- Create new GitHub hooks/actions for CI/CD  
- Redo Extensions tab: see <https://vladmandic.github.io/sd-extension-manager/pages/extensions.html>
- Stream-load models as option for slow storage
- Autodetect nVidia and AMD: `nvidia-smi` vs `rocm-smi`
- [Temporal Weighing](https://github.com/comfyanonymous/ComfyUI/discussions/473)

## Investigate

Stuff to be investigated...

- Torch Compile
- `Torch-DirectML`
- `TensorRT`

## Merge PRs

Pick & merge PRs from main repo...

- Merge backlog: <https://github.com/vladmandic/automatic/pulls>

## Models

StabilityAI is working on new stuff...

- SD XL
- SD ReImagined

## Integration

Tech that can be integrated as part of the core workflow...

- [Merge without distortion](https://github.com/ogkalu2/Merge-Stable-Diffusion-models-without-distortion)
- [Weighted merges](https://github.com/bbc-mc/sdweb-merge-block-weighted-gui/tree/master)
- [Null-text inversion](https://github.com/ouhenio/null-text-inversion-colab)
- [Custom diffusion](https://github.com/guaneec/custom-diffusion-webui), [Custom diffusion](https://www.cs.cmu.edu/~custom-diffusion/)
- [Dream artist](https://github.com/7eu7d7/DreamArtist-sd-webui-extension)

## Random

- Bunch of stuff: <https://pharmapsychotic.com/tools.html>

### Pending Code Updates

- update GPU utility search paths for better GPU type detection
