# Kiitian-Finder in C

Original [kiitian-finder](https://github.com/erucix/kiitian-finder) re-written in pure C with `lib-curl`. 

## Compilation Steps:
Make sure to install `libcurl` to properly run the executable.
```bash
sudo apt install libcurl4-openssl-dev gcc
git clone https://github.com/erucix/kiitian-finder-in-C.git
cd kiitian-finder-in-C
gcc kiit.c -lcurl -o kiit.bin
./kiit.bin
```
Put required roll numbers in `input.txt` each in new-line and the corresponding details will be saved in `output.txt` in CSV format.
