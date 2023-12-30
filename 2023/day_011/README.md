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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.1 | 1.0 | 1.00 ± 0.25 |
| mattcl | input-lanjian | 0.9 ± 0.1 | 0.3 | 1.0 | 1.01 ± 0.26 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.4 | 1.05 ± 0.26 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 4.6 | 3.46 ± 0.71 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.0 | 4.7 | 3.48 ± 0.74 |
| lanjian | input-lanjian | 3.4 ± 0.3 | 2.9 | 5.8 | 3.97 ± 0.84 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.8 | 6.4 | 4.09 ± 0.91 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 13.9 | 18.1 | 17.40 ± 3.34 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.0 | 18.0 | 17.48 ± 3.36 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.0 | 18.9 | 17.52 ± 3.35 |
| mattcl-py | input-kcen | 15.2 ± 0.8 | 13.9 | 20.0 | 17.53 ± 3.42 |
| pting | input-lanjian | 58.0 ± 1.4 | 55.6 | 62.2 | 66.93 ± 12.64 |
| pting | input-kcen | 58.5 ± 2.3 | 56.1 | 69.6 | 67.45 ± 12.89 |
| pting | input-mattcl | 58.8 ± 4.9 | 56.1 | 91.4 | 67.78 ± 13.88 |
| pting | input-pting | 62.0 ± 2.4 | 58.7 | 73.2 | 71.51 ± 13.68 |
| kcen | input-lanjian | 86.9 ± 1.3 | 85.1 | 90.9 | 100.25 ± 18.82 |
| kcen | input-mattcl | 88.8 ± 1.5 | 86.4 | 92.0 | 102.46 ± 19.26 |
| kcen | input-kcen | 89.1 ± 1.7 | 86.3 | 92.9 | 102.74 ± 19.33 |
| kcen | input-pting | 95.2 ± 6.8 | 90.6 | 124.1 | 109.79 ± 22.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|