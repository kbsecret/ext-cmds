kbsecret-zxcvbn
===================

`kbsecret zxcvbn` runs the requested login records through
[zxcvbn-ruby](https://github.com/envato/zxcvbn-ruby), the Ruby port of
[Dropbox's zxcvbn](https://github.com/dropbox/zxcvbn).

Each record is given an entropy and security score, and records below the minimum entropy
and security scores (`30.0` and `2` by default, respectively) are warned about.

## Usage

```bash
$ kbsecret zxcvbn [--session <session>] [--all] [--entropy <num>] [--score <num>] <record [record ...]>
```

## Demo

[![asciicast](https://asciinema.org/a/vxH83h2jYbzGqCbtcCt4SsjtI.png)](https://asciinema.org/a/vxH83h2jYbzGqCbtcCt4SsjtI)
