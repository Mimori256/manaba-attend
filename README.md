# manaba-attend

[Manaba の出席カード](https://atmnb.tsukuba.ac.jp/attend/tsukuba)の提出を自動化するプログラム。

Program automating to send your attendance on Manaba.

[<img alt="Demo video" width="400" src="https://j.gifs.com/Xo5Y38.gif">](https://youtu.be/9ZQMev_WQeE)

## Requirement

- Python3
- Google Chrome
- HomeBrew

## Installation

```shell
$ brew install chromedriver
$ cd manaba-attend/
$ python3 -m venv env
$ source env/bin/activate
$ # . env/bin/activate.fish (if you use fish shell 🐟)
$ pip install -r requirements.txt
```

## Usage

```shell
$ python main.py 1234567
```
