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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.5 | 1.4 | 1.02 ± 0.20 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 5.9 | 2.63 ± 0.49 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 4.3 | 2.63 ± 0.45 |
| lanjian | input-lanjian | 3.6 ± 0.4 | 3.2 | 5.4 | 3.16 ± 0.60 |
| lanjian | input-kcen | 3.7 ± 0.5 | 3.1 | 6.5 | 3.17 ± 0.65 |
| pting | input-lanjian | 52.6 ± 1.3 | 50.7 | 56.9 | 45.54 ± 7.36 |
| pting | input-kcen | 52.8 ± 1.3 | 50.4 | 56.9 | 45.75 ± 7.40 |
| pting | input-mattcl | 53.3 ± 1.2 | 51.2 | 55.9 | 46.14 ± 7.45 |
| mattcl-py | input-kcen | 54.3 ± 1.0 | 52.7 | 57.0 | 47.06 ± 7.56 |
| mattcl-py | input-lanjian | 54.4 ± 1.5 | 52.3 | 60.2 | 47.09 ± 7.63 |
| pting | input-pting | 55.7 ± 1.4 | 53.7 | 61.7 | 48.26 ± 7.81 |
| mattcl-py | input-mattcl | 56.0 ± 1.4 | 54.2 | 60.5 | 48.47 ± 7.83 |
| mattcl-py | input-pting | 58.5 ± 2.3 | 56.2 | 72.4 | 50.68 ± 8.33 |
| kcen | input-lanjian | 84.1 ± 1.6 | 81.0 | 88.4 | 72.85 ± 11.72 |
| kcen | input-kcen | 85.5 ± 3.5 | 82.3 | 101.5 | 74.04 ± 12.20 |
| kcen | input-mattcl | 86.0 ± 1.6 | 84.2 | 92.6 | 74.51 ± 11.98 |
| kcen | input-pting | 91.2 ± 3.0 | 87.1 | 99.7 | 78.98 ± 12.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|