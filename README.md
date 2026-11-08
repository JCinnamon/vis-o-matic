# vis-o-matic
lightweight browser-based suite of visual image processing, analysis, and visualization tools

## Maintaining the suite

There is no build step. Each tool is its own `index.html` in its own repository, and you edit that file directly. Shared code is copied into each tool (look for the `__VOM_..._START__` comments), so a change to shared code must be made in every copy.
