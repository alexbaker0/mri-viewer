# MRI Viewer

A browser-based 3D MRI viewer: three-plane slices plus a rotatable volume render, with colour maps, window/threshold, tissue presets, a clip plane and a measuring tool. Built on [NiiVue](https://github.com/niivue/niivue).

**Try it:** https://alexbaker0.github.io/mri-viewer/

It opens with openly licensed sample head scans. Visitors can open their own NIfTI files (`.nii` / `.nii.gz`); they are read locally in the browser and never uploaded. Credits and licences: [THIRD_PARTY.md](THIRD_PARTY.md).

(The original project also includes a standard-library-only Python DICOM → NIfTI converter, kept private along with the scans it was written for.)
