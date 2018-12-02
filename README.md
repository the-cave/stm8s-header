# STM8S header

## What is it?

It is a collection of STM8S/STM8AF header declaration officially offered by STMicroelectronics but with some patch to enable SDCC support.

## Currently supported targets

* STM8S208
* STM8S207
* STM8S007
* STM8AF52Ax
* STM8AF62Ax
* STM8S105
* STM8S005
* STM8AF626x
* STM8AF622x
* STM8S103
* STM8S003
* STM8S903
* STM8S001

## Why a handful of STM8 SDCC example found over the internet did not use the official headers?

Historically, the library like what you found here is not possible per ST licensing terms. Back then, the patch to support more compilers apart from what ST declared would violate the license. At some point, ST released their libraries in more permissive licensing terms. Now, this is possible, but with some restrictions, please see `LICENSE.md` for more info.

## Aim of this repository

* Keep the changes least intrusive to the official header files
* Ease of library usage and dependency management via git submodules

## Contributing

People just change and patch whatever works for them. I also patch the header files just to make them works on my use cases. The patches are far from perfect but they will keep progressing relying on contributions. Pull requests are very welcome and discussable.

## License

All code in this repository is subjected to the [MCD-ST Liberty SW License Agreement V2](https://www.st.com/software_license_agreement_liberty_v2). Redistribution inside a project with a different license does not override the license on the header files in this repository.
