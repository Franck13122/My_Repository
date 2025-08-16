
# Physically Based Rendering Notes (Static Site)

This mini-site contains compact diagrams and explanations for:

1. Light energy mapping (radiance → linear rendering → tone mapping → gamma → display nits)
2. GPU ray tracing pipeline (raygen, traversal, hit/miss/any-hit, denoiser, final frame)
3. Shader↔RT core handshake for multiple bounces (how `TraceRay()` proceeds)

## Use
- Open `index.html` directly in a browser.
- Or upload the folder to a static host (GitHub Pages, Netlify) as-is.

## License
- Personal use and educational sharing allowed. No attribution required.
