# pyinstaller-no-virus-detection
Run pyinstaller without virus detection on windows
1. Desinstalar pyinstaller python.exe -m pip uninstall pyinstaller
2. Baixar compilador(Pode ser instalando Visual Studio 2017+ ou Clang aka https://solarianprogrammer.com/2021/06/11/install-clang-windows-msys2-mingw-w64/)
3. Baixar release do pyinstaller e extrair na raiz do disco(Source Code(zip)) (https://github.com/pyinstaller/pyinstaller/releases
4. Abrir prompt ou powershell na pasta extraida/bootloader e rodar  o comando python.exe ./waf all --target-arch=64bit (ou 32bit)
5. Rodar comando na pasta pyinstaller "pip3 install ."
6. Rode o pyinstaller novamente para criar o .exe
