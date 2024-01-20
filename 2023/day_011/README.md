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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.03 ± 0.35 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.37 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.5 | 1.0 | 1.12 ± 0.34 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.0 | 4.0 | 3.72 ± 1.09 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 5.5 | 3.81 ± 1.13 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.5 | 5.9 | 4.31 ± 1.29 |
| lanjian | input-kcen | 3.4 ± 0.3 | 2.9 | 4.9 | 4.34 ± 1.27 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 14.1 | 18.1 | 19.22 ± 5.35 |
| mattcl-py | input-kcen | 15.1 ± 0.7 | 13.9 | 19.0 | 19.25 ± 5.38 |
| mattcl-py | input-pting | 15.2 ± 0.8 | 13.8 | 18.1 | 19.28 ± 5.40 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.0 | 18.3 | 19.34 ± 5.39 |
| pting | input-lanjian | 53.3 ± 0.9 | 51.9 | 56.0 | 67.77 ± 18.70 |
| pting | input-kcen | 54.0 ± 1.1 | 52.0 | 57.2 | 68.71 ± 18.98 |
| pting | input-mattcl | 54.2 ± 1.6 | 52.0 | 59.0 | 68.92 ± 19.09 |
| pting | input-pting | 57.0 ± 3.1 | 54.7 | 77.5 | 72.46 ± 20.34 |
| kcen | input-lanjian | 85.9 ± 3.0 | 83.6 | 100.7 | 109.17 ± 30.30 |
| kcen | input-mattcl | 87.0 ± 1.5 | 84.2 | 90.3 | 110.58 ± 30.52 |
| kcen | input-kcen | 87.4 ± 1.9 | 84.0 | 92.0 | 111.09 ± 30.69 |
| kcen | input-pting | 91.2 ± 1.8 | 88.3 | 96.3 | 115.90 ± 32.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|