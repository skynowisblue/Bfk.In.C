# Bfk.In.C 🐣

A tiny Bfk interpreter written in C.

## 📊 Size

- **Source code:** 600 bytes
- **Binary:** ~15360 bytes(If Compiled with `-Os` And `-s`) (Windows, with `-Os` And `-s`)
- **Dependencies:** Only `<stdio.h>`

## ✨ Features

- ✅ All 8 Bfk commands (`> < + - . , [ ]`)
- ✅ File input support
- ✅ Only uses `stdio.h`
- ✅ Extremely small source

## 🛠️ Build

```PowerShell/Cmd
gcc -Os -s bfk.c -o bfk.exe
```

## 🚀 Usage

```bash
./bfk.exe program.bfk
```

## 📝 Example

Save this as `hello.bfk`:

```
++++++++++[>+++++++>++++++++++>+++>+<<<<-]>++.>+.+++++++..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.>.
```

Run it:

```bash
./bfk.exe hello.bfk
```

Output:

```
Hello World!
```

## 📜 License

Licensed under **GPL-3.0**. See [LICENSE](LICENSE) for details.

## 👤 Author

Made by [@skynowisblue](https://github.com/skynowisblue)
