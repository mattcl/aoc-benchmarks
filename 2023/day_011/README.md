# Day 11 benchmarks

[link to problem](https://adventofcode.com/2023/day/11)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 11)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.04 ± 0.28 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.1 | 1.05 ± 0.27 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.3 | 5.9 | 3.60 ± 0.86 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 5.7 | 3.68 ± 0.90 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.9 | 6.7 | 4.17 ± 0.99 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.8 | 7.4 | 4.17 ± 0.98 |
| mattcl-py | input-pting | 14.8 ± 0.5 | 13.8 | 18.5 | 17.37 ± 3.60 |
| mattcl-py | input-lanjian | 14.8 ± 0.4 | 13.9 | 17.6 | 17.43 ± 3.60 |
| mattcl-py | input-mattcl | 14.9 ± 0.7 | 13.9 | 19.3 | 17.52 ± 3.68 |
| mattcl-py | input-kcen | 15.0 ± 0.6 | 13.9 | 18.3 | 17.67 ± 3.69 |
| pting | input-lanjian | 53.2 ± 1.2 | 51.5 | 56.8 | 62.55 ± 12.87 |
| pting | input-mattcl | 53.9 ± 1.8 | 51.5 | 61.0 | 63.32 ± 13.14 |
| pting | input-kcen | 55.0 ± 5.5 | 51.9 | 93.1 | 64.59 ± 14.72 |
| pting | input-pting | 56.2 ± 2.0 | 54.2 | 64.8 | 66.09 ± 13.74 |
| kcen | input-lanjian | 85.6 ± 1.9 | 83.5 | 93.7 | 100.65 ± 20.71 |
| kcen | input-mattcl | 86.5 ± 1.3 | 84.3 | 89.7 | 101.69 ± 20.86 |
| kcen | input-kcen | 87.9 ± 7.0 | 84.2 | 126.7 | 103.33 ± 22.68 |
| kcen | input-pting | 90.6 ± 1.8 | 87.7 | 94.0 | 106.42 ± 21.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|