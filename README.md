# AVELL FOX 5 BS CONTROLADOR DO TECLADO PARA LINUX OU MACOS

Um projeto não oficial, para controlar o teclado no Linux ou MacOS.

Este projeto visa apenas controlar a luz e cores do teclado do meu AVELL FOX 5 BS mas caso o seu modelo tenha o teclado:
ITE keyboard (vendor id 0x048d, device id 0xce00, ITE revision 0.02) há grandes chances de funcionar para o seu também.

Modelos compatíveis:
- Avell FOX 5 BS
- TongFang GI5CN4E
- Z7(m)-KP7/5(G)Z
- Z7(m)-kP7/5EC

Como compilar & Executar

Este programa é feito com Electron.
```shell
# instale as dependências
npm install

# execute o ambiente de desenvolvimento
npm start

# (Linux) compilar
npm run pack:linux

# (macOS) compilar
npm run pack

#OBS: Talvez no linux você precise executar como sudo
```
#Não suporta seu aparelho?
Caso seu teclado seja do modelo ITE revision is 0.03 confira o projeto do @rodgomesc: https://github.com/rodgomesc/avell-unofficial-control-center.

#Observações
Agradecimentos ao @kirainmoe: https://github.com/kirainmoe/project-starbeat
Desenvolvido com Electron e node-hid, Node.js/Javascriipt e Materialize UI Library
Licença:MIT