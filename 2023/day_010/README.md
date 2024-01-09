# Day 10 benchmarks

[link to problem](https://adventofcode.com/2023/day/10)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 10)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 1.4 ± 0.2 | 0.5 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.6 | 2.2 | 1.07 ± 0.23 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 4.8 | 2.24 ± 0.39 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.7 | 2.24 ± 0.40 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.7 | 2.26 ± 0.42 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.2 | 2.27 ± 0.39 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.6 | 18.9 | 12.80 ± 2.03 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.8 | 18.9 | 12.88 ± 2.04 |
| mattcl-ts | input-kcen | 17.7 ± 0.4 | 16.8 | 18.9 | 12.89 ± 2.04 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.7 | 19.7 | 12.98 ± 2.06 |
| mattcl-py | input-kcen | 25.8 ± 0.8 | 24.6 | 28.9 | 18.82 ± 3.01 |
| mattcl-py | input-pting | 26.0 ± 0.7 | 24.8 | 28.7 | 18.92 ± 3.01 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.5 | 29.1 | 18.96 ± 3.05 |
| mattcl-py | input-lanjian | 26.2 ± 0.8 | 25.1 | 29.6 | 19.09 ± 3.04 |
| pting | input-pting | 27.1 ± 0.7 | 25.9 | 29.5 | 19.76 ± 3.13 |
| pting | input-kcen | 27.2 ± 0.6 | 26.1 | 29.1 | 19.79 ± 3.13 |
| pting | input-lanjian | 27.2 ± 0.6 | 26.1 | 30.0 | 19.84 ± 3.14 |
| pting | input-mattcl | 27.3 ± 0.9 | 26.0 | 30.5 | 19.91 ± 3.19 |
| kcen | input-pting | 47.5 ± 1.3 | 45.1 | 50.7 | 34.64 ± 5.51 |
| kcen | input-lanjian | 48.6 ± 1.0 | 47.1 | 50.8 | 35.46 ± 5.61 |
| kcen | input-kcen | 50.5 ± 0.9 | 48.8 | 53.2 | 36.84 ± 5.81 |
| kcen | input-mattcl | 51.2 ± 4.6 | 48.4 | 82.6 | 37.30 ± 6.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|