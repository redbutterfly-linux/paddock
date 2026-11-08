# paddock
This is the main core repository for Red Butterfly Linux.

# structure:
```
├── pkgs
│   └── firefox
│       ├── firefox.lua         - The declarative config for rbpt.
│       ├── info.lua            - The main pkg manifest.
│       └── scrs                - The folders having scripts.
│           └── build.lua        - The build script
```

In `scrs` you can add more scripts but as of now the supported are:
- `build.lua` - Return the build command and the options.
- `hooks.lua` - Run the hooks for certain operations.