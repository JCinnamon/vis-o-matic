# vis-o-matic
lightweight browser-based suite of visual image processing, analysis, and visualization tools

## Maintaining the suite

There is no build step. Each tool is its own `index.html` in its own repository, and you edit that file directly. Shared code is copied into each tool (look for the `__VOM_..._START__` comments), so a change to shared code must be made in every copy.

## Deleting a project

- **Browser project:** you choose each time. Tick "Also delete images and outputs" to delete them from this browser, which can't be undone. A dataset also used by another project is kept. Leave it unticked and the images stay in Image Manager, while outputs and the run log stay in browser storage with nothing listing them.
- **Folder project:** only the link is removed. The folder isn't touched.
