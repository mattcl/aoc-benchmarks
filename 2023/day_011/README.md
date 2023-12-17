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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.28 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.2 | 5.3 | 3.33 ± 0.75 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 4.1 | 3.43 ± 0.73 |
| lanjian | input-lanjian | 3.4 ± 0.5 | 2.7 | 5.9 | 3.85 ± 0.90 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 5.8 | 3.92 ± 0.85 |
| mattcl-py | input-kcen | 15.0 ± 0.4 | 14.1 | 17.8 | 16.93 ± 3.27 |
| mattcl-py | input-mattcl | 15.0 ± 0.6 | 13.9 | 17.6 | 16.95 ± 3.29 |
| mattcl-py | input-pting | 15.0 ± 0.7 | 13.8 | 18.0 | 16.97 ± 3.34 |
| mattcl-py | input-lanjian | 15.1 ± 0.7 | 14.1 | 18.1 | 17.03 ± 3.34 |
| pting | input-lanjian | 52.9 ± 1.4 | 50.8 | 59.2 | 59.70 ± 11.49 |
| pting | input-mattcl | 53.8 ± 2.0 | 51.7 | 65.3 | 60.76 ± 11.81 |
| pting | input-kcen | 53.9 ± 4.6 | 51.2 | 85.6 | 60.88 ± 12.74 |
| pting | input-pting | 56.1 ± 1.4 | 54.1 | 61.2 | 63.30 ± 12.17 |
| kcen | input-lanjian | 87.8 ± 1.6 | 85.0 | 91.4 | 99.10 ± 18.99 |
| kcen | input-mattcl | 89.2 ± 1.4 | 87.1 | 92.6 | 100.76 ± 19.28 |
| kcen | input-kcen | 89.5 ± 1.6 | 86.9 | 93.1 | 101.04 ± 19.36 |
| kcen | input-pting | 93.6 ± 1.4 | 90.9 | 97.4 | 105.68 ± 20.22 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|