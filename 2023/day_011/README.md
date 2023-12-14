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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.6 | 2.73 ± 0.48 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 3.8 | 2.78 ± 0.46 |
| lanjian | input-lanjian | 3.4 ± 0.3 | 2.7 | 5.3 | 3.12 ± 0.56 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.8 | 5.5 | 3.17 ± 0.56 |
| pting | input-lanjian | 52.9 ± 1.1 | 50.8 | 56.1 | 47.81 ± 7.11 |
| pting | input-kcen | 53.9 ± 1.9 | 51.3 | 62.5 | 48.70 ± 7.37 |
| pting | input-mattcl | 54.0 ± 1.5 | 51.4 | 59.7 | 48.80 ± 7.32 |
| mattcl-py | input-kcen | 55.2 ± 0.9 | 54.0 | 57.5 | 49.87 ± 7.39 |
| mattcl-py | input-lanjian | 56.0 ± 5.7 | 53.4 | 93.4 | 50.61 ± 9.07 |
| pting | input-pting | 56.2 ± 1.0 | 54.8 | 59.1 | 50.80 ± 7.53 |
| mattcl-py | input-mattcl | 56.8 ± 1.5 | 54.5 | 60.7 | 51.32 ± 7.68 |
| mattcl-py | input-pting | 58.6 ± 1.2 | 56.9 | 61.6 | 52.96 ± 7.87 |
| kcen | input-lanjian | 84.9 ± 1.9 | 81.6 | 91.8 | 76.77 ± 11.44 |
| kcen | input-kcen | 86.2 ± 1.9 | 83.7 | 92.4 | 77.91 ± 11.60 |
| kcen | input-mattcl | 87.6 ± 2.3 | 84.2 | 96.2 | 79.16 ± 11.84 |
| kcen | input-pting | 90.4 ± 1.5 | 87.8 | 93.4 | 81.72 ± 12.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|