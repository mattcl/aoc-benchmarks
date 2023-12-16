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
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.0 | 1.06 ± 0.23 |
| mattcl | input-kcen | 1.0 ± 4.0 | 0.1 | 57.8 | 1.16 ± 4.87 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.0 | 4.3 | 3.57 ± 0.75 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 5.0 | 3.58 ± 0.72 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 6.4 | 4.06 ± 0.91 |
| lanjian | input-kcen | 3.5 ± 1.7 | 2.2 | 26.1 | 4.19 ± 2.14 |
| mattcl-py | input-pting | 15.0 ± 0.5 | 13.8 | 17.2 | 18.09 ± 3.37 |
| mattcl-py | input-lanjian | 15.1 ± 0.6 | 13.9 | 18.4 | 18.17 ± 3.40 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 13.9 | 17.8 | 18.18 ± 3.39 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.2 | 18.3 | 18.40 ± 3.46 |
| pting | input-lanjian | 53.4 ± 2.1 | 51.5 | 64.1 | 64.18 ± 12.03 |
| pting | input-kcen | 53.8 ± 1.9 | 52.1 | 64.9 | 64.70 ± 12.07 |
| pting | input-mattcl | 53.9 ± 2.1 | 51.7 | 62.0 | 64.78 ± 12.12 |
| pting | input-pting | 56.0 ± 1.5 | 54.2 | 62.5 | 67.34 ± 12.48 |
| kcen | input-lanjian | 90.9 ± 1.5 | 88.5 | 94.5 | 109.38 ± 20.13 |
| kcen | input-mattcl | 92.5 ± 2.0 | 89.4 | 100.8 | 111.22 ± 20.52 |
| kcen | input-kcen | 93.2 ± 1.7 | 90.4 | 98.9 | 112.13 ± 20.65 |
| kcen | input-pting | 97.4 ± 3.4 | 94.3 | 112.8 | 117.18 ± 21.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|