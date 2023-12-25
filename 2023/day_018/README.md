# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 878.6 ± 180.0 | 167.2 | 1377.2 | 1.00 |
| lanjian | input-pting | 903.8 ± 179.8 | 152.8 | 1074.1 | 1.03 ± 0.29 |
| lanjian | input-lanjian | 914.1 ± 177.3 | 179.5 | 1461.2 | 1.04 ± 0.29 |
| mattcl | input-lanjian | 932.2 ± 169.5 | 227.1 | 1188.3 | 1.06 ± 0.29 |
| mattcl | input-pting | 943.7 ± 143.0 | 249.9 | 1130.0 | 1.07 ± 0.27 |
| mattcl | input-mattcl | 951.9 ± 153.0 | 187.6 | 1170.8 | 1.08 ± 0.28 |
| mattcl-py | input-lanjian | 14254.7 ± 526.1 | 13199.1 | 17202.5 | 16.23 ± 3.38 |
| mattcl-py | input-pting | 14340.1 ± 670.0 | 13280.2 | 17752.6 | 16.32 ± 3.43 |
| pting | input-pting | 14619.1 ± 630.0 | 13670.5 | 17765.6 | 16.64 ± 3.48 |
| pting | input-lanjian | 14631.7 ± 619.1 | 13620.0 | 18462.4 | 16.65 ± 3.48 |
| mattcl-py | input-mattcl | 14844.3 ± 758.1 | 13710.3 | 18622.8 | 16.90 ± 3.57 |
| pting | input-mattcl | 15047.7 ± 620.1 | 14065.7 | 17769.5 | 17.13 ± 3.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|