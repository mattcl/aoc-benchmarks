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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.4 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.4 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.9 | 1.02 ± 0.23 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.2 | 4.7 | 2.55 ± 0.43 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 5.5 | 2.56 ± 0.45 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 5.7 | 2.57 ± 0.45 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.5 | 2.57 ± 0.47 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.3 | 18.6 | 14.78 ± 2.31 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.0 | 18.3 | 14.78 ± 2.31 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.6 | 19.1 | 14.86 ± 2.33 |
| mattcl-ts | input-mattcl | 17.6 ± 4.3 | 16.1 | 73.7 | 15.04 ± 4.39 |
| mattcl-py | input-kcen | 25.6 ± 0.9 | 24.3 | 29.3 | 21.86 ± 3.47 |
| mattcl-py | input-pting | 26.0 ± 0.7 | 25.1 | 28.6 | 22.21 ± 3.48 |
| mattcl-py | input-mattcl | 26.0 ± 2.9 | 24.6 | 56.2 | 22.28 ± 4.25 |
| mattcl-py | input-lanjian | 26.1 ± 0.9 | 25.1 | 29.7 | 22.31 ± 3.54 |
| pting | input-kcen | 26.4 ± 0.6 | 25.6 | 29.1 | 22.61 ± 3.54 |
| pting | input-mattcl | 26.8 ± 0.7 | 25.6 | 29.3 | 22.96 ± 3.60 |
| pting | input-lanjian | 27.0 ± 0.8 | 26.0 | 30.4 | 23.05 ± 3.63 |
| pting | input-pting | 27.0 ± 0.8 | 25.7 | 30.0 | 23.13 ± 3.64 |
| kcen | input-pting | 47.3 ± 1.1 | 45.6 | 52.1 | 40.43 ± 6.33 |
| kcen | input-lanjian | 47.9 ± 1.4 | 46.3 | 55.6 | 40.99 ± 6.45 |
| kcen | input-mattcl | 49.9 ± 1.1 | 48.3 | 53.7 | 42.70 ± 6.68 |
| kcen | input-kcen | 50.2 ± 1.4 | 48.3 | 55.9 | 42.90 ± 6.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|