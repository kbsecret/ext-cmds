kbsecret-audit-pass
===================

`kbsecret audit-pass` runs the requested login records through
[pwnedpasswords.com](https://pwnedpasswords.com)
(a component of [HIBP](https://haveibeenpwned.com)).

Passwords are audited with a k-anonymity scheme &mdash; only the first five characters of the
password's SHA1 digest are sent to the server, and the server responds with the suffixes of
every matching digest.

## Usage

```bash
$ kbsecret audit-pass [--session <session>] [--all] <record [record ...]>
```

## Demo

[![asciicast](https://asciinema.org/a/UxZfDTo83tc92UcheacrCLPbS.png)](https://asciinema.org/a/UxZfDTo83tc92UcheacrCLPbS)
