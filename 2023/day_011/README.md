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
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.7 | 1.04 ± 0.26 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.3 | 1.2 | 1.07 ± 0.23 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.4 | 3.21 ± 0.62 |
| lanjian | input-pting | 3.2 ± 0.5 | 2.2 | 6.0 | 3.36 ± 0.79 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 6.2 | 3.69 ± 0.79 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.8 | 6.1 | 3.76 ± 0.75 |
| mattcl-py | input-pting | 15.1 ± 0.5 | 13.9 | 18.3 | 16.00 ± 2.82 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 13.9 | 18.4 | 16.11 ± 2.87 |
| mattcl-py | input-lanjian | 15.3 ± 0.7 | 14.2 | 18.6 | 16.17 ± 2.90 |
| mattcl-py | input-kcen | 15.3 ± 0.5 | 14.3 | 18.3 | 16.19 ± 2.86 |
| pting | input-mattcl | 57.3 ± 1.1 | 55.6 | 60.0 | 60.55 ± 10.53 |
| pting | input-lanjian | 57.7 ± 1.7 | 55.3 | 65.2 | 60.98 ± 10.69 |
| pting | input-kcen | 57.8 ± 2.5 | 55.8 | 73.7 | 61.04 ± 10.87 |
| pting | input-pting | 60.3 ± 1.3 | 58.1 | 63.6 | 63.74 ± 11.12 |
| kcen | input-lanjian | 90.1 ± 1.4 | 88.0 | 94.2 | 95.21 ± 16.53 |
| kcen | input-mattcl | 91.9 ± 1.2 | 89.9 | 95.1 | 97.11 ± 16.84 |
| kcen | input-kcen | 92.6 ± 2.3 | 89.9 | 101.5 | 97.86 ± 17.11 |
| kcen | input-pting | 96.1 ± 1.8 | 92.8 | 102.6 | 101.55 ± 17.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|