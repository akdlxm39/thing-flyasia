# THING — FLY ASIA

Public exhibition website for the THING robotic hand.

- Home: `/`
- Korean poster: `ko/`
- English poster: `en/`
- Demonstration videos: `demos/`
- Combined Korean print PDF: `downloads/THING-poster-ko.pdf` (2 pages, 584 × 841 mm each)
- Shared navigation styles: `assets/site.css`

GitHub Pages deploys from the `main` branch, root directory. Videos are ordinary MP4 files, not LFS pointers.

The posters use `assets/system-architecture.png`, exported at 3202 × 2118 pixels. Update the cache version in both poster pages when replacing an image. When regenerating the Korean PDF, replace `downloads/THING-poster-ko.pdf` and update its download-link cache version on all four pages.

Product images: NVIDIA and Logitech. Mechanical and demonstration material: THING team. Additional artwork credits and licenses are retained under `assets/`.

## Re-enable repository links

The source project is private. Its original URL is preserved in the gray Project GitHub links on the home and English pages. To enable them after the repository becomes public, remove `aria-disabled="true"` and `tabindex="-1"`, and update the Private repository labels. The click handlers only block links while `aria-disabled` is true.
