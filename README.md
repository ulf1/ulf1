## Recently

- Markov Regime Switching - [trading-regime](https://github.com/ulf1/trading-regime) - Training parallized with PyTorch; daily GCP Cloud Run workflow for data caching, ticker exploration and model recalibration ([docs](https://github.com/ulf1/trading-regime/tree/main/docs), [dashboard](https://showresults-service-6gmepoiioa-ew.a.run.app/))
- Chain-of-Thought (CoT) Backend - [mas-inquiry](https://github.com/ulf1/mas-inquiry) - Multi-agent system to dissect a human inquiry with langgraph and smaller Gemini Flash Lite models ([docs](https://github.com/ulf1/mas-inquiry/tree/main/docs))
- RAG Desktop App - [streamlit-rag-biblio](https://github.com/ulf1/streamlit-rag-biblio) - streamlit chats with langgraph (Mistral, AcademicCloud). literature files are indexed as RAG. pyinstaller for MacOS and Win Desktop apps.

### Nocode Vibe Coding Apps
All first shots, no further dev planned. Basically the 2026 version of ui mock-up generation. 
- [Prompt Mastermind](https://studio--studio-6780315578-30416.us-central1.hosted.app/) - the app generates an ai  image, and the user must guess the prompt that created the image.
- [The Glitch Hunter](https://studio--studio-8148573502-74cf7.us-central1.hosted.app/) - copy paste your code snippet, and the LLM will check and comment your code in Gen Z slang.

## Sparse Connectivity

- [keras-spconn](https://github.com/ulf1/keras-spconn) (not published as pypi) - uses `tf.GradientTape` to implement Dynamic Sparsity as outer training loop [[sprg](https://github.com/ulf1/keras-spconn/blob/main/keras_spconn/sprg.py)]
- [10.31219/osf.io/bgkpv](https://doi.org/10.31219/osf.io/bgkpv) - HCNN implementation with Dynamic Sparsity (a HCNN is an extremly wide an extremly sparse RNN without input matrix; only few RNN states are observable)
- Note: In general state- or neuron-level sparsity does't parallize well with GPU; it might more appropriate for CPU based architectures

## Software packages for the Evidence project (2020-2023)
The DFG project "Evidence" ([433249742](https://gepris.dfg.de/gepris/projekt/433249742)) ran from 2020 till Jul. 2023 at [BBAW](https://www.bbaw.de/). The following software packages are maintained by [@ulf1](https://github.com/ulf1) without compensations since Aug. 2023.

Feature Preprocessing:
- [torch-hrp](https://github.com/ulf1/torch-hrp): Hashed Random Projection layer for PyTorch (0.2.0). Zenodo. https://doi.org/10.5281/zenodo.8131955 
- [bool-to-int8-ray](https://github.com/ulf1/bool-to-int8-ray): Boolean Vectors to 8-bit Integer Vector Serialization with Ray.io (0.2.0). Zenodo. https://doi.org/10.5281/zenodo.8131973 
- [node-distance](https://github.com/ulf1/node-distance): Tree node distances as features. (0.2.0). Zenodo. https://doi.org/10.5281/zenodo.8132055 
- [treesimi](https://github.com/ulf1/treesimi): Shingling for measuring tree similarity (0.3.0). Zenodo. https://doi.org/10.5281/zenodo.8132026 
- [ipasymbols](https://github.com/ulf1/ipasymbols): Properties of IPA symbols for data analysis. (0.1.0-a). Zenodo. https://doi.org/10.5281/zenodo.8132009 
- [kshingle](https://github.com/ulf1/kshingle): Shingling text data (0.10.0). Zenodo. https://doi.org/10.5281/zenodo.7096407 
- [quaxa](https://github.com/ulf1/quaxa): QUAlity of sentence eXAmples scoring (0.1.0). Zenodo. https://doi.org/10.5281/zenodo.8183110

Best-Worst Scaling
- [bwsample](https://github.com/ulf1/bwsample): Processing Best-Worst Scaling data. Journal of Open Source Software, 6(64), 3324, https://doi.org/10.21105/joss.03324 ; see NPM package “bwsample”, Version 0.1.5, https://www.npmjs.com/package/bwsample 

Javascript
- [histpdf](https://github.com/ulf1/histpdf), Version 0.1.0, https://www.npmjs.com/package/histpdf 
- [vue-fit2box](https://github.com/ulf1/vue-fit2box): Fit Text into an Element by Font-Resizing (1.0.0). Zenodo. https://doi.org/10.5281/zenodo.4604361 
