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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.27 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.28 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.1 | 3.41 ± 0.75 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 4.7 | 3.44 ± 0.76 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 6.6 | 3.96 ± 0.90 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.8 | 5.4 | 4.03 ± 0.90 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.0 | 17.20 ± 3.45 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 13.9 | 18.5 | 17.21 ± 3.46 |
| mattcl-py | input-kcen | 15.3 ± 0.7 | 14.2 | 18.2 | 17.31 ± 3.49 |
| mattcl-py | input-pting | 15.3 ± 0.9 | 13.9 | 18.9 | 17.35 ± 3.55 |
| pting | input-lanjian | 58.3 ± 1.7 | 56.5 | 66.3 | 66.12 ± 13.15 |
| pting | input-kcen | 58.6 ± 1.3 | 56.6 | 63.3 | 66.46 ± 13.16 |
| pting | input-mattcl | 58.7 ± 2.3 | 56.2 | 72.0 | 66.62 ± 13.36 |
| pting | input-pting | 61.3 ± 1.3 | 59.0 | 64.5 | 69.58 ± 13.77 |
| kcen | input-lanjian | 88.2 ± 1.6 | 84.3 | 92.0 | 100.09 ± 19.78 |
| kcen | input-mattcl | 89.1 ± 1.3 | 86.5 | 92.1 | 101.07 ± 19.94 |
| kcen | input-kcen | 89.1 ± 1.3 | 86.9 | 91.7 | 101.16 ± 19.96 |
| kcen | input-pting | 93.7 ± 1.3 | 90.9 | 96.6 | 106.33 ± 20.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|