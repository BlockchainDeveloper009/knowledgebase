# knowledgebase
urls, links, 

## government links

[U.S. Bureau of labor statistics](https://www.bls.gov/web/metro/laummtrk.htm)

## economy

## learning
[Blockchain Reference links](https://github.com/BlockchainDeveloper009/knowledgebase/blob/devbr/blockchain_reference_links)
## tools

## home improvement

#### Plumbing
   --Electrical
#### Wood work
>>> [Load-bearing wall - Rotted Studd wall - Replace bottom plate - bottom plate of a wall - Non loadbearing wall - bottom plate installation]()
#### Painting
#### Drone
#### Inspection
####  Gardening
####  Masonary
 
```bash
|-- top
|-- c12
|    |---c13
|    |---c14
|-- c2
```

$ ./tree-md .
# Project tree

.
 * [tree-md](./tree-md)
 * [dir2](./dir2)
   * [file21.ext](./dir2/file21.ext)
   * [file22.ext](./dir2/file22.ext)
   * [file23.ext](./dir2/file23.ext)
 * [dir1](./dir1)
   * [file11.ext](./dir1/file11.ext)
   * [file12.ext](./dir1/file12.ext)
 * [file_in_root.ext](./file_in_root.ext)
 * [README.md](./README.md)
 * [dir3](./dir3)

```bash
#!/bin/bash

#File: tree-md

tree=$(tree -tf --noreport -I '*~' --charset ascii $1 |
       sed -e 's/| \+/  /g' -e 's/[|`]-\+/ */g' -e 's:\(* \)\(\(.*/\)\([^/]\+\)\):\1[\4](\2):g')

printf "# Project tree\n\n${tree}"
```

```
$ tree
.
├── dir1
│   ├── file11.ext
│   └── file12.ext
├── dir2
│   ├── file21.ext
│   ├── file22.ext
│   └── file23.ext
├── dir3
├── file_in_root.ext
└── README.md$ tree
.

```
├── ## Drone
│   ├── #### 1Drone
│   └── file12.ext
├── ####  Masonary
│   ├── #### Painting
│   ├── #### Inspection
│   └── ####  Gardening
├── dir3
├── file_in_root.ext
└── README.md




