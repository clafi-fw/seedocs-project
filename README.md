# ClaFi SeeDocs project

ClaFi authors maintain this SeeDocs project to build and publish the framework's documentation
portal. Its intermediate files include the API declarations scanned from the framework
(`Surface.cfg`) and the notes authors write for those declarations (`footnotes/`).

## Checking and updating the API declarations

To scan or check the framework, clone [ClaFi](https://github.com/clafi-fw/cpp) into `Lib/ClaFi`
and this repository into `SeeDocs Projects/ClaFi` under the same parent folder. For another
layout, set `Sources` in `Project.cfg` to the framework's `Source` folder. Relative paths are
resolved from this project.

Run these commands from this folder with the framework's `SeeDocsCli` on your path.

```sh
SeeDocsCli check
SeeDocsCli scan
```
