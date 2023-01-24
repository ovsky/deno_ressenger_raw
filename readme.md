
## 📦 ressenger - ReMessenger - raw files

![icon](https://i.ibb.co/S5KqgBZ/ressenger.png)

---
The raw data and build files for ressenger - ultralight and secure Messenger ReactJS handler running on Deno.

The raw repository that contains data of:
- [deno-modern-installer](https://deno.land/x/modern_installer): for building and bundling
- [denojs-framework](https://gluonjs.org/): for handling web-based behaviour
- and finally: `deno_ressenger_raw\gluon-deno\ressenger`:

[thanks to `guonjs` it can be rebuilt to handle any website]

## Releases:
Latest downloadable releases: 
https://github.com/ovsky/deno_ressenger_raw/releases

## Build:

Run:  
```shell
cd gluon-deno\ressenger
deno compile -A --unstable index.js
deno run -A --unstable build.ts
```

The new executable and the installer will be printed out.
If you want to hide the cmd, use `start.bat`.