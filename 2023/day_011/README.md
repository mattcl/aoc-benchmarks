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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.3 | 1.00 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.6 | 1.2 | 1.04 ± 0.25 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.27 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.3 | 6.3 | 3.36 ± 0.81 |
| lanjian | input-mattcl | 3.2 ± 0.3 | 2.5 | 5.8 | 3.38 ± 0.78 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 2.8 | 6.7 | 3.84 ± 0.92 |
| lanjian | input-kcen | 3.7 ± 0.4 | 3.1 | 5.9 | 3.91 ± 0.90 |
| mattcl-py | input-lanjian | 15.0 ± 0.3 | 14.1 | 16.4 | 15.83 ± 3.33 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 13.8 | 18.4 | 15.88 ± 3.38 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.3 | 18.5 | 15.91 ± 3.37 |
| mattcl-py | input-kcen | 15.2 ± 0.7 | 14.2 | 18.3 | 16.07 ± 3.43 |
| pting | input-lanjian | 53.5 ± 1.3 | 51.6 | 58.2 | 56.44 ± 11.87 |
| pting | input-mattcl | 54.0 ± 1.3 | 52.4 | 57.6 | 56.97 ± 11.98 |
| pting | input-kcen | 54.6 ± 1.8 | 51.8 | 60.0 | 57.50 ± 12.17 |
| pting | input-pting | 56.8 ± 1.5 | 55.1 | 61.7 | 59.89 ± 12.61 |
| kcen | input-lanjian | 84.7 ± 1.4 | 82.7 | 87.9 | 89.33 ± 18.72 |
| kcen | input-kcen | 85.7 ± 1.5 | 83.6 | 90.5 | 90.32 ± 18.94 |
| kcen | input-mattcl | 86.5 ± 2.5 | 83.8 | 97.3 | 91.21 ± 19.25 |
| kcen | input-pting | 89.6 ± 1.7 | 86.5 | 93.6 | 94.44 ± 19.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|