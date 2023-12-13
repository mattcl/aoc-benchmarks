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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 2.0 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.9 | 1.05 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 2.1 | 0.2 | 30.3 | 1.05 ± 1.95 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 5.7 | 2.80 ± 0.52 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 4.8 | 2.83 ± 0.52 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 2.9 | 5.2 | 3.21 ± 0.57 |
| lanjian | input-kcen | 3.6 ± 2.3 | 2.5 | 35.2 | 3.38 ± 2.19 |
| pting | input-lanjian | 52.4 ± 1.1 | 50.2 | 55.7 | 48.65 ± 7.74 |
| pting | input-kcen | 52.8 ± 1.3 | 50.9 | 57.6 | 49.03 ± 7.82 |
| pting | input-mattcl | 53.0 ± 1.7 | 51.3 | 60.6 | 49.16 ± 7.91 |
| mattcl-py | input-lanjian | 54.4 ± 1.0 | 53.0 | 57.2 | 50.51 ± 8.02 |
| mattcl-py | input-kcen | 55.7 ± 6.0 | 53.3 | 98.3 | 51.65 ± 9.86 |
| mattcl-py | input-mattcl | 55.8 ± 1.2 | 54.0 | 58.9 | 51.83 ± 8.25 |
| pting | input-pting | 55.9 ± 1.8 | 53.7 | 62.9 | 51.84 ± 8.35 |
| mattcl-py | input-pting | 58.2 ± 1.4 | 55.9 | 63.1 | 53.97 ± 8.60 |
| kcen | input-lanjian | 84.5 ± 1.8 | 82.1 | 90.5 | 78.44 ± 12.47 |
| kcen | input-kcen | 85.8 ± 2.9 | 83.0 | 98.2 | 79.60 ± 12.83 |
| kcen | input-mattcl | 86.9 ± 2.8 | 83.7 | 94.8 | 80.69 ± 12.98 |
| kcen | input-pting | 90.0 ± 2.6 | 86.8 | 97.8 | 83.49 ± 13.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|