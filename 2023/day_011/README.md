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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.00 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 ± 0.27 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.28 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 3.6 | 3.25 ± 0.67 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.2 | 5.6 | 3.38 ± 0.76 |
| lanjian | input-lanjian | 3.5 ± 0.5 | 2.6 | 6.8 | 3.73 ± 0.88 |
| lanjian | input-kcen | 3.5 ± 0.4 | 2.7 | 4.9 | 3.73 ± 0.84 |
| mattcl-py | input-lanjian | 15.0 ± 0.3 | 14.2 | 16.3 | 16.23 ± 3.10 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 14.3 | 17.9 | 16.27 ± 3.15 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 13.9 | 18.5 | 16.27 ± 3.15 |
| mattcl-py | input-kcen | 15.2 ± 0.5 | 14.1 | 18.6 | 16.37 ± 3.16 |
| pting | input-lanjian | 53.6 ± 2.5 | 51.2 | 69.0 | 57.97 ± 11.33 |
| pting | input-mattcl | 54.1 ± 1.8 | 52.0 | 64.6 | 58.43 ± 11.25 |
| pting | input-kcen | 54.2 ± 2.2 | 51.9 | 65.6 | 58.54 ± 11.36 |
| pting | input-pting | 56.4 ± 2.5 | 54.1 | 70.2 | 60.95 ± 11.86 |
| kcen | input-lanjian | 88.7 ± 1.5 | 85.7 | 91.5 | 95.83 ± 18.25 |
| kcen | input-mattcl | 89.3 ± 1.3 | 87.3 | 91.9 | 96.49 ± 18.35 |
| kcen | input-kcen | 90.3 ± 2.2 | 86.9 | 98.6 | 97.54 ± 18.65 |
| kcen | input-pting | 93.6 ± 1.4 | 90.9 | 96.7 | 101.12 ± 19.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-lanjian|<pre>9556896</pre>|<pre>685038186836</pre>|
|input-mattcl|<pre>9724940</pre>|<pre>569052586852</pre>|
|input-pting|<pre>10276166</pre>|<pre>598693078798</pre>|