# InSong-SVC project page

Static project page for **InSong-SVC: Optimizing Singing Voice Conversion for the Final Mix**.

## Setup

Place the extracted contents at the repository root, with index.html directly at the root and the assets folder next to it. No build step or dependencies are required. Configure GitHub Pages to serve this branch from the repository root.

## Audio samples

This package intentionally contains no audio files. The 12 conversion directions, six systems, and three playback modes remain available; sample cards display “Audio sample coming soon”. No missing audio files are requested.

When audio is ready, add its files under relative paths in this repository, then update the inline const D object in index.html: mix, source, and prompt are the three reference paths; systems contains raw, add, and lufs paths for each system. Replace the corresponding null values with relative paths. Keep paths relative so the page also works under a GitHub project-site subdirectory.
