# install-gcc-arm-none-eabi
GitHub Action to install the `GNU Arm Embedded Toolchain` into an Ubuntu environment.

## Usage
Using it is very simple, just add the following line to your job:

```yaml
jobs:
  build:

    runs-on: ubuntu-20.04

    steps:
    - uses: actions/checkout@v2
    - name: Install GNU Arm Embedded Toolchain          # <---- ADD THIS LINE
      uses: marvinschopf/install-gcc-arm-none-eabi@main # <---- ADD THIS LINE
```

## License
**MIT License**  
Copyright (c) 2021 Marvin Schopf  

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
