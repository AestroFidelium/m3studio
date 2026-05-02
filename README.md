## Patches for Headless/Blender 5.0

This fork contains patches required to run m3studio in Blender's headless mode (`--background`):

| File | Patch |
|------|-------|
| `bl_graphics_draw.py` | Safe fallback when `gpu.shader` unavailable |
| `m3_animations.py` | FakeFCurves wrapper for Blender 5.0 Action API |
| `io_m3_import.py` | fcurves API fixes, disable `material_remove` in headless |

Used by: [m3-to-glb](https://github.com/AestroFidelium/m3-to-glb) converter
