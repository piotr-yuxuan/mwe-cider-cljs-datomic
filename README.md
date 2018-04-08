# mwe-figwheel-cljs-datomic

Minimal working example of an unexpected behaviour with happens on a
fresh figwheel project when I add datomic-free as a dependency.

## Overview

I intended to give re-posh, figwheel, and re-frame a try but I stumble
upon this exception. I'm not sure it's a bug, perhaps I missed
additional configuration.

However, [datomic documentation](https://docs.datomic.com/on-prem/getting-started/connect-to-a-database.html#leiningen) looks quite straightforward.

## Setup

To reproduce the unexpected behaviour, run

``` shell
lein figwheel
```
