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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.4 | 1.07 ± 0.32 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 1.9 | 4.0 | 3.54 ± 0.94 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 3.7 | 3.63 ± 0.92 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.5 | 4.6 | 3.93 ± 1.05 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.5 | 5.9 | 4.12 ± 1.13 |
| mattcl-py | input-pting | 15.0 ± 0.6 | 13.9 | 17.6 | 18.12 ± 4.47 |
| mattcl-py | input-lanjian | 15.0 ± 0.6 | 13.9 | 18.2 | 18.21 ± 4.49 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 14.2 | 18.2 | 18.21 ± 4.48 |
| mattcl-py | input-kcen | 15.1 ± 0.5 | 14.1 | 17.8 | 18.28 ± 4.49 |
| pting | input-lanjian | 52.8 ± 1.4 | 51.0 | 57.1 | 63.97 ± 15.66 |
| pting | input-kcen | 53.3 ± 1.3 | 51.5 | 58.1 | 64.52 ± 15.78 |
| pting | input-mattcl | 53.3 ± 1.1 | 51.7 | 57.8 | 64.55 ± 15.77 |
| pting | input-pting | 56.5 ± 2.0 | 54.2 | 63.0 | 68.46 ± 16.84 |
| kcen | input-lanjian | 85.1 ± 1.3 | 82.4 | 87.6 | 103.11 ± 25.15 |
| kcen | input-kcen | 86.5 ± 1.8 | 83.6 | 92.4 | 104.76 ± 25.60 |
| kcen | input-mattcl | 86.9 ± 2.3 | 84.9 | 99.0 | 105.28 ± 25.79 |
| kcen | input-pting | 90.4 ± 1.6 | 88.0 | 94.3 | 109.50 ± 26.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|