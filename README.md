A simple gn+ninja+clang demo on windows.

1. The `gn.exe` file is downloaded from https://chrome-infra-packages.appspot.com/dl/gn/gn/windows-amd64/+/latest
2. The `ninja.exe` file is downloaded from https://github.com/ninja-build/ninja/releases
3. Install clang, and make sure clang.exe is in the path env variable.
4. `gn gen out/helloworld`
5. `ninja -C out/hellworld`

## Credits
https://www.jiangkang.tech/2020/05/29/c/gn-gou-jian-c-xiang-mu-zhi-helloworld/