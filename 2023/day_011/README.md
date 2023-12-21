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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.28 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.5 | 1.06 ± 0.27 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.3 | 3.42 ± 0.80 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.4 | 3.46 ± 0.80 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.6 | 5.5 | 3.75 ± 0.91 |
| lanjian | input-kcen | 3.4 ± 0.5 | 2.7 | 5.9 | 3.95 ± 0.98 |
| mattcl-py | input-pting | 14.9 ± 0.6 | 13.9 | 18.5 | 17.12 ± 3.66 |
| mattcl-py | input-mattcl | 14.9 ± 0.6 | 13.8 | 17.5 | 17.13 ± 3.65 |
| mattcl-py | input-lanjian | 15.0 ± 0.6 | 14.1 | 18.1 | 17.24 ± 3.69 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 14.3 | 18.1 | 17.34 ± 3.69 |
| pting | input-lanjian | 53.1 ± 1.3 | 51.6 | 58.3 | 60.93 ± 12.87 |
| pting | input-mattcl | 53.7 ± 1.1 | 51.9 | 56.5 | 61.60 ± 12.97 |
| pting | input-kcen | 53.8 ± 1.4 | 52.1 | 59.8 | 61.73 ± 13.04 |
| pting | input-pting | 56.0 ± 1.2 | 54.6 | 61.4 | 64.22 ± 13.53 |
| kcen | input-lanjian | 85.0 ± 3.6 | 81.9 | 101.7 | 97.47 ± 20.84 |
| kcen | input-mattcl | 86.1 ± 1.5 | 83.3 | 89.2 | 98.70 ± 20.77 |
| kcen | input-kcen | 86.7 ± 1.5 | 84.6 | 90.8 | 99.39 ± 20.91 |
| kcen | input-pting | 90.4 ± 3.0 | 87.6 | 102.3 | 103.70 ± 22.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|