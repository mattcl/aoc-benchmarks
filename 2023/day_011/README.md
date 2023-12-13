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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.1 | 0.7 | 1.6 | 1.03 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.6 | 1.06 ± 0.24 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.6 | 6.0 | 2.84 ± 0.59 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.9 | 2.84 ± 0.63 |
| lanjian | input-lanjian | 3.5 ± 0.4 | 2.8 | 6.3 | 3.20 ± 0.65 |
| lanjian | input-kcen | 3.6 ± 2.4 | 2.5 | 37.0 | 3.30 ± 2.27 |
| pting | input-lanjian | 52.6 ± 3.5 | 50.6 | 76.4 | 48.17 ± 9.03 |
| pting | input-mattcl | 52.9 ± 1.3 | 51.0 | 57.1 | 48.40 ± 8.57 |
| pting | input-kcen | 53.2 ± 2.3 | 50.8 | 64.0 | 48.67 ± 8.79 |
| mattcl-py | input-lanjian | 54.5 ± 1.1 | 52.8 | 57.3 | 49.88 ± 8.80 |
| pting | input-pting | 55.7 ± 2.0 | 53.5 | 63.7 | 51.00 ± 9.12 |
| mattcl-py | input-kcen | 55.8 ± 6.4 | 53.2 | 96.3 | 51.07 ± 10.71 |
| mattcl-py | input-mattcl | 56.0 ± 2.2 | 53.8 | 69.3 | 51.21 ± 9.20 |
| mattcl-py | input-pting | 57.9 ± 1.2 | 55.7 | 60.6 | 52.98 ± 9.35 |
| kcen | input-lanjian | 84.0 ± 2.3 | 81.5 | 90.9 | 76.91 ± 13.64 |
| kcen | input-kcen | 85.2 ± 1.8 | 82.7 | 92.3 | 77.97 ± 13.76 |
| kcen | input-mattcl | 86.1 ± 2.1 | 83.9 | 93.2 | 78.80 ± 13.94 |
| kcen | input-pting | 88.8 ± 2.0 | 86.7 | 96.7 | 81.25 ± 14.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|