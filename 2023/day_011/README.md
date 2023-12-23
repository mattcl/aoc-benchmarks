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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.2 | 1.1 | 1.02 ± 0.27 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.27 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.0 | 5.5 | 3.43 ± 0.82 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 3.5 | 3.44 ± 0.74 |
| lanjian | input-lanjian | 3.4 ± 0.5 | 2.6 | 5.6 | 3.93 ± 0.97 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.6 | 5.8 | 3.98 ± 0.92 |
| mattcl-py | input-lanjian | 15.1 ± 0.7 | 13.9 | 18.4 | 17.54 ± 3.67 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 14.0 | 18.4 | 17.58 ± 3.68 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.3 | 18.3 | 17.59 ± 3.66 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.0 | 18.9 | 17.69 ± 3.68 |
| pting | input-lanjian | 52.7 ± 1.2 | 50.9 | 55.8 | 61.02 ± 12.55 |
| pting | input-mattcl | 53.0 ± 1.0 | 51.1 | 55.5 | 61.34 ± 12.59 |
| pting | input-kcen | 53.6 ± 2.4 | 51.3 | 65.9 | 62.08 ± 13.00 |
| pting | input-pting | 56.0 ± 1.1 | 53.5 | 58.7 | 64.89 ± 13.33 |
| kcen | input-lanjian | 87.9 ± 1.3 | 86.0 | 91.2 | 101.83 ± 20.87 |
| kcen | input-kcen | 89.7 ± 1.1 | 87.3 | 91.8 | 103.85 ± 21.27 |
| kcen | input-mattcl | 90.3 ± 1.5 | 87.6 | 95.4 | 104.57 ± 21.45 |
| kcen | input-pting | 94.1 ± 1.7 | 90.7 | 98.6 | 108.99 ± 22.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|