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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.1 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.4 | 1.4 | 1.08 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.2 | 1.1 | 1.08 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.1 | 1.11 ± 0.26 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.6 | 3.44 ± 0.76 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.9 | 3.47 ± 0.82 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.7 | 5.7 | 4.05 ± 0.96 |
| lanjian | input-lanjian | 3.6 ± 0.5 | 2.9 | 6.3 | 4.09 ± 1.00 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.2 | 17.09 ± 3.54 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 13.9 | 18.5 | 17.15 ± 3.56 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.2 | 18.3 | 17.15 ± 3.56 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.2 | 18.4 | 17.24 ± 3.58 |
| pting | input-lanjian | 54.5 ± 2.2 | 51.6 | 66.6 | 61.28 ± 12.69 |
| pting | input-mattcl | 54.6 ± 1.4 | 52.3 | 60.6 | 61.45 ± 12.59 |
| pting | input-kcen | 54.8 ± 2.6 | 52.6 | 71.0 | 61.61 ± 12.87 |
| pting | input-pting | 56.9 ± 1.3 | 54.5 | 59.9 | 63.97 ± 13.09 |
| kcen | input-lanjian | 85.3 ± 1.2 | 82.2 | 87.5 | 95.93 ± 19.54 |
| kcen | input-mattcl | 86.6 ± 1.1 | 84.3 | 89.8 | 97.42 ± 19.84 |
| kcen | input-kcen | 87.0 ± 1.5 | 84.2 | 90.5 | 97.89 ± 19.96 |
| kcen | input-pting | 91.2 ± 2.0 | 88.0 | 95.9 | 102.57 ± 20.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|