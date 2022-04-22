# C - Singly linked lists


| Type/File          | Definition/Prototype                                                                   |
| ------------------ | -------------------------------------------------------------------------------------- |
| `struct list_s`    | <ul><li>`char *str`</li><li>`unsigned int len`</li><li>`struct list_s *next`</li></ul> |
| `typedef list_t`   | `struct list_s`                                                                        |
| `0-print_list.c`   | `size_t print_list(const list_t *h);`                                                  |
| `1-list_len.c`     | `size_t list_len(const list_t *h);`                                                    |
| `2-add_node.c`     | `list_t *add_node(list_t **head, const char *str);`                                    |
| `3-add_node_end.c` | `list_t *add_node_end(list_t **head, const char *str);`                                |
| `4-free_list.c`    | `void free_list(list_t *head)`                                                         |
