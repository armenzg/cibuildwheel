---
title: Working examples
---

<!-- START bin/projects.py -->

<!-- this section is generated by bin/projects.py. Don't edit it directly, instead, edit docs/data/projects.yml -->

| Name                              | CI | OS | Notes |
|-----------------------------------|----|----|:------|
| [scikit-learn][]                  | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | The machine learning library. A complex but clean config using many of cibuildwheel's features to build a large project with Cython and C++ extensions.  |
| [Matplotlib][]                    | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | The venerable Matplotlib, a Python library with C++ portions |
| [MyPy][]                          | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | MyPyC, the compiled component of MyPy. |
| [psutil][]                        | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Cross-platform lib for process and system monitoring in Python |
| [scikit-image][]                  | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Image processing library. Uses cibuildwheel to build and test a project that uses Cython with platform-native code.  |
| [twisted-iocpsupport][]           | ![github icon][] | ![windows icon][] | A submodule of Twisted that hooks into native C APIs using Cython. |
| [cmake][]                         | ![github icon][] ![travisci icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Multitagged binary builds for all supported platforms, using cibw 2 config configuration. |
| [websockets][]                    | ![travisci icon][] | ![apple icon][] ![linux icon][] | Library for building WebSocket servers and clients. Mostly written in Python, with a small C 'speedups' extension module.  |
| [pyzmq][]                         | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Python bindings for zeromq, the networking library. Uses Cython and CFFI.  |
| [aiortc][]                        | ![github icon][] | ![apple icon][] ![linux icon][] | WebRTC and ORTC implementation for Python using asyncio. |
| [River][]                         | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | 🌊 Online machine learning in Python |
| [coverage.py][]                   | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | The coverage tool for Python |
| [numexpr][]                       | ![github icon][] ![travisci icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Fast numerical array expression evaluator for Python, NumPy, PyTables, pandas, bcolz and more |
| [h5py][]                          | ![azurepipelines icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | HDF5 for Python -- The h5py package is a Pythonic interface to the HDF5 binary data format. |
| [Dependency Injector][]           | ![travisci icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Dependency injection framework for Python, uses Windows TravisCI |
| [PyAV][]                          | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Pythonic bindings for FFmpeg's libraries. |
| [PyTables][]                      | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | A Python package to manage extremely large amounts of data |
| [ruptures][]                      | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Extensive Cython + NumPy [pyproject.toml](https://github.com/deepcharles/ruptures/blob/master/pyproject.toml) example. |
| [aioquic][]                       | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | QUIC and HTTP/3 implementation in Python |
| [pikepdf][]                       | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | A Python library for reading and writing PDF, powered by qpdf |
| [google neuroglancer][]           | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | WebGL-based viewer for volumetric data |
| [DeepForest][]                    | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | An Efficient, Scalable and Optimized Python Framework for Deep Forest (2021.2.1) |
| [AutoPy][]                        | ![travisci icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Includes a Windows Travis build. |
| [Parselmouth][]                   | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | A Python interface to the Praat software package, using pybind11, C++17 and CMake, with the core Praat static library built only once and shared between wheels. |
| [python-rapidjson][]              | ![travisci icon][] ![gitlab icon][] ![appveyor icon][] | ![windows icon][] ![linux icon][] | Python wrapper around rapidjson |
| [Rtree][]                         | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Rtree: spatial index for Python GIS ¶ |
| [markupsafe][]                    | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Safely add untrusted strings to HTML/XML markup. |
| [H3-py][]                         | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Python bindings for H3, a hierarchical hexagonal geospatial indexing system |
| [python-snappy][]                 | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Python bindings for the snappy google library |
| [pybind11 cmake_example][]        | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Example pybind11 module built with a CMake-based build system |
| [KDEpy][]                         | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Kernel Density Estimation in Python |
| [cyvcf2][]                        | ![github icon][] | ![apple icon][] ![linux icon][] | cython + htslib == fast VCF and BCF processing |
| [dd-trace-py][]                   | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Uses custom alternate arch emulation on GitHub |
| [pybind11 python_example][]       | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Example pybind11 module built with a Python-based build system |
| [sourmash][]                      | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Quickly search, compare, and analyze genomic and metagenomic data sets. |
| [tgcalls][]                       | ![github icon][] | ![apple icon][] ![windows icon][] | Python `pybind11` binding to Telegram's WebRTC library with third party dependencies like `OpenSSL`, `MozJPEG`, `FFmpeg`, etc. |
| [time-machine][]                  | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Time mocking library using only the CPython C API. |
| [matrixprofile][]                 | ![travisci icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | A Python 3 library making time series data mining tasks, utilizing matrix profile algorithms, accessible to everyone. |
| [iminuit][]                       | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Jupyter-friendly Python interface for C++ MINUIT2 |
| [CTranslate2][]                   | ![github icon][] | ![apple icon][] ![linux icon][] | Includes libraries from the [Intel oneAPI toolkit](https://software.intel.com/content/www/us/en/develop/tools/oneapi/base-toolkit.html). The Linux wheels also include CUDA libraries for GPU execution. |
| [jq.py][]                         | ![travisci icon][] | ![apple icon][] ![linux icon][] | Python bindings for jq |
| [Tokenizer][]                     | ![github icon][] ![travisci icon][] | ![apple icon][] ![linux icon][] | Fast and customizable text tokenization library with BPE and SentencePiece support |
| [PyGLM][]                         | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Fast OpenGL Mathematics (GLM) for Python |
| [bx-python][]                     | ![travisci icon][] | ![apple icon][] ![linux icon][] | A library that includes Cython extensions. |
| [iDynTree][]                      | ![github icon][] | ![linux icon][] | Uses manylinux_2_24 |
| [boost-histogram][]               | ![github icon][] ![travisci icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Supports full range of wheels, including PyPy and alternate archs. |
| [pybase64][]                      | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Fast Base64 encoding/decoding in Python |
| [TgCrypto][]                      | ![travisci icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Includes a Windows Travis build. |
| [etebase-py][]                    | ![travisci icon][] | ![linux icon][] | Python bindings to a Rust library using `setuptools-rust`, and `sccache` for improved speed. |
| [fathon][]                        | ![travisci icon][] | ![apple icon][] ![linux icon][] | python package for DFA (Detrended Fluctuation Analysis) and related algorithms |
| [pyjet][]                         | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | The interface between FastJet and NumPy |
| [numpythia][]                     | ![github icon][] | ![apple icon][] ![linux icon][] | The interface between PYTHIA and NumPy |
| [polaroid][]                      | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Full range of wheels for setuptools rust, with auto release and PyPI deploy. |
| [Imagecodecs (fork)][]            | ![azurepipelines icon][] | ![apple icon][] ![linux icon][] | Over 20 external dependencies in compiled libraries, custom docker image, `libomp`, `openblas` and `install_name_tool` for macOS. |
| [ninja][]                         | ![github icon][] ![travisci icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Multitagged binary builds for all supported platforms, using cibw 2 config configuration. |
| [pybind11 scikit_build_example][] | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | An example combining scikit-build and pybind11 |
| [GSD][]                           | ![github icon][] | ![apple icon][] ![linux icon][] ![windows icon][] | Cython and NumPy project with 64-bit wheels. |
| [pyinstrument_cext][]             | ![travisci icon][] ![appveyor icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | A simple C extension, without external dependencies |
| [xmlstarlet][]                    | ![github icon][] | ![windows icon][] ![apple icon][] ![linux icon][] | Python 3.6+ CFFI bindings with true MSVC build. |
| [CorrectionLib][]                 | ![github icon][] | ![apple icon][] ![linux icon][] | Structured JSON powered correction library for HEP, designed for the CMS experiment at CERN. |
| [SiPM][]                          | ![github icon][] | ![apple icon][] ![linux icon][] | High performance library for SiPM detectors simulation using C++17, OpenMP and AVX2 intrinsics. |

[scikit-learn]: https://github.com/scikit-learn/scikit-learn
[Matplotlib]: https://github.com/matplotlib/matplotlib
[MyPy]: https://github.com/mypyc/mypy_mypyc-wheels
[psutil]: https://github.com/giampaolo/psutil
[scikit-image]: https://github.com/scikit-image/scikit-image
[twisted-iocpsupport]: https://github.com/twisted/twisted-iocpsupport
[cmake]: https://github.com/scikit-build/cmake-python-distributions
[websockets]: https://github.com/aaugustin/websockets
[pyzmq]: https://github.com/zeromq/pyzmq
[aiortc]: https://github.com/aiortc/aiortc
[River]: https://github.com/online-ml/river
[coverage.py]: https://github.com/nedbat/coveragepy
[numexpr]: https://github.com/pydata/numexpr
[h5py]: https://github.com/h5py/h5py
[Dependency Injector]: https://github.com/ets-labs/python-dependency-injector
[PyAV]: https://github.com/PyAV-Org/PyAV
[PyTables]: https://github.com/PyTables/PyTables
[ruptures]: https://github.com/deepcharles/ruptures
[aioquic]: https://github.com/aiortc/aioquic
[pikepdf]: https://github.com/pikepdf/pikepdf
[google neuroglancer]: https://github.com/google/neuroglancer
[DeepForest]: https://github.com/LAMDA-NJU/Deep-Forest
[AutoPy]: https://github.com/autopilot-rs/autopy
[Parselmouth]: https://github.com/YannickJadoul/Parselmouth
[python-rapidjson]: https://github.com/python-rapidjson/python-rapidjson
[Rtree]: https://github.com/Toblerity/rtree
[markupsafe]: https://github.com/pallets/markupsafe
[H3-py]: https://github.com/uber/h3-py
[python-snappy]: https://github.com/andrix/python-snappy
[pybind11 cmake_example]: https://github.com/pybind/cmake_example
[KDEpy]: https://github.com/tommyod/KDEpy
[cyvcf2]: https://github.com/brentp/cyvcf2
[dd-trace-py]: https://github.com/DataDog/dd-trace-py
[pybind11 python_example]: https://github.com/pybind/python_example
[sourmash]: https://github.com/dib-lab/sourmash
[tgcalls]: https://github.com/MarshalX/tgcalls
[time-machine]: https://github.com/adamchainz/time-machine
[matrixprofile]: https://github.com/matrix-profile-foundation/matrixprofile
[iminuit]: https://github.com/scikit-hep/iminuit
[CTranslate2]: https://github.com/OpenNMT/CTranslate2
[jq.py]: https://github.com/mwilliamson/jq.py
[Tokenizer]: https://github.com/OpenNMT/Tokenizer
[PyGLM]: https://github.com/Zuzu-Typ/PyGLM
[bx-python]: https://github.com/bxlab/bx-python
[iDynTree]: https://github.com/robotology/idyntree
[boost-histogram]: https://github.com/scikit-hep/boost-histogram
[pybase64]: https://github.com/mayeut/pybase64
[TgCrypto]: https://github.com/pyrogram/tgcrypto
[etebase-py]: https://github.com/etesync/etebase-py
[fathon]: https://github.com/stfbnc/fathon
[pyjet]: https://github.com/scikit-hep/pyjet
[numpythia]: https://github.com/scikit-hep/numpythia
[polaroid]: https://github.com/daggy1234/polaroid
[Imagecodecs (fork)]: https://github.com/czaki/imagecodecs_build
[ninja]: https://github.com/scikit-build/ninja-python-distributions
[pybind11 scikit_build_example]: https://github.com/pybind/scikit_build_example
[GSD]: https://github.com/glotzerlab/gsd
[pyinstrument_cext]: https://github.com/joerick/pyinstrument_cext
[xmlstarlet]: https://github.com/dimitern/xmlstarlet
[CorrectionLib]: https://github.com/cms-nanoAOD/correctionlib
[SiPM]: https://github.com/EdoPro98/SimSiPM

[appveyor icon]: data/readme_icons/appveyor.svg
[github icon]: data/readme_icons/github.svg
[azurepipelines icon]: data/readme_icons/azurepipelines.svg
[circleci icon]: data/readme_icons/circleci.svg
[gitlab icon]: data/readme_icons/gitlab.svg
[travisci icon]: data/readme_icons/travisci.svg
[windows icon]: data/readme_icons/windows.svg
[apple icon]: data/readme_icons/apple.svg
[linux icon]: data/readme_icons/linux.svg

<!-- scikit-learn: 47064, last pushed 0 days ago -->
<!-- Matplotlib: 14167, last pushed 0 days ago -->
<!-- MyPy: 11232, last pushed 0 days ago -->
<!-- psutil: 7625, last pushed 0 days ago -->
<!-- scikit-image: 4502, last pushed 0 days ago -->
<!-- twisted-iocpsupport: 4358, last pushed 5 days ago -->
<!-- cmake: 4129, last pushed 0 days ago -->
<!-- websockets: 3539, last pushed 0 days ago -->
<!-- pyzmq: 2893, last pushed 5 days ago -->
<!-- aiortc: 2535, last pushed 2 days ago -->
<!-- River: 1899, last pushed 2 days ago -->
<!-- coverage.py: 1702, last pushed 3 days ago -->
<!-- numexpr: 1632, last pushed 60 days ago -->
<!-- h5py: 1580, last pushed 4 days ago -->
<!-- Dependency Injector: 1530, last pushed 11 days ago -->
<!-- PyAV: 1336, last pushed 3 days ago -->
<!-- PyTables: 1057, last pushed 4 days ago -->
<!-- ruptures: 785, last pushed 5 days ago -->
<!-- aioquic: 735, last pushed 3 days ago -->
<!-- pikepdf: 734, last pushed 1 days ago -->
<!-- google neuroglancer: 680, last pushed 4 days ago -->
<!-- DeepForest: 651, last pushed 44 days ago -->
<!-- AutoPy: 568, last pushed 80 days ago -->
<!-- Parselmouth: 547, last pushed 13 days ago -->
<!-- python-rapidjson: 427, last pushed 72 days ago -->
<!-- Rtree: 418, last pushed 169 days ago -->
<!-- markupsafe: 417, last pushed 4 days ago -->
<!-- H3-py: 416, last pushed 0 days ago -->
<!-- python-snappy: 406, last pushed 46 days ago -->
<!-- pybind11 cmake_example: 306, last pushed 13 days ago -->
<!-- KDEpy: 297, last pushed 94 days ago -->
<!-- cyvcf2: 268, last pushed 5 days ago -->
<!-- dd-trace-py: 265, last pushed 2 days ago -->
<!-- pybind11 python_example: 264, last pushed 28 days ago -->
<!-- sourmash: 260, last pushed 1 days ago -->
<!-- tgcalls: 240, last pushed 0 days ago -->
<!-- time-machine: 203, last pushed 4 days ago -->
<!-- matrixprofile: 193, last pushed 72 days ago -->
<!-- iminuit: 183, last pushed 2 days ago -->
<!-- CTranslate2: 183, last pushed 2 days ago -->
<!-- jq.py: 172, last pushed 34 days ago -->
<!-- Tokenizer: 154, last pushed 6 days ago -->
<!-- PyGLM: 112, last pushed 0 days ago -->
<!-- bx-python: 106, last pushed 58 days ago -->
<!-- iDynTree: 86, last pushed 4 days ago -->
<!-- boost-histogram: 83, last pushed 2 days ago -->
<!-- pybase64: 73, last pushed 0 days ago -->
<!-- TgCrypto: 70, last pushed 98 days ago -->
<!-- etebase-py: 51, last pushed 244 days ago -->
<!-- fathon: 35, last pushed 95 days ago -->
<!-- pyjet: 31, last pushed 3 days ago -->
<!-- numpythia: 31, last pushed 27 days ago -->
<!-- polaroid: 24, last pushed 41 days ago -->
<!-- Imagecodecs (fork): 19, last pushed 11 days ago -->
<!-- ninja: 19, last pushed 1 days ago -->
<!-- pybind11 scikit_build_example: 17, last pushed 13 days ago -->
<!-- GSD: 17, last pushed 3 days ago -->
<!-- pyinstrument_cext: 10, last pushed 19 days ago -->
<!-- xmlstarlet: 7, last pushed 45 days ago -->
<!-- CorrectionLib: 6, last pushed 27 days ago -->
<!-- SiPM: 4, last pushed 58 days ago -->

<!-- END bin/projects.py -->

> Add your repo here! Let us know on [GitHub Discussions](https://github.com/pypa/cibuildwheel/discussions/485), or send a PR, adding your information to `docs/data/projects.yml`.
>
> <sup>I'd like to include notes here to indicate why an example might be interesting to cibuildwheel users - the styles/technologies/techniques used in each. Please include that in future additions!</sup>

<style>
.wy-nav-content {
  /* this table benefits from a wider page */
  max-width: 1000px;
}
.rst-content .section table img {
  /* make the icons darker on this page */
  filter: brightness(0.5);
}
</style>
