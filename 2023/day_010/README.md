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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.5 | 1.9 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.1 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.2 | 1.03 ± 0.20 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.5 | 1.04 ± 0.21 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 3.7 | 2.22 ± 0.32 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 4.9 | 2.23 ± 0.34 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.6 | 2.26 ± 0.37 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.6 | 5.8 | 2.27 ± 0.38 |
| mattcl-ts | input-mattcl | 17.1 ± 0.5 | 16.0 | 18.7 | 12.41 ± 1.70 |
| mattcl-ts | input-pting | 17.2 ± 0.4 | 16.2 | 18.8 | 12.51 ± 1.71 |
| mattcl-ts | input-lanjian | 17.4 ± 0.5 | 16.4 | 18.9 | 12.66 ± 1.74 |
| mattcl-ts | input-kcen | 17.4 ± 3.8 | 16.1 | 66.1 | 12.68 ± 3.24 |
| mattcl-py | input-mattcl | 25.9 ± 1.0 | 24.7 | 30.5 | 18.83 ± 2.64 |
| mattcl-py | input-kcen | 25.9 ± 1.0 | 24.7 | 29.1 | 18.86 ± 2.63 |
| mattcl-py | input-pting | 26.5 ± 0.9 | 25.1 | 29.6 | 19.24 ± 2.67 |
| mattcl-py | input-lanjian | 26.5 ± 1.1 | 25.2 | 30.0 | 19.30 ± 2.71 |
| pting | input-mattcl | 27.3 ± 0.7 | 26.1 | 30.4 | 19.82 ± 2.72 |
| pting | input-kcen | 27.3 ± 0.8 | 26.1 | 29.6 | 19.83 ± 2.72 |
| pting | input-lanjian | 27.4 ± 0.7 | 26.2 | 30.3 | 19.89 ± 2.72 |
| pting | input-pting | 27.5 ± 1.1 | 26.2 | 31.9 | 20.01 ± 2.80 |
| kcen | input-pting | 47.4 ± 0.9 | 45.9 | 50.4 | 34.45 ± 4.68 |
| kcen | input-lanjian | 48.7 ± 1.4 | 46.7 | 54.7 | 35.38 ± 4.86 |
| kcen | input-mattcl | 50.1 ± 1.1 | 48.6 | 53.2 | 36.45 ± 4.96 |
| kcen | input-kcen | 50.6 ± 1.4 | 48.3 | 54.6 | 36.76 ± 5.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|