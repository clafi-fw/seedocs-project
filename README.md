# ClaFi SeeDocs project

Open this folder in SeeDocs to browse the ClaFi API reference. `Surface.cfg` contains the saved
reference, and `footnotes/` contains the notes linked from declarations.

To scan or check the framework, clone [ClaFi](https://github.com/clafi-fw/cpp) into `Lib/ClaFi`
and this repository into `SeeDocs Projects/ClaFi` under the same parent folder. For another
layout, set `Sources` in `Project.cfg` to the framework's `Source` folder. Relative paths are
resolved from this project.

Run these commands from this folder with the framework's `SeeDocsCli` on your path.

```sh
SeeDocsCli check
SeeDocsCli scan
```
