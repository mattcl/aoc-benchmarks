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
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.6 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 2.0 | 1.01 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.6 | 1.5 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 5.9 | 2.88 ± 0.53 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.6 | 5.6 | 2.89 ± 0.50 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.4 | 4.6 | 3.04 ± 0.61 |
| lanjian | input-kcen | 3.4 ± 0.3 | 2.9 | 4.9 | 3.26 ± 0.58 |
| pting | input-lanjian | 52.1 ± 1.5 | 50.2 | 58.7 | 49.95 ± 7.84 |
| pting | input-kcen | 52.8 ± 1.2 | 50.9 | 56.0 | 50.57 ± 7.89 |
| pting | input-mattcl | 53.0 ± 1.3 | 51.1 | 58.2 | 50.80 ± 7.93 |
| mattcl-py | input-kcen | 54.9 ± 1.4 | 53.3 | 60.8 | 52.57 ± 8.21 |
| mattcl-py | input-lanjian | 54.9 ± 1.9 | 52.8 | 64.5 | 52.63 ± 8.32 |
| pting | input-pting | 55.0 ± 1.1 | 53.8 | 58.3 | 52.71 ± 8.19 |
| mattcl-py | input-mattcl | 56.3 ± 2.0 | 53.6 | 65.3 | 53.98 ± 8.54 |
| mattcl-py | input-pting | 58.1 ± 1.4 | 56.0 | 62.7 | 55.65 ± 8.68 |
| kcen | input-lanjian | 84.9 ± 2.2 | 82.1 | 91.4 | 81.32 ± 12.72 |
| kcen | input-kcen | 85.0 ± 3.0 | 82.1 | 100.1 | 81.46 ± 12.88 |
| kcen | input-mattcl | 85.9 ± 2.1 | 83.1 | 92.6 | 82.30 ± 12.85 |
| kcen | input-pting | 89.0 ± 1.8 | 86.3 | 95.7 | 85.28 ± 13.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|