# NuxiiGit

NuxiiGit contains the source code to "Kat," a command-line application that periodically produces [open-source projects](https://github.com/NuxiiGit?tab=repositories) and [art works](https://katsaii.newgrounds.com/). 

## Examples

Creating a canonical instance of Kat in Haskell

```hs
{-# LANGUAGE TypeOperators #-}

-- |Represents instances of Kat.
data (🙀)
    = Katsaii
    | Nuxii
    deriving (Eq, Show) 

main = putStrLn $ let katsaii = show Katsaii
                      nuxii   = show Nuxii
                      in "Kat is either " ++ katsaii ++ " or " ++ nuxii
```

## Features

Kat also offers freelancing and collaboration options using the `-f` parameter.
