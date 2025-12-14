# Window Placement Sample

These samples, and the header files under cpp\inc, are intended to show how to
implement scenarios like apps storing their Window positions and using them to
launch where they were when closed. These headers are described in more detail
in these associated readme pages:

 - [RememberingWindowPositions.md](RememberingWindowPositions.md)
 - [Win32Concepts.md](Win32Concepts.md)

## Samples

### SaveRestoreSample

This app creates a window that launches where it was when last closed, using
the helpers in [PlacementEx.h](cpp\inc\PlacementEx.h). It also exposes options
that the user can choose, which change this initial position based on personal
preference.


### FullScreenSample

This app creates a window that can enter FullScreen mode, where it covers the
whole monitor (including the taskbar) and has no title bar. Exiting FullScreen
mode is similar to storing the window position when closing, and this sample
uses PlacementEx.h helpers to do both.
