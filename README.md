# Install windows app on MacOS using Wine (eg. emu8086)


Run windows software in MacOS:

1. Install brew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2. Install wine

brew install --cask --no-quarantine wine-stable 

3. Install emu8086 or other windows exe program (run this command from the exe directory or mention the program path)

wine wine-setup.exe

4. Open emu8086 or other windows exe program (run this command from the exe directory or mention the program path)

WINEPREFIX="/Users/gaminglab/.wine" wine c:\\\\emu8086\\\\emu8086.exe 
