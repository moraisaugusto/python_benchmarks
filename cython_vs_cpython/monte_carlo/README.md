# Cython

To generate the Cython C library run the following command:

```bash
python setup.py build_ext --inplace
```


## Results

```bash
$ repeat 10 time python test_cython.py
3.14166104
python test_cython.py  11.41s user 0.02s system 100% cpu 11.403 total
3.14146104
python test_cython.py  11.03s user 0.01s system 100% cpu 11.020 total
3.1415116
python test_cython.py  11.22s user 0.02s system 100% cpu 11.212 total
3.1418764
python test_cython.py  11.29s user 0.01s system 100% cpu 11.277 total
3.14196384
python test_cython.py  11.17s user 0.04s system 100% cpu 11.182 total
3.14126688
python test_cython.py  11.08s user 0.02s system 100% cpu 11.069 total
3.14153696
python test_cython.py  11.69s user 0.03s system 100% cpu 11.701 total
3.14160264
python test_cython.py  11.39s user 0.03s system 100% cpu 11.392 total
3.14145632
python test_cython.py  11.92s user 0.04s system 100% cpu 11.944 total
3.14194592
python test_cython.py  11.80s user 0.02s system 100% cpu 11.804 total
```

**mean**: 11.4000


```bash
 repeat 10 time python test_cpython.py
 3.14183208
 python test_cpython.py  16.84s user 0.02s system 100% cpu 16.841 total
 3.14158352
 python test_cpython.py  16.77s user 0.02s system 100% cpu 16.769 total
 3.1417584
 python test_cpython.py  17.06s user 0.03s system 100% cpu 17.073 total
 3.14165928
 python test_cpython.py  16.26s user 0.02s system 100% cpu 16.255 total
 3.14170176
 python test_cpython.py  16.54s user 0.01s system 100% cpu 16.528 total
 3.14171152
 python test_cpython.py  16.33s user 0.03s system 100% cpu 16.336 total
 3.14151392
 python test_cpython.py  16.95s user 0.04s system 100% cpu 16.967 total
 3.14147584
 python test_cpython.py  16.52s user 0.02s system 100% cpu 16.522 total
 3.14161256
 python test_cpython.py  16.61s user 0.01s system 100% cpu 16.597 total
 3.14144344
 python test_cpython.py  15.88s user 0.02s system 100% cpu 15.885 total
```

**mean**: 16.5760
