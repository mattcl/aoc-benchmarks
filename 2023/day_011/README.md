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
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.28 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.3 | 6.0 | 3.49 ± 0.85 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 5.7 | 3.53 ± 0.85 |
| lanjian | input-lanjian | 3.7 ± 0.5 | 2.8 | 6.5 | 4.21 ± 1.03 |
| lanjian | input-kcen | 3.8 ± 0.5 | 3.0 | 7.3 | 4.29 ± 1.06 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 14.0 | 17.9 | 17.09 ± 3.63 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.2 | 18.1 | 17.14 ± 3.64 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 13.9 | 17.7 | 17.21 ± 3.68 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.4 | 18.3 | 17.35 ± 3.70 |
| pting | input-lanjian | 53.3 ± 1.4 | 51.3 | 58.5 | 60.30 ± 12.70 |
| pting | input-kcen | 53.6 ± 1.1 | 52.0 | 56.6 | 60.61 ± 12.73 |
| pting | input-mattcl | 53.8 ± 1.2 | 51.8 | 57.5 | 60.85 ± 12.80 |
| pting | input-pting | 56.3 ± 1.5 | 54.7 | 61.7 | 63.66 ± 13.43 |
| kcen | input-lanjian | 84.7 ± 1.9 | 82.1 | 92.1 | 95.83 ± 20.15 |
| kcen | input-kcen | 86.1 ± 1.2 | 83.8 | 89.5 | 97.33 ± 20.40 |
| kcen | input-mattcl | 86.4 ± 1.3 | 84.2 | 89.6 | 97.70 ± 20.49 |
| kcen | input-pting | 90.2 ± 1.9 | 86.9 | 97.0 | 102.04 ± 21.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|