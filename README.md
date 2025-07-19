# Bashのエイリアス集

```sh
mkdir ~/.bash_aliases.d

DIRECTORY=<チェックアウト先ディレクトリー パス>
for FILE_NAME in xclip ghq vim ssh apt git docker; do ln -fs "${DIRECTORY}/${FILE_NAME}" ~/.bash_aliases.d/$FILE_NAME ; done
```

`.bash_aliases`

```sh
. ~/.bash_aliases.d/*
```
