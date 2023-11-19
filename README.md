# cyberark-eng.github.io
Collaborative space for CyberArk knowledge

## Vault upgrade comparability matrix
|   |10.10|11.2|11.3|11.4|11.5|11.7|
|---  |---|---|---|---|---|---|
|10.10| - |   |   |   |   |   |
|11.2 |   | - |   |   |   |   |
|11.3 |   |   | - |   |   |   |
|11.4 |   |   |   | - |   |   |
|11.5 |   |   |   |   | - |   |
|11.7 |   |   |   |   |   | - |
|12.0 |   |   |   |   |   |   |


## EOL Vault upgrade comparability matrix
| **9.9**     | **9.95** | **9.10** | **10.1** | **10.2** | **10.3** | **10.4** | **10.5.0** | **10.5.2** | **10.5.3** | **10.5.4** | **10.6** | **10.7** | **10.8** | **10.9** | **10.10.0** | **10.10.2** | **10.10.6** | **11.2** | **11.3** | **11.4** | **11.5.0** | **11.5.2** | **11.5.3** | **11.5.6** | **11.5.7** | **11.6** | **11.7** | **12.0** | **12.1** | **12.2.0** | **12.2.1** | **12.2.2** | **12.2.4** | **12.2.8** | **12.2.11** | **12.2.15** | **12.6.0** | **12.6.3** | **12.6.6** | **12.6.10** | **13.0** | **13.2** | **14.0** | **** |
|:-----------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:----------:|:----------:|:----------:|:----------:|:--------:|:--------:|:--------:|:--------:|:-----------:|:-----------:|:-----------:|:--------:|:--------:|:--------:|:----------:|:----------:|:----------:|:----------:|:----------:|:--------:|:--------:|:--------:|:--------:|:----------:|:----------:|:----------:|:----------:|:----------:|:-----------:|:-----------:|:----------:|:----------:|:----------:|:-----------:|:--------:|:--------:|:--------:|:----:|
| **9.9**     | -        | ✔        | ✔        | X        | X        | X        | X          | X          | X          | X          | X        | ✔        | ✔        | ✔        | X           | X           | X           | X        | X        | X        | X          | X          | X          | X          | X          | X        | X        | X        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **9.95**    |          | -        | ✔        | X        | X        | X        | X          | X          | X          | X          | X        | ✔        | ✔        | ✔        | ✔           | ✔           | X           | X        | X        | X        | X          | X          | X          | X          | X          | X        | X        | X        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **9.10**    |          |          | -        | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.1**    |          |          |          | -        | ✔        | ✔        | X          | X          | X          | X          | X        | X        | X        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | X        | X          | X          | X          | X          | X          | X        | X        | X        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.2**    |          |          |          |          | -        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | X        | X          | X          | X          | X          | X          | X        | X        | X        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.3**    |          |          |          |          |          | -        | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | X          | X          | X          | X          | X        | X        | X        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.4**    |          |          |          |          |          |          | -          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | X          | X          | X          | X        | X        | X        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.5.0**  |          |          |          |          |          |          |            | -          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.5.2**  |          |          |          |          |          |          |            |            | -          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.5.3**  |          |          |          |          |          |          |            |            |            | -          | ✔        | ✔        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.5.4**  |          |          |          |          |          |          |            |            |            |            | -        | X        | X        | X        | X           | X           | X           | X        | X        | X        | X          | X          | X          | X          | X          | X        | X        | X        | X        | ✔          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.6**    |          |          |          |          |          |          |            |            |            |            |          | -        | ✔        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | X        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.7**    |          |          |          |          |          |          |            |            |            |            |          |          | -        | ✔        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | X          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.8**    |          |          |          |          |          |          |            |            |            |            |          |          |          | -        | ✔           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.9**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          | -           | ✔           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | X          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **10.10.0** |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             | -           | ✔           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | X          | X           | X        | X        | X        | X    |   |
| **10.10.2** |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             | -           | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | X          | X           | X        | X        | X        | X    |   |
| **10.10.6** |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             | -        | X        | X        | X          | X          | X          | X          | X          | ✔        | X        | X        | X        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | X          | X           | X        | X        | X        | X    |   |
| **11.2**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          | -        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **11.3**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          | -        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **11.4**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          | -          | ✔          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **11.5.0**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            | -          | ✔          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | X        | X    |   |
| **11.5.2**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            | -          | ✔          | ✔          | ✔        | ✔        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | X        | X    |   |
| **11.5.3**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            | -          | ✔          | ✔        | X        | X        | X        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | X        | X    |   |
| **11.5.6**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            | -          | ✔        | X        | X        | X        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | X        | X    |   |
| **11.5.7**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            | -        | X        | X        | X        | X          | X          | X          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | X        | X    |   |
| **11.6**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          | -        | ✔        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | X          | X           | X        | X        | X        | X    |   |
| **11.7**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          | -        | ✔        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | X          | X           | X        | X        | X        | X    |   |
| **12.0**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          | -        | ✔          | ✔          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | X          | X           | X        | X        | X        | X    |   |
| **12.1**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          | -          | ✔          | X          | X          | X          | X           | X           | X          | X          | X          | X           | X        | X        | X        | X    |   |
| **12.2.0**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            | -          | ✔          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | ✔        |      |   |
| **12.2.1**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            | -          | ✔          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | ✔        |      |   |
| **12.2.2**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            | -          | ✔          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | ✔        |      |   |
| **12.2.4**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            | -          | ✔           | ✔           | ✔          | ✔          | ✔          | ✔           | ✔        | ✔        | ✔        |      |   |
| **12.2.8**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            | -           | ✔           | ✔          | X          | ✔          | ✔           | ✔        | X        | ✔        |      |   |
| **12.2.11** |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             | -           | ✔          | X          | X          | ✔           | ✔        | X        | ✔        |      |   |
| **12.2.15** |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             | -          | X          | X          | X           | ✔        | X        | ✔        |      |   |
| **12.6.0**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             |            | -          | ✔          | ✔           | ✔        | ✔        | ✔        |      |   |
| **12.6.3**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             |            |            | -          | ✔           | ✔        | ✔        | ✔        |      |   |
| **12.6.6**  |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             |            |            |            | -           | ✔        | ✔        | ✔        |      |   |
| **12.6.10** |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             |            |            |            |             | -        | X        | ✔        |      |   |
| **13.0**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             |            |            |            |             |          | -        | ✔        |      |   |
| **13.2**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             |            |            |            |             |          |          | -        | ✔    |   |
| **14.0**    |          |          |          |          |          |          |            |            |            |            |          |          |          |          |             |             |             |          |          |          |            |            |            |            |            |          |          |          |          |            |            |            |            |            |             |             |            |            |            |             |          |          |          | -    |
