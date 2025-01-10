# wal-lsm-tree-sstable-summary

![lsm-tree](assets/images/lsm.jpg)

## Hash Index
### Pros:
  + O(1) Read
### Cons:
  + Hard to manage hashes in disk, it must be managed in memory
  + More data means more memory and more cost
  + Memory is not durable in case of shutdown or crash
  + Cost of range queries is O(n)

## B-Tree
## Red Black Tree
## WAL
## LSM Tree
## SSTable
