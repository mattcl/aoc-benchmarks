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
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.3 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.03 ± 0.26 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.4 | 1.03 ± 0.27 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.1 | 4.7 | 3.55 ± 0.70 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.1 | 5.7 | 3.62 ± 0.76 |
| lanjian | input-lanjian | 3.4 ± 0.3 | 2.6 | 4.8 | 4.11 ± 0.82 |
| lanjian | input-kcen | 3.5 ± 0.4 | 3.0 | 5.2 | 4.14 ± 0.84 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 13.9 | 18.4 | 18.14 ± 3.23 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 13.7 | 18.4 | 18.16 ± 3.25 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.0 | 18.3 | 18.20 ± 3.25 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.1 | 18.4 | 18.27 ± 3.24 |
| pting | input-lanjian | 54.1 ± 1.2 | 52.2 | 57.6 | 64.80 ± 11.33 |
| pting | input-kcen | 54.5 ± 1.4 | 52.7 | 59.1 | 65.35 ± 11.45 |
| pting | input-mattcl | 54.6 ± 1.1 | 52.8 | 57.0 | 65.44 ± 11.43 |
| pting | input-pting | 57.6 ± 1.2 | 55.3 | 61.7 | 69.02 ± 12.06 |
| kcen | input-lanjian | 85.2 ± 1.5 | 83.0 | 90.1 | 102.14 ± 17.80 |
| kcen | input-mattcl | 86.6 ± 1.3 | 85.1 | 90.7 | 103.76 ± 18.05 |
| kcen | input-kcen | 87.0 ± 1.4 | 84.4 | 90.5 | 104.21 ± 18.14 |
| kcen | input-pting | 91.3 ± 2.1 | 88.2 | 97.8 | 109.43 ± 19.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|