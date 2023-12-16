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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.26 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.1 | 1.02 ± 0.24 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.3 | 1.3 | 1.02 ± 0.24 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.1 | 5.3 | 3.31 ± 0.68 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.2 | 5.9 | 3.33 ± 0.72 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.7 | 5.2 | 3.77 ± 0.80 |
| lanjian | input-kcen | 3.6 ± 0.4 | 2.6 | 5.7 | 3.84 ± 0.83 |
| mattcl-py | input-pting | 15.2 ± 0.5 | 14.1 | 18.4 | 16.38 ± 2.99 |
| mattcl-py | input-mattcl | 15.2 ± 0.5 | 14.2 | 18.1 | 16.42 ± 3.00 |
| mattcl-py | input-lanjian | 15.3 ± 0.5 | 14.2 | 18.6 | 16.53 ± 3.02 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.3 | 18.3 | 16.54 ± 3.04 |
| pting | input-lanjian | 53.3 ± 1.6 | 51.2 | 59.9 | 57.52 ± 10.44 |
| pting | input-kcen | 53.6 ± 1.3 | 52.1 | 57.2 | 57.84 ± 10.46 |
| pting | input-mattcl | 53.9 ± 1.5 | 51.8 | 60.2 | 58.17 ± 10.55 |
| pting | input-pting | 56.5 ± 1.8 | 54.0 | 63.6 | 61.01 ± 11.11 |
| kcen | input-lanjian | 91.7 ± 1.7 | 89.3 | 98.5 | 98.95 ± 17.83 |
| kcen | input-mattcl | 93.1 ± 1.7 | 90.2 | 98.3 | 100.43 ± 18.09 |
| kcen | input-kcen | 93.6 ± 2.6 | 89.6 | 100.6 | 100.97 ± 18.31 |
| kcen | input-pting | 98.0 ± 2.0 | 95.7 | 104.0 | 105.79 ± 19.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|