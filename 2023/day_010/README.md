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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.1 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.3 | 1.4 | 1.01 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.0 | 1.7 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.6 | 1.04 ± 0.30 |
| lanjian | input-mattcl | 2.7 ± 0.3 | 1.9 | 4.6 | 3.04 ± 0.65 |
| lanjian | input-kcen | 2.7 ± 0.2 | 2.0 | 4.4 | 3.06 ± 0.64 |
| lanjian | input-pting | 2.7 ± 0.3 | 1.9 | 5.6 | 3.06 ± 0.70 |
| lanjian | input-lanjian | 2.7 ± 0.4 | 2.0 | 5.6 | 3.07 ± 0.71 |
| mattcl-ts | input-kcen | 17.1 ± 0.4 | 16.0 | 18.1 | 19.51 ± 3.71 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.0 | 18.1 | 19.56 ± 3.73 |
| mattcl-ts | input-pting | 17.2 ± 0.4 | 16.3 | 18.5 | 19.61 ± 3.73 |
| mattcl-ts | input-lanjian | 17.3 ± 0.4 | 16.2 | 19.1 | 19.72 ± 3.76 |
| mattcl-py | input-kcen | 25.4 ± 0.7 | 24.2 | 28.5 | 28.95 ± 5.52 |
| mattcl-py | input-mattcl | 25.6 ± 0.9 | 24.2 | 28.6 | 29.18 ± 5.61 |
| mattcl-py | input-pting | 25.8 ± 0.7 | 24.7 | 28.5 | 29.40 ± 5.61 |
| mattcl-py | input-lanjian | 26.1 ± 1.0 | 24.8 | 29.2 | 29.77 ± 5.74 |
| pting | input-kcen | 26.6 ± 0.7 | 25.4 | 29.1 | 30.30 ± 5.79 |
| pting | input-mattcl | 26.8 ± 0.7 | 25.7 | 29.6 | 30.47 ± 5.82 |
| pting | input-pting | 26.9 ± 1.0 | 25.3 | 30.3 | 30.64 ± 5.91 |
| pting | input-lanjian | 26.9 ± 0.9 | 25.7 | 29.9 | 30.69 ± 5.89 |
| kcen | input-pting | 46.8 ± 1.1 | 45.0 | 50.2 | 53.34 ± 10.16 |
| kcen | input-lanjian | 48.1 ± 1.1 | 46.0 | 50.8 | 54.75 ± 10.42 |
| kcen | input-mattcl | 50.1 ± 1.3 | 48.3 | 55.1 | 57.08 ± 10.89 |
| kcen | input-kcen | 50.4 ± 2.6 | 48.3 | 68.0 | 57.42 ± 11.24 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|