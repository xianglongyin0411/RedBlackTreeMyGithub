```

BenchmarkDotNet v0.14.0, Windows 10 (10.0.19045.5487/22H2/2022Update)
11th Gen Intel Core i5-1145G7 2.60GHz, 1 CPU, 8 logical and 4 physical cores
.NET SDK 9.0.201
  [Host]     : .NET 9.0.3 (9.0.325.11113), X64 RyuJIT AVX-512F+CD+BW+DQ+VL+VBMI
  DefaultJob : .NET 9.0.3 (9.0.325.11113), X64 RyuJIT AVX-512F+CD+BW+DQ+VL+VBMI


```
| Method     | Mean       | Error   | StdDev  |
|----------- |-----------:|--------:|--------:|
| InsertTest |   366.6 μs | 3.36 μs | 2.80 μs |
| DeleteTest | 1,175.6 μs | 9.74 μs | 8.14 μs |
| SearchTest |   790.1 μs | 1.89 μs | 1.77 μs |
