# 2.6.0:

### Major updates
 - WebGL2 context support.WebGL2 is initialized instead of WebGL 1 when available ([deltakosh](https://github.com/deltakosh))
 - Support for [Vertex Array Objects](https://www.opengl.org/registry/specs/ARB/vertex_array_object.txt) ([deltakosh](https://github.com/deltakosh))
 - New Unity 5 Editor Toolkit. Complete pipeline integration [Doc](TODO) - ([MackeyK24](https://github.com/MackeyK24))
 - New DebugLayer. [Doc](TODO) - ([temechon](https://github.com/temechon))
 - New `VideoTexture.CreateFromWebCam` to generate video texture using WebRTC. [Demo](https://www.babylonjs-playground.com#1R77YT#2) - (Sebastien Vandenberghe)(https://github.com/sebavanmicrosoft) / ([deltakosh](https://github.com/deltakosh))
 - New `HolographicCamera` to support rendering on Windows Holographic. - ([sebavan](https://github.com/sebavan))

### Updates
 - `Effect.getVertexShaderSource()` and `Effect.getFragmentShaderSource()` now returns the effective shader code (including evaluation of #define) ([deltakosh](https://github.com/deltakosh))

### Exporters
    
### API doc

### Bug fixes
 - Fixed an issue withaspect ratio when using CreateScreenshot ([deltakosh](https://github.com/deltakosh))

### Breaking changes
