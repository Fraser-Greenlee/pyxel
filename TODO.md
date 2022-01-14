# ToDo
- [x] Get Python portion of pyxel running in browser
- [ ] Make Pyodide version of Rust Module
    - [x] Find basic requirements.
        - Runs on "Emscripten" OS
        - Use `wasm32-unknown-emscripten` target to it can use libraries.
        - Add as another target in `lib/Makefile`
    - [ ] debug build fail
        - [ ] understand logs
            - [ ] What does the `stdout` mean?
                cargo:rerun-if-env-changed=PYO3_CROSS
                cargo:rerun-if-env-changed=PYO3_CROSS_LIB_DIR
                cargo:rerun-if-env-changed=PYO3_CROSS_PYTHON_VERSION
            - [ ] What file path was it trying to load?
        - [ ] Try make a mini alt project, maybe there's obvious stuff I'm missing?
