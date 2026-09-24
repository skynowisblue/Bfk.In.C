# Bfk.In.C 🐣

A tiny Brainfuck interpreter written in C.

## 📊 Size

- **Source code:** 600 bytes
- **Binary:** ~15 KB (Windows, with `-Os`)
- **Dependencies:** Only `<stdio.h>`

## ✨ Features

- ✅ All 8 Brainfuck commands (`> < + - . , [ ]`)
- ✅ File input support
- ✅ Only uses `stdio.h`
- ✅ Extremely small source

## 🛠️ Build

```bash
gcc -Os bfk.c -o bfk.exe
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
