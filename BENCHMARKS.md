# memcache benchmarks

```bash
# goos: darwin
# goarch: amd64
# pkg: github.com/a-hilaly/memcache

BenchmarkMemCachePutPreAlloc-8           2000000               677 ns/op
BenchmarkMemCachePutPlat-8               1000000              1076 ns/op
BenchmarkMemCacheGetExist-8             10000000               121 ns/op
BenchmarkMemCacheGetNonExist-8          20000000                66.4 ns/op
BenchmarkMemCacheDeleteExist-8           3000000               435 ns/op
BenchmarkMemCacheDeleteNonExist-8       20000000               108 ns/op
BenchmarkMemStorePutPlat-8              10000000               238 ns/op
BenchmarkMemStorePutPreAlloc-8          10000000               254 ns/op
BenchmarkMemStoreGetExist-8             20000000                59.6 ns/op
BenchmarkMemStoreGetNonExist-8          20000000                58.6 ns/op
BenchmarkMemStoreDeleteExist-8          10000000               241 ns/op
BenchmarkMemStoreDeleteNonExist-8       20000000                62.7 ns/op
```