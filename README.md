# FluxML Ecosystem Coordination

Find us on Zulip: https://julialang.zulipchat.com/#streams/237432/ml-ecosystem-coordination

Our meeting recordings: https://www.youtube.com/playlist?list=PLP8iPy9hna6T_ILHzPw43BFGngBcNmugQ

Join the long-term conversation under the [Discussions tab](https://github.com/JuliaCommunity/ML-Coordination-Tracker/discussions). This is also where we post more structured design documentation and Q&A about Flux. If you have an idea for improving the ecosystem, you can post it there.

This is still very much a work in progress, and **we welcome all contributions**! For a list of issues and action points, see the [general issues project](https://github.com/JuliaCommunity/ML-Coordination-Tracker/projects/5). More specific projects can be found under the [Projects tab](https://github.com/JuliaCommunity/ML-Coordination-Tracker/projects).

Many of our contributions might be spread across several repos, so if you want to get involved and don't know where to start, you should ping us on Zulip. Or if you see that someone is assigned to a specific issue, you can DM them on Zulip.

## Repositories

Below is a list of repositories that we actively contribute to (this is also a convenient list of the FluxML ecosystem):
- [Flux.jl](https://github.com/FluxML/Flux.jl): A 100% pure-Julia deep learning stack. Provides lightweight abstractions on top of Julia's core GPU and AD support.
- [Zygote.jl](https://github.com/FluxML/Zygote.jl): The source-to-source AD tool that backs Flux.jl.
- [FastAI.jl](https://github.com/FluxML/FastAI.jl): A Julia port of Python's [fastai](https://docs.fast.ai) stack (built upon the packages listed below).
- [FluxTraining.jl](https://github.com/lorenzoh/FluxTraining.jl): Easily customized training loops, a large library of useful metrics, and many useful utilities (such as logging)
- [DataLoaders.jl](https://github.com/lorenzoh/DataLoaders.jl): Multi-threaded data loading built on MLDataPattern.jl (similar to PyTorch's [`DataLoader`](https://pytorch.org/docs/stable/data.html#torch.utils.data.DataLoader)).
- [MLDataPattern.jl](https://github.com/JuliaML/MLDataPattern.jl): Utility package for subsetting, partitioning, iterating, and resampling of datasets.
- [MLDatasets.jl](https://github.com/JuliaML/MLDatasets.jl): A collection of common machine learning datasets.
- [DataAugmentation.jl](https://github.com/lorenzoh/DataAugmentation.jl): Utilities for augmenting image-like data
- [Metalhead.jl](https://github.com/FluxML/Metalhead.jl): Computer vision models for Flux 
- [Transformers.jl](https://github.com/chengchingwen/Transformers.jl): NLP transformer-based models for Flux
