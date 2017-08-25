## Install Nand2tetris Software Suite for Mac user

The page is written in English, so I write in Japanese for Japanese

## Install Java

javaがインストールされているか確かめる

```bash
$ java -version
java version "1.8.0_121"
Java(TM) SE Runtime Environment (build 1.8.0_121-b13)
Java HotSpot(TM) 64-Bit Server VM (build 25.121-b13, mixed mode)
```

反応しなかったらjavaをインストールしましょう

## install Nand2tetris Software

[このページ](http://nand2tetris.org/software.php)の__Download the Nand2tetris Software

一応、このプロジェクトの./tools(本ディレクトリ)にダウンロードしてきた
パッケージを置いてあります

ダウンロード後は実行ファイルに実行権限を与えておきましょう

```
$ cd nand2tetris
$ chmod -R 755 tools/
```

## How to use

下記ファイルを実行するとソフトウェアが立ち上がる

```
$ nand2tetris/tools/HardwareSimulator.sh
```

ほかのツールを立ち上げるには下記のファイルを実行する

| Tool               | Command              |
|:-------------------|:---------------------|
| Hardware simulator | HardwareSimulator.sh |
| CPU Emulator       | CPUEmulator.sh       |
| Assembler          | Assembler.sh         |
| VM Emulator        | VMEmulator.sh        |
| Jack Compiler      | JackCompiler.sh      |
