# install-windows-app-on-macos-using-wine-ex-emu8086-
install-windows-app-on-macos-using-wine (ex-emu8086)


Run windows software in MacOS:

1. Install brew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2. Install wine

brew install --cask --no-quarantine wine-stable 

3. Install emu8086 or other windows exe program (run this command from the exe directory or mention the program path)

wine wine-setup.exe

4. Open emu8086 or other windows exe program (run this command from the exe directory or mention the program path)

WINEPREFIX="/Users/gaminglab/.wine" wine c:\\\\emu8086\\\\emu8086.exe 

5. Emu8086 license key

[source: https://gist.github.com/joao-neves95/8cb68b4904226efc28f5f1fb2ce65f33]
