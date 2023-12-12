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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.4 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.70 ± 0.48 |
| lanjian | input-pting | 3.3 ± 0.5 | 2.4 | 6.4 | 2.81 ± 0.57 |
| lanjian | input-lanjian | 3.7 ± 0.4 | 2.9 | 6.3 | 3.21 ± 0.58 |
| lanjian | input-kcen | 3.8 ± 0.4 | 2.9 | 5.6 | 3.26 ± 0.59 |
| pting | input-lanjian | 52.9 ± 1.5 | 50.3 | 57.1 | 45.58 ± 6.71 |
| pting | input-mattcl | 53.1 ± 0.9 | 51.5 | 55.5 | 45.78 ± 6.66 |
| pting | input-kcen | 53.6 ± 1.8 | 51.0 | 61.0 | 46.20 ± 6.86 |
| mattcl-py | input-lanjian | 54.6 ± 1.1 | 52.4 | 57.7 | 47.09 ± 6.87 |
| mattcl-py | input-kcen | 54.9 ± 1.1 | 52.7 | 57.8 | 47.37 ± 6.91 |
| mattcl-py | input-mattcl | 56.1 ± 1.2 | 54.2 | 58.6 | 48.41 ± 7.07 |
| pting | input-pting | 56.2 ± 1.3 | 53.8 | 59.5 | 48.47 ± 7.09 |
| mattcl-py | input-pting | 58.6 ± 1.2 | 56.8 | 61.7 | 50.53 ± 7.37 |
| kcen | input-lanjian | 84.7 ± 2.0 | 82.7 | 92.5 | 73.03 ± 10.68 |
| kcen | input-kcen | 85.2 ± 2.2 | 82.8 | 93.5 | 73.47 ± 10.78 |
| kcen | input-mattcl | 87.6 ± 4.4 | 84.5 | 111.4 | 75.50 ± 11.54 |
| kcen | input-pting | 90.9 ± 1.9 | 87.6 | 96.7 | 78.37 ± 11.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|