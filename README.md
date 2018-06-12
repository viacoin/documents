# documents
A collection of viacoin related documents

## Exchanges

### Yobtc Instructions
- [Using YoBTC.com](https://github.com/viacoin/documents/blob/master/exchanges/yobtccom.pdf)

## Whitepapers

### Viacoin Whitepaper
- [English - Regular](https://github.com/viacoin/documents/blob/master/whitepapers/Viacoin_whitepaper.pdf)
- [English - Fullcolor](https://github.com/viacoin/documents/blob/master/whitepapers/Viacoin_fullcolor_whitepaper.pdf)
- [Chinese](https://github.com/viacoin/documents/blob/master/whitepapers/translations/chinese/Viacoin_whitepaper_chinese.pdf)
- [Russian](https://github.com/viacoin/documents/blob/master/whitepapers/translations/russian/Viacoin_whitepaper_russian.pdf)
- [German](https://github.com/viacoin/documents/blob/master/whitepapers/translations/german/Viacoin_whitepaper_german.pdf)
- [Japanese](https://github.com/viacoin/documents/blob/master/whitepapers/translations/japanese/Viacoin_whitepaper_japanese.pdf)
- [Korean](https://github.com/viacoin/documents/blob/master/whitepapers/translations/korean/Viacoin_whitepaper_korean.pdf)
- [Spanish](https://github.com/viacoin/documents/blob/master/whitepapers/translations/spanish/Viacoin_whitepaper_spanish.pdf)
- [Vietnamese](https://github.com/viacoin/documents/blob/master/whitepapers/translations/vietnamese/Viacoin_whitepaper_vietnamese.pdf)

### Styx
- [English](https://github.com/viacoin/documents/blob/master/whitepapers/styx/Viacoin-Styx-Whitepaper.pdf)
- [Chinese](https://github.com/viacoin/documents/blob/master/whitepapers/styx/Viacoin-Styx-Whitepaper-Chinese.pdf)

## Compile LaTeX whitepaper on Arch linux
```$ yaourt -S texlive-core --noconfirm```

````$ yaourt -S packer --noconfirm````

````$ packer biber````

````$ pdflatex Viacoin_whitepaper.tex````

````$ biber Viacoin_whitepaper````

````$ pdflatex Viacoin_whitepaper.tex ````


