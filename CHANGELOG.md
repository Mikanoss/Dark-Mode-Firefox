# Version 1.1
- Removed duplicate `getComputedStyle` calls by caching per element
- Reused parsed RGB and luminance values instead of recalculating
- Combined and simplified invalid color checks
- Streamlined `TrackDOMTree` walker loop
- Flattened `MutationObserver` loop structure
- Avoided unnecessary fallback to `background-color` when not needed
- Added check to detect transparency on `:root` element
- Renamed some variables
- Expanded some functions to new lines

# Version 1.0
- Initial Release