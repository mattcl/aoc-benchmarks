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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.5 | 1.06 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.6 | 1.1 | 1.13 ± 0.27 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.3 | 5.6 | 3.39 ± 0.84 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.2 | 5.6 | 3.40 ± 0.85 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.9 | 5.1 | 3.83 ± 0.93 |
| lanjian | input-kcen | 3.5 ± 0.3 | 2.9 | 4.9 | 3.85 ± 0.91 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 17.6 | 16.77 ± 3.68 |
| mattcl-py | input-lanjian | 15.2 ± 0.5 | 14.4 | 18.9 | 16.78 ± 3.67 |
| mattcl-py | input-pting | 15.3 ± 0.7 | 14.4 | 18.6 | 16.85 ± 3.72 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.1 | 18.9 | 16.95 ± 3.73 |
| pting | input-lanjian | 53.5 ± 1.5 | 51.5 | 59.0 | 59.00 ± 12.86 |
| pting | input-mattcl | 53.6 ± 1.0 | 52.0 | 56.5 | 59.01 ± 12.80 |
| pting | input-kcen | 54.5 ± 3.9 | 51.8 | 80.1 | 60.02 ± 13.66 |
| pting | input-pting | 55.8 ± 1.0 | 53.8 | 58.1 | 61.53 ± 13.34 |
| kcen | input-lanjian | 85.2 ± 1.5 | 83.3 | 89.0 | 93.85 ± 20.35 |
| kcen | input-mattcl | 86.9 ± 3.0 | 84.0 | 102.2 | 95.70 ± 20.95 |
| kcen | input-kcen | 86.9 ± 2.3 | 84.7 | 95.1 | 95.78 ± 20.85 |
| kcen | input-pting | 91.3 ± 2.4 | 88.5 | 100.4 | 100.60 ± 21.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|