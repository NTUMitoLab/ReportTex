# ReportTex: A LaTeX template supporting both English and Traditional Chinese


|<img width="859" alt="Screen Shot 2021-03-12 at 6 50 57 PM" src="https://user-images.githubusercontent.com/29009898/110930292-e3190200-8363-11eb-9f15-2c4f47b68371.png">|<img width="860" alt="Screen Shot 2021-03-12 at 6 51 45 PM" src="https://user-images.githubusercontent.com/29009898/110930386-017efd80-8364-11eb-902d-e82908c36310.png">|
|---|---|

## How to build `main.tex`?

Simply type 

```
make
```

or

```
make build
```

in terminal.

## How is this repo organized?


|FileName|Description|
|---|---|
|`main.tex`|Write your article here|
|`setup.tex`|Layout setting. You can customize your setting here, or put template permeable|
|`library.bib`|Reference collection|
|`fig/`|Image folder|
|`makefile`|Script for generating PDF output. Type `make` in terminal|
|`.github`|Continuous Integration with [tectonic](https://github.com/tectonic-typesetting/tectonic), a modern LaTeX compiler written in Rust|


## How to compile this file 

### Linux

- See [Gihub CI yaml](.github/workflows/ci.yml)

### MacOS

- Install fonts
     - Download [Noto Font](https://www.google.com/get/noto/#sans-hant)：
     -  Put `.otf` into FontBook (A build-in software in MacOS for organizing fonts)
     ![Screen Shot 2021-03-12 at 1.41.23 PM](https://i.imgur.com/WqanmTB.jpg)
- Install `tectonic`
  ```bash
  brew install tectonic
  ```

- 🎉 Complete installation: 
     The PDF can be built by typing 
     ```
     make
     ```
     in terminal. The automation is supported by the [makefile](makefile). Change it if you need customization.



