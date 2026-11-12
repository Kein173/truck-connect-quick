Truck Connect Quick v22 — live CMR document framing

Changes from v21:
- Camera preview uses a compact portrait viewfinder instead of an elongated full-height preview.
- Live on-device page detection runs while the camera is open.
- A white four-corner outline appears around a detected page; it turns green when detection is stable.
- The captured page is cropped and perspective-corrected using a fresh detection at capture time.
- Existing PDF creation, sharing, and temporary-file cleanup behavior is preserved.

Install by replacing the files in the GitHub Pages repository with the contents of this archive.
Camera access requires HTTPS and permission from the browser. Detection works best with a light CMR sheet on a darker, plain surface.
