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
| lanjian | input-kcen | 956.7 ± 159.3 | 279.4 | 1657.3 | 1.00 |
| lanjian | input-pting | 966.6 ± 146.5 | 268.0 | 1168.0 | 1.01 ± 0.23 |
| mattcl | input-kcen | 969.9 ± 211.8 | 262.9 | 1679.2 | 1.01 ± 0.28 |
| lanjian | input-mattcl | 978.1 ± 148.7 | 258.8 | 1393.7 | 1.02 ± 0.23 |
| mattcl | input-pting | 989.4 ± 154.0 | 315.1 | 1250.7 | 1.03 ± 0.24 |
| lanjian | input-lanjian | 992.7 ± 163.1 | 214.2 | 1460.2 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1006.0 ± 173.3 | 282.2 | 1543.3 | 1.05 ± 0.25 |
| mattcl | input-lanjian | 1037.7 ± 113.5 | 503.1 | 1183.4 | 1.08 ± 0.22 |
| mattcl-py | input-pting | 14426.6 ± 582.9 | 13500.3 | 17189.7 | 15.08 ± 2.58 |
| mattcl-py | input-lanjian | 14429.9 ± 570.7 | 13459.8 | 17960.8 | 15.08 ± 2.58 |
| pting | input-pting | 14626.6 ± 527.1 | 13955.8 | 17925.3 | 15.29 ± 2.60 |
| pting | input-lanjian | 14732.5 ± 567.5 | 13909.1 | 17597.7 | 15.40 ± 2.63 |
| mattcl-py | input-mattcl | 14885.8 ± 554.8 | 14028.5 | 18426.8 | 15.56 ± 2.65 |
| mattcl-py | input-kcen | 14891.5 ± 649.9 | 13893.4 | 17664.3 | 15.57 ± 2.68 |
| pting | input-mattcl | 15133.9 ± 526.4 | 14059.5 | 18067.5 | 15.82 ± 2.69 |
| pting | input-kcen | 15140.9 ± 704.7 | 14100.6 | 18736.4 | 15.83 ± 2.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|