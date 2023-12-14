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
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.09 ± 0.29 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.10 ± 0.29 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.13 ± 0.29 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.4 | 4.0 | 2.90 ± 0.67 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.3 | 6.1 | 2.93 ± 0.76 |
| lanjian | input-kcen | 3.8 ± 0.4 | 3.0 | 6.0 | 3.52 ± 0.85 |
| lanjian | input-lanjian | 3.8 ± 0.5 | 3.0 | 6.2 | 3.54 ± 0.89 |
| mattcl-py | input-kcen | 55.8 ± 1.2 | 53.8 | 58.9 | 51.88 ± 11.41 |
| mattcl-py | input-lanjian | 56.3 ± 5.0 | 53.9 | 90.3 | 52.37 ± 12.37 |
| mattcl-py | input-mattcl | 57.4 ± 1.7 | 55.7 | 65.8 | 53.44 ± 11.80 |
| pting | input-kcen | 58.5 ± 1.8 | 54.6 | 64.1 | 54.43 ± 12.03 |
| pting | input-lanjian | 58.5 ± 1.3 | 55.8 | 60.8 | 54.45 ± 11.98 |
| pting | input-mattcl | 58.9 ± 3.0 | 55.3 | 76.7 | 54.83 ± 12.33 |
| mattcl-py | input-pting | 59.0 ± 1.8 | 56.6 | 65.6 | 54.93 ± 12.13 |
| pting | input-pting | 61.6 ± 1.6 | 58.7 | 66.0 | 57.29 ± 12.63 |
| kcen | input-lanjian | 84.6 ± 1.6 | 82.3 | 90.4 | 78.74 ± 17.30 |
| kcen | input-kcen | 85.4 ± 1.7 | 83.1 | 91.8 | 79.45 ± 17.46 |
| kcen | input-mattcl | 86.5 ± 1.2 | 84.8 | 89.5 | 80.47 ± 17.65 |
| kcen | input-pting | 90.0 ± 1.2 | 86.5 | 91.7 | 83.73 ± 18.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|