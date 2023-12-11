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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.08 ± 0.27 |
| lanjian | input-mattcl | 2.9 ± 0.3 | 2.1 | 4.8 | 2.64 ± 0.56 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.2 | 4.3 | 2.70 ± 0.54 |
| lanjian | input-kcen | 3.3 ± 0.4 | 2.6 | 5.4 | 2.99 ± 0.68 |
| lanjian | input-lanjian | 3.4 ± 0.4 | 2.6 | 6.2 | 3.03 ± 0.69 |
| pting | input-kcen | 52.2 ± 1.5 | 50.6 | 57.1 | 46.85 ± 8.80 |
| pting | input-mattcl | 53.1 ± 1.1 | 51.1 | 56.6 | 47.66 ± 8.91 |
| pting | input-lanjian | 53.3 ± 4.5 | 50.5 | 82.0 | 47.81 ± 9.74 |
| mattcl-py | input-kcen | 53.9 ± 1.0 | 52.3 | 56.9 | 48.36 ± 9.02 |
| mattcl-py | input-lanjian | 54.4 ± 1.8 | 52.6 | 64.9 | 48.81 ± 9.20 |
| mattcl-py | input-mattcl | 55.7 ± 1.0 | 54.1 | 58.6 | 50.05 ± 9.33 |
| pting | input-pting | 55.8 ± 2.0 | 53.7 | 65.8 | 50.09 ± 9.46 |
| mattcl-py | input-pting | 57.9 ± 1.1 | 56.0 | 60.4 | 51.99 ± 9.70 |
| kcen | input-kcen | 88.8 ± 1.8 | 85.5 | 95.0 | 79.70 ± 14.88 |
| kcen | input-lanjian | 89.1 ± 2.2 | 86.3 | 96.2 | 80.01 ± 14.99 |
| kcen | input-mattcl | 90.6 ± 1.5 | 88.6 | 96.2 | 81.38 ± 15.16 |
| kcen | input-pting | 95.0 ± 1.7 | 92.0 | 97.9 | 85.27 ± 15.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|