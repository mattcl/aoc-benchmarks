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
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.7 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.02 ± 0.30 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.2 | 1.09 ± 0.27 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.9 | 3.39 ± 0.82 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.2 | 5.9 | 3.45 ± 0.89 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.8 | 5.9 | 3.89 ± 0.94 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 3.0 | 5.9 | 3.90 ± 1.00 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 17.7 | 16.77 ± 3.75 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 13.9 | 18.4 | 16.82 ± 3.80 |
| mattcl-py | input-lanjian | 15.3 ± 0.7 | 14.3 | 18.6 | 16.84 ± 3.79 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.2 | 18.3 | 16.94 ± 3.81 |
| pting | input-kcen | 54.3 ± 1.0 | 52.8 | 56.9 | 59.87 ± 13.26 |
| pting | input-lanjian | 54.4 ± 1.9 | 51.6 | 60.9 | 60.06 ± 13.43 |
| pting | input-mattcl | 54.9 ± 3.2 | 52.5 | 75.7 | 60.58 ± 13.82 |
| pting | input-pting | 57.2 ± 1.2 | 54.9 | 60.1 | 63.05 ± 13.98 |
| kcen | input-lanjian | 85.2 ± 1.7 | 82.9 | 90.4 | 93.97 ± 20.82 |
| kcen | input-mattcl | 87.2 ± 1.4 | 84.4 | 90.7 | 96.22 ± 21.29 |
| kcen | input-kcen | 87.4 ± 1.7 | 84.6 | 91.8 | 96.39 ± 21.35 |
| kcen | input-pting | 90.8 ± 1.3 | 88.1 | 93.0 | 100.14 ± 22.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|