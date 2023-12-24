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
| mattcl | input-mattcl | 0.9 ± 3.6 | 0.1 | 50.8 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.3 | 1.5 | 1.04 ± 3.98 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.2 | 1.1 | 1.05 ± 4.02 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.4 | 1.07 ± 4.11 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 4.8 | 3.32 ± 12.71 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.1 | 5.6 | 3.32 ± 12.71 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.9 | 5.4 | 3.85 ± 14.73 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.7 | 5.2 | 3.91 ± 14.94 |
| mattcl-py | input-pting | 15.2 ± 0.5 | 14.0 | 17.6 | 16.34 ± 62.45 |
| mattcl-py | input-mattcl | 15.3 ± 0.7 | 14.2 | 18.3 | 16.44 ± 62.86 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.1 | 18.3 | 16.46 ± 62.90 |
| mattcl-py | input-lanjian | 15.4 ± 0.8 | 14.3 | 18.6 | 16.52 ± 63.17 |
| pting | input-lanjian | 53.4 ± 1.6 | 51.7 | 59.5 | 57.34 ± 219.20 |
| pting | input-mattcl | 53.4 ± 1.3 | 51.5 | 58.6 | 57.35 ± 219.22 |
| pting | input-kcen | 53.8 ± 1.3 | 52.2 | 58.5 | 57.76 ± 220.78 |
| pting | input-pting | 55.9 ± 1.4 | 54.2 | 62.6 | 60.02 ± 229.41 |
| kcen | input-lanjian | 89.0 ± 3.2 | 86.5 | 105.5 | 95.51 ± 365.10 |
| kcen | input-mattcl | 90.7 ± 1.2 | 88.7 | 93.9 | 97.39 ± 372.28 |
| kcen | input-kcen | 90.9 ± 1.3 | 89.3 | 95.8 | 97.53 ± 372.82 |
| kcen | input-pting | 94.9 ± 3.6 | 91.4 | 111.7 | 101.84 ± 389.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|