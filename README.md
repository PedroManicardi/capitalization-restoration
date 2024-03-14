# Capitalization restoration for apertium-es-pt 
Note: instructions expect that you are inside that repository

# How to build
```bash
./autogen.sh
make
```

## How to run
follow build instructions then run with a input text.
For example:
```bash
#supposing an input like "Brown horse"
echo '[[c:aa/aa]]^Cabalo<n>/Cabalo$ [[c:Aa/aa]]^marrón<adj>/marrón$' | apertium-restore-caps es-pt.crx.bin
```

