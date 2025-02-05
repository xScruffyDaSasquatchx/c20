**LM_Tool** is a community-modified version of [H1CE Tool][hek/tool] which improves the speed of [lightmaps][] generation (radiosity). LM_Tool achieves this by disabling some runtime debug checks present in the official Tool release, and can _only_ be used for radiosity; all other functions are disabled.

```.alert
The updated [H1A Tool][h1a-tool] supports a `-noassert` flag that, with its other lightmapping optimizations, greatly outperforms LM_Tool and is now the fastest lightmapping solution.

![](lm-time.jpg)
```

# Installation
Simply download and extract `LM_Tool.exe` and place it in Halo's directory where `tool.exe` would be found.

# Usage
LM_Tool is used from the command line in the same way as Tool, just change the EXE name. For example:

```
LM_Tool.exe lightmaps levels\test\ratrace\ratrace ratrace 1 0.01
```

_See [Tool documentation][tool#lightmaps] for more details of using and troubleshooting lightmaps._
