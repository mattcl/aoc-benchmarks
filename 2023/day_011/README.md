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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.3 | 1.4 | 1.01 ± 0.27 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.30 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.0 | 5.8 | 3.61 ± 0.85 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.5 | 3.63 ± 0.82 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 4.9 | 4.03 ± 0.98 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.7 | 5.9 | 4.13 ± 0.96 |
| mattcl-py | input-mattcl | 14.9 ± 0.5 | 13.9 | 17.4 | 17.91 ± 3.78 |
| mattcl-py | input-lanjian | 14.9 ± 0.7 | 13.9 | 18.0 | 17.96 ± 3.83 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 13.9 | 18.1 | 17.97 ± 3.82 |
| mattcl-py | input-kcen | 15.0 ± 0.5 | 14.0 | 17.8 | 17.99 ± 3.81 |
| pting | input-lanjian | 52.6 ± 1.2 | 50.6 | 56.2 | 63.18 ± 13.25 |
| pting | input-kcen | 53.1 ± 1.2 | 51.5 | 56.5 | 63.89 ± 13.41 |
| pting | input-mattcl | 53.9 ± 5.0 | 51.0 | 89.3 | 64.76 ± 14.78 |
| pting | input-pting | 55.9 ± 1.8 | 53.7 | 63.7 | 67.16 ± 14.17 |
| kcen | input-lanjian | 84.9 ± 2.7 | 82.2 | 98.8 | 102.09 ± 21.53 |
| kcen | input-mattcl | 87.4 ± 6.6 | 83.8 | 124.4 | 105.06 ± 23.30 |
| kcen | input-kcen | 87.5 ± 7.8 | 83.0 | 131.5 | 105.23 ± 23.89 |
| kcen | input-pting | 90.0 ± 2.5 | 87.2 | 100.2 | 108.20 ± 22.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|