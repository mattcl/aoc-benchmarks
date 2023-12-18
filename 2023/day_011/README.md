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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.2 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.25 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.26 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.3 | 3.27 ± 0.71 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.1 | 5.8 | 3.39 ± 0.71 |
| lanjian | input-kcen | 3.4 ± 0.3 | 2.7 | 4.8 | 3.71 ± 0.77 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.9 | 6.3 | 3.72 ± 0.83 |
| mattcl-py | input-lanjian | 15.1 ± 0.7 | 13.9 | 18.0 | 16.33 ± 3.11 |
| mattcl-py | input-pting | 15.1 ± 0.7 | 14.1 | 18.2 | 16.34 ± 3.13 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 14.0 | 18.4 | 16.36 ± 3.10 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.0 | 18.0 | 16.40 ± 3.12 |
| pting | input-lanjian | 52.6 ± 1.9 | 50.9 | 64.0 | 56.89 ± 10.74 |
| pting | input-kcen | 53.2 ± 2.4 | 51.1 | 64.6 | 57.52 ± 10.96 |
| pting | input-mattcl | 53.6 ± 1.5 | 51.4 | 58.2 | 57.96 ± 10.86 |
| pting | input-pting | 55.6 ± 1.5 | 53.4 | 60.6 | 60.13 ± 11.25 |
| kcen | input-lanjian | 85.3 ± 1.9 | 82.9 | 92.2 | 92.20 ± 17.20 |
| kcen | input-kcen | 86.7 ± 2.6 | 84.0 | 100.1 | 93.81 ± 17.60 |
| kcen | input-mattcl | 86.8 ± 1.4 | 84.5 | 90.6 | 93.83 ± 17.44 |
| kcen | input-pting | 90.1 ± 1.2 | 87.7 | 92.4 | 97.41 ± 18.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|