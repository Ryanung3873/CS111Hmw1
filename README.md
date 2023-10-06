# A Kernel Seedling
Code to count number of processes

## Building
```shell
make 
sudo insmod proc_count.ko
```

## Running
```shell
cat /proc/count
```
Results: 175

## Cleaning Up
```shell
make clean
```

## Testing
```python
python -m unittest
```
TODO: ran 3 test in 2.395s?
      OK

Report which kernel release version you tested your module on
(hint: use `uname`, check for options with `man uname`).
It should match release numbers as seen on https://www.kernel.org/.

```shell
uname -r -s -v
``
TODO: Linux 5.14.8-arch1-1 #1 SMP PREEMPT Sun, 26 Sep 2021 19:36:15 +0000