# Pausable Source Record filter for OBS Studio

Plugin for OBS Studio to make sources available to record via a filter - Now with the ability to pause all recordings simultaneously.

# Download

Latest macOS packages (includes arm64, x86_64, and universal):
https://github.com/mreflow/pausable-obs-source-record/releases/tag/v0.4.6-pause-sync

Original upstream page:
https://obsproject.com/forum/resources/source-record.1285/

# Build
1. In-tree build
    - Build OBS Studio: https://obsproject.com/wiki/Install-Instructions
    - Check out this repository to plugins/source-record
    - Add `add_subdirectory(source-record)` to plugins/CMakeLists.txt
    - Rebuild OBS Studio

1. Stand-alone build (Linux only)
    - Verify that you have package with development files for OBS
    - Check out this repository and run `cmake -S . -B build -DBUILD_OUT_OF_TREE=On && cmake --build build`

# Donation To Original Creator
https://www.paypal.me/exeldro
