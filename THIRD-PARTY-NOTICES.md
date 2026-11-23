# Third-party software

The Penumbra installer bundles the following open-source software. Each keeps its own licence; thanks to their authors. The licence texts of the Python packages are installed with them, in each package's `.dist-info` folder under `engine\python\Lib\site-packages` in Penumbra's install folder.

| Component | Version | Licence | Home |
|---|---|---|---|
| Python (embeddable) | 3.13.2 | PSF License | https://www.python.org |
| NumPy | 2.5.4 | BSD-3-Clause (plus 0BSD, MIT, Zlib, CC0-1.0 for parts) | https://numpy.org |
| Pillow | 13.0.0 | MIT-CMU | https://python-pillow.org |
| PyAudioWPatch (with PortAudio) | 0.2.12.9 | Apache-2.0 | https://github.com/s0d3s/PyAudioWPatch |
| typing_extensions | 4.16.0 | PSF-2.0 | https://github.com/python/typing_extensions |
| PyWinRT (`winrt-runtime` and the `winrt-Windows.*` packages) | 4.0.3 / 10.0.28000 | MIT | https://github.com/pywinrt/pywinrt |
| .NET runtime, WPF and Windows Forms | 8.0 | MIT | https://dotnet.microsoft.com |
| Vortice.Windows (Direct3D 11, Direct2D, DirectComposition, DXGI, D3DCompiler, Mathematics) | 3.8.3 | MIT | https://github.com/amerkoleci/Vortice.Windows |
| SharpGen.Runtime | (with Vortice) | MIT | https://github.com/SharpGenTools/SharpGenTools |

The installer itself is made with [Inno Setup](https://jrsoftware.org/isinfo.php) (Inno Setup License).

Online services Penumbra uses (only as described under Privacy in the README): [LRCLIB](https://lrclib.net) for lyrics, and Apple's iTunes Search for sharp covers on the Now playing screen.
