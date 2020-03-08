
## Global install
```
$ npm install -g https://github.com/NoctisHsu/ehentai-downloader.git
```

or

```
$ git clone https://github.com/NoctisHsu/ehentai-downloader.git
$ npm install -g ehentai-downloader
```

### completed download

```
$ eget <url> [path]

  argument
    url  target Url
    path saved path

  example
    $ eget https://e-hentai.org/g/1008611/abcdefghij/
    $ eget https://e-hentai.org/g/1008611/abcdefghij/ D:\
```

### scope download

```
$ eget <url> <path> <range>

  argument
    range {downloadScope}

  example
    $ eget https://e-hentai.org/g/1008611/abcdefghij/ . 0-2,7,8,9
    $ eget https://e-hentai.org/g/1008611/abcdefghij/ D:\ 120-140
    $ eget https://e-hentai.org/g/1008611/abcdefghij/ D:\ 20-10000
```
### set config

[config.yml](https://github.com/NoctisHsu/ehentai-downloader/blob/master/config.yml)
`eget --config`

```
Linux
  $ vi $(eget --config)

Windows PowerShell
  $ $config = eget --config
  $ explorer $config
```
