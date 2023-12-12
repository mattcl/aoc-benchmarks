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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.0 | 5.9 | 2.66 ± 0.52 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.3 | 5.6 | 2.67 ± 0.52 |
| lanjian | input-kcen | 3.4 ± 0.4 | 2.6 | 6.6 | 2.99 ± 0.57 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.6 | 6.1 | 3.06 ± 0.58 |
| pting | input-lanjian | 52.2 ± 0.9 | 50.4 | 55.0 | 45.88 ± 6.66 |
| pting | input-kcen | 52.5 ± 1.3 | 50.5 | 57.4 | 46.15 ± 6.74 |
| pting | input-mattcl | 53.2 ± 1.3 | 50.7 | 55.7 | 46.76 ± 6.84 |
| mattcl-py | input-lanjian | 54.3 ± 1.0 | 52.5 | 56.3 | 47.75 ± 6.93 |
| mattcl-py | input-kcen | 54.7 ± 1.3 | 52.7 | 58.0 | 48.08 ± 7.01 |
| pting | input-pting | 55.8 ± 1.2 | 53.5 | 59.3 | 49.05 ± 7.15 |
| mattcl-py | input-mattcl | 56.8 ± 5.0 | 54.2 | 90.8 | 49.98 ± 8.43 |
| mattcl-py | input-pting | 58.5 ± 1.4 | 56.5 | 63.7 | 51.43 ± 7.50 |
| kcen | input-lanjian | 84.5 ± 1.5 | 82.6 | 87.7 | 74.33 ± 10.79 |
| kcen | input-kcen | 85.2 ± 2.3 | 81.9 | 91.8 | 74.90 ± 10.98 |
| kcen | input-mattcl | 87.0 ± 1.7 | 83.5 | 93.5 | 76.53 ± 11.12 |
| kcen | input-pting | 90.0 ± 1.4 | 87.3 | 92.9 | 79.20 ± 11.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|