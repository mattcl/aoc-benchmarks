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
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.39 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.10 ± 0.39 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.5 | 1.12 ± 0.38 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.0 | 4.8 | 3.95 ± 1.18 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.0 | 5.2 | 4.07 ± 1.22 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.6 | 6.4 | 4.48 ± 1.38 |
| lanjian | input-kcen | 3.3 ± 0.5 | 2.7 | 6.5 | 4.55 ± 1.45 |
| mattcl-py | input-pting | 14.8 ± 0.5 | 13.9 | 18.1 | 20.48 ± 5.85 |
| mattcl-py | input-mattcl | 14.9 ± 0.7 | 13.8 | 18.2 | 20.59 ± 5.91 |
| mattcl-py | input-lanjian | 14.9 ± 0.7 | 14.0 | 18.1 | 20.62 ± 5.93 |
| mattcl-py | input-kcen | 15.0 ± 0.7 | 13.8 | 18.3 | 20.68 ± 5.94 |
| pting | input-lanjian | 53.0 ± 1.7 | 51.0 | 58.8 | 73.08 ± 20.86 |
| pting | input-mattcl | 53.1 ± 1.3 | 51.3 | 57.2 | 73.23 ± 20.84 |
| pting | input-kcen | 53.3 ± 2.5 | 51.1 | 66.7 | 73.50 ± 21.13 |
| pting | input-pting | 56.1 ± 2.1 | 53.8 | 67.7 | 77.38 ± 22.13 |
| kcen | input-lanjian | 85.0 ± 3.3 | 82.8 | 100.2 | 117.34 ± 33.59 |
| kcen | input-kcen | 85.6 ± 1.1 | 83.7 | 88.4 | 118.14 ± 33.54 |
| kcen | input-mattcl | 86.2 ± 1.6 | 83.6 | 90.8 | 118.88 ± 33.78 |
| kcen | input-pting | 90.5 ± 2.3 | 88.2 | 100.6 | 124.84 ± 35.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|