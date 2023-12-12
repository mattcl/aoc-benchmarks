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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.4 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.04 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.8 | 1.5 | 1.04 ± 0.22 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 4.8 | 2.56 ± 0.46 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.4 | 4.8 | 2.57 ± 0.46 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 6.0 | 2.58 ± 0.51 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.4 | 5.8 | 2.60 ± 0.53 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.7 | 14.83 ± 2.47 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.5 | 18.9 | 14.86 ± 2.48 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.8 | 18.9 | 15.02 ± 2.51 |
| mattcl-ts | input-pting | 17.8 ± 2.7 | 16.7 | 52.3 | 15.06 ± 3.39 |
| mattcl-py | input-kcen | 25.8 ± 0.9 | 24.4 | 28.7 | 21.87 ± 3.70 |
| mattcl-py | input-mattcl | 25.8 ± 0.9 | 24.3 | 29.9 | 21.93 ± 3.70 |
| mattcl-py | input-lanjian | 26.1 ± 0.7 | 25.0 | 29.5 | 22.16 ± 3.71 |
| mattcl-py | input-pting | 26.1 ± 0.8 | 24.8 | 29.4 | 22.17 ± 3.73 |
| pting | input-mattcl | 26.9 ± 0.6 | 25.7 | 29.5 | 22.83 ± 3.81 |
| pting | input-kcen | 27.0 ± 0.6 | 25.6 | 29.8 | 22.88 ± 3.82 |
| pting | input-lanjian | 27.2 ± 0.8 | 26.1 | 30.4 | 23.05 ± 3.86 |
| pting | input-pting | 27.3 ± 2.5 | 25.8 | 51.8 | 23.18 ± 4.36 |
| kcen | input-pting | 47.3 ± 1.0 | 45.3 | 49.7 | 40.09 ± 6.68 |
| kcen | input-lanjian | 48.6 ± 1.1 | 46.7 | 51.4 | 41.20 ± 6.88 |
| kcen | input-kcen | 50.5 ± 1.1 | 48.4 | 53.1 | 42.86 ± 7.15 |
| kcen | input-mattcl | 50.6 ± 1.2 | 48.6 | 54.2 | 42.90 ± 7.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|