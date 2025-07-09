# #3: Hybrid Mapping FTL
This project implements a FTL using a hybrid mapping scheme.
It supports logical-to-physical address translation for flash memory with data blocks and a free block list.
#### `ftl_open()`
- Initializes the address mapping table and free block linked list.
#### `ftl_write(int lsn, char *sectorbuf)`
- Writes a 512B sector to flash memory using hybrid mapping.
- Allocates new blocks and performs merge if needed.
#### `ftl_read(int lsn, char *sectorbuf)`
- Reads the most recent sector data from flash by searching log and data blocks.
#### `ftl_print()`
- Prints the mapping table(`lbn`, `pbn`, `last_offset`).
