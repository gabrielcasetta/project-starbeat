# Project: STAR BEAT!

An unofficial control center for Tongfang laptops on Linux/MacOS.

# Early Stage


This project is on an early stage. There is little feature in this program, including keyboard light controlling. If you meet problems or you have some ideas, please open an issue and tell me.

# Build & Run


The program is powered by Electron.

```shell
# install dependencies
npm install

# start development environment(macOS)
npm start
# in Linux you may need to run with `sudo`

# pack binary(macOS)
npm run pack

# pack binary(Linux)
npm run pack:linux
```

# Supported Devices


This program is designed for Hasee God-of-War models, but will theoretically work on those devices with ITE keyboard (vendor id 0x048d, device id 0xce00, ITE revision 0.02). The following are the models that are known to work:

- Z7(m)-KP7/5(G)Z
- Z7(m)-kP7/5EC

# Not Support My Device?


This program only support ITE controller with revision 0.02. If your ITE revision is 0.03, please use this CLI tool by @rodgomesc: https://github.com/rodgomesc/avell-unofficial-control-center ; if your ITE revision is 0.02 and vendor_id / product_id are correct, please open an issue to tell me.

# Other

- Powered by Electron and node-hid, written in Node.js/Javascriipt
- Materialize UI Library
- Thanks to [@rodgomesc](https://github.com/rodgomesc) for his inspiration and help
- Thanks to the testing of KP7EC by QianBiXiangYang
- Logo and project name are inspired from Poppin'Party

# License

Project: STAR BEAT! is MIT licensed.