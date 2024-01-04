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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.26 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.3 | 1.3 | 1.05 ± 0.24 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.6 | 1.7 | 1.06 ± 0.24 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.1 | 4.5 | 3.33 ± 0.73 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.5 | 3.36 ± 0.73 |
| lanjian | input-lanjian | 3.5 ± 0.3 | 3.1 | 5.6 | 3.82 ± 0.82 |
| lanjian | input-kcen | 3.6 ± 0.5 | 2.9 | 6.6 | 3.90 ± 0.91 |
| mattcl-py | input-pting | 15.0 ± 0.6 | 13.9 | 18.0 | 16.25 ± 3.14 |
| mattcl-py | input-lanjian | 15.0 ± 0.6 | 14.0 | 18.0 | 16.30 ± 3.16 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 14.0 | 17.9 | 16.31 ± 3.15 |
| mattcl-py | input-kcen | 15.2 ± 1.5 | 14.1 | 34.8 | 16.53 ± 3.53 |
| pting | input-kcen | 53.1 ± 1.2 | 51.5 | 57.2 | 57.58 ± 10.97 |
| pting | input-mattcl | 53.4 ± 1.3 | 51.4 | 58.6 | 57.86 ± 11.05 |
| pting | input-lanjian | 53.5 ± 1.9 | 51.1 | 60.9 | 58.01 ± 11.17 |
| pting | input-pting | 56.0 ± 1.9 | 53.9 | 66.2 | 60.74 ± 11.68 |
| kcen | input-lanjian | 85.4 ± 1.8 | 82.7 | 90.0 | 92.67 ± 17.65 |
| kcen | input-kcen | 86.5 ± 1.6 | 83.9 | 90.8 | 93.77 ± 17.83 |
| kcen | input-mattcl | 86.9 ± 1.4 | 84.7 | 90.5 | 94.22 ± 17.89 |
| kcen | input-pting | 90.7 ± 2.2 | 87.8 | 98.2 | 98.36 ± 18.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|