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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.4 | 1.10 ± 0.39 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.23 ± 0.39 |
| mattcl | input-lanjian | 1.0 ± 3.2 | 0.1 | 46.0 | 1.25 ± 4.25 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 1.9 | 4.3 | 3.87 ± 1.14 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.0 | 4.0 | 3.97 ± 1.16 |
| lanjian | input-lanjian | 3.3 ± 0.4 | 2.4 | 5.3 | 4.36 ± 1.34 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 5.5 | 4.58 ± 1.36 |
| mattcl-py | input-lanjian | 15.2 ± 0.5 | 14.2 | 18.1 | 20.06 ± 5.56 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 17.9 | 20.07 ± 5.56 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.1 | 18.1 | 20.15 ± 5.61 |
| mattcl-py | input-pting | 15.3 ± 0.6 | 14.2 | 19.7 | 20.17 ± 5.61 |
| pting | input-lanjian | 56.0 ± 1.1 | 54.3 | 58.9 | 73.85 ± 20.35 |
| pting | input-kcen | 56.0 ± 1.3 | 54.6 | 62.3 | 73.87 ± 20.37 |
| pting | input-mattcl | 56.6 ± 1.3 | 54.9 | 61.2 | 74.69 ± 20.60 |
| pting | input-pting | 59.2 ± 1.3 | 57.2 | 62.4 | 78.08 ± 21.52 |
| kcen | input-lanjian | 85.2 ± 1.7 | 82.2 | 89.5 | 112.42 ± 30.99 |
| kcen | input-mattcl | 86.7 ± 2.5 | 84.7 | 99.6 | 114.41 ± 31.62 |
| kcen | input-kcen | 86.7 ± 1.2 | 85.0 | 90.2 | 114.41 ± 31.49 |
| kcen | input-pting | 91.7 ± 2.0 | 89.3 | 99.4 | 120.99 ± 33.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|