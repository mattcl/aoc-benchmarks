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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.5 | 1.03 ± 0.28 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.2 | 5.7 | 3.52 ± 0.78 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.4 | 3.52 ± 0.74 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 6.4 | 4.09 ± 0.90 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.6 | 5.4 | 4.13 ± 0.89 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 13.8 | 18.1 | 17.73 ± 3.34 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.2 | 18.2 | 17.75 ± 3.33 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.2 | 18.6 | 17.78 ± 3.36 |
| mattcl-py | input-kcen | 15.4 ± 1.7 | 14.4 | 37.4 | 18.06 ± 3.86 |
| pting | input-lanjian | 52.9 ± 1.6 | 50.9 | 59.8 | 61.91 ± 11.48 |
| pting | input-mattcl | 54.0 ± 2.0 | 51.6 | 65.3 | 63.18 ± 11.80 |
| pting | input-kcen | 54.2 ± 1.6 | 52.0 | 60.9 | 63.36 ± 11.74 |
| pting | input-pting | 56.3 ± 1.9 | 53.9 | 65.5 | 65.82 ± 12.25 |
| kcen | input-lanjian | 85.6 ± 2.2 | 82.7 | 94.2 | 100.21 ± 18.52 |
| kcen | input-kcen | 86.6 ± 2.1 | 84.5 | 92.6 | 101.33 ± 18.71 |
| kcen | input-mattcl | 87.3 ± 1.8 | 84.3 | 91.3 | 102.09 ± 18.80 |
| kcen | input-pting | 89.7 ± 1.3 | 87.7 | 94.3 | 104.91 ± 19.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|