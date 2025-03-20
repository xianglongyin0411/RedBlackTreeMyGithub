```

BenchmarkDotNet v0.14.0, Windows 10 (10.0.19045.5487/22H2/2022Update)
11th Gen Intel Core i5-1145G7 2.60GHz, 1 CPU, 8 logical and 4 physical cores
.NET SDK 9.0.201
  [Host]     : .NET 9.0.3 (9.0.325.11113), X64 RyuJIT AVX-512F+CD+BW+DQ+VL+VBMI
  DefaultJob : .NET 9.0.3 (9.0.325.11113), X64 RyuJIT AVX-512F+CD+BW+DQ+VL+VBMI


```
| Method     | Mean     | Error   | StdDev  |
|----------- |---------:|--------:|--------:|
| InsertTest | 413.7 μs | 1.21 μs | 1.01 μs |
| DeleteTest | 725.4 μs | 3.84 μs | 3.21 μs |
| SearchTest | 801.1 μs | 4.36 μs | 3.86 μs |
