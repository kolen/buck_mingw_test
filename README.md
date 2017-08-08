``buck build //:foo``

Also try to uncomment following lines in `.buckconfig`:

``` ini
  ;; archiver_platform = WINDOWS
  ;; linker_platform = WINDOWS
```

Works with default clang on Mac OS (if everything in `.buckconfig` is
uncommented).
