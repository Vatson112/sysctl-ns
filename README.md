# sysctl-ns

A curated list of sysctl settings for containers.

## net

### core

| parameter     |  namespaced | comment                        |
|---|---|---|
| rmem_default  | false       |                                |
| rmem_max      | false       |                                |
| wmem_default  | false       |                                |
| wmem_max      | false       |                                |
| somaxconn     | true        | Value copy from kernel default value.(128 befor 5.14, 4096 after |
| netdev_max_backlog   | false           |                                |
|               |             |                                |
|               |             |                                |
|               |             |                                |

### ipv4

| parameter     |  namespaced | comment                        |
|---|---|---|
| tcp_syncookies  | true       |                                |
|               |             |                                |
|               |             |                                |
|               |             |                                |
|               |             |                                |
