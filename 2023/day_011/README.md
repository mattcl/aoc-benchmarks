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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.4 | 1.1 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.23 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.4 | 1.1 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.4 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.0 | 5.2 | 3.31 ± 0.67 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.8 | 3.35 ± 0.66 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.7 | 6.6 | 3.76 ± 0.79 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.7 | 5.9 | 3.76 ± 0.71 |
| mattcl-py | input-pting | 15.2 ± 0.5 | 14.4 | 17.7 | 16.38 ± 2.73 |
| mattcl-py | input-mattcl | 15.2 ± 0.5 | 14.3 | 18.5 | 16.43 ± 2.75 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.3 | 18.6 | 16.54 ± 2.78 |
| mattcl-py | input-kcen | 15.6 ± 0.7 | 14.6 | 19.1 | 16.81 ± 2.86 |
| pting | input-mattcl | 53.4 ± 1.1 | 51.5 | 57.2 | 57.58 ± 9.50 |
| pting | input-lanjian | 53.5 ± 4.1 | 51.0 | 80.2 | 57.69 ± 10.42 |
| pting | input-kcen | 53.6 ± 1.8 | 51.6 | 61.3 | 57.84 ± 9.66 |
| pting | input-pting | 55.9 ± 1.9 | 53.8 | 65.1 | 60.31 ± 10.09 |
| kcen | input-lanjian | 85.6 ± 2.0 | 82.8 | 91.8 | 92.27 ± 15.26 |
| kcen | input-mattcl | 86.4 ± 1.6 | 84.2 | 90.5 | 93.18 ± 15.36 |
| kcen | input-kcen | 86.8 ± 1.4 | 83.8 | 90.4 | 93.61 ± 15.40 |
| kcen | input-pting | 90.6 ± 1.2 | 87.5 | 92.7 | 97.66 ± 16.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|