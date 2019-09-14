# STM32SystemWorkbench
### Install System Workbench on Mac OS X

1. Go to [https://www.st.com/en/development-tools/sw4stm32.html](https://www.st.com/en/development-tools/sw4stm32.html)
2. You'll need an account to access the download page. *(suggestion: use gmail to create an account)*
3. Go to "download area" and download the LATEST version for Mac OS X named "install_sw4stm32_macos_64bits-latest.run"
4. Open Terminal, go to the directory where the file locates at, and enter command to set the file permission: 
``` bash
chmod 777 install_sw4stm32_macos_64bits-latest.run
```
5. Run the executable (During installation process, you may get asked to enter your password to continue installation process)
```bash
./install_sw4stm32_macos_64bits-latest.run
```


### Install STM32CubeMX Eclipse plug in
1. Go to [https://www.st.com/en/development-tools/stsw-stm32095.html](https://www.st.com/en/development-tools/stsw-stm32095.html) and download the file (in "Get Software" section)
2. Open System Workbench and go to *Help* -> *Install New Software...*
3. Click *Add...* -> *Archive...* and then select the zip file you just downloaded
4. For the name section, a suggested name is STM32CubeMX
5. Click "Next" and finish the rest of the installation process
