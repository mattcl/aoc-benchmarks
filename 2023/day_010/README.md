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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.7 | 1.7 | 1.05 ± 0.22 |
| lanjian | input-kcen | 2.9 ± 0.2 | 1.9 | 3.3 | 2.57 ± 0.46 |
| lanjian | input-lanjian | 3.0 ± 0.1 | 2.3 | 3.3 | 2.61 ± 0.45 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.6 | 2.63 ± 0.50 |
| lanjian | input-mattcl | 3.2 ± 3.4 | 2.0 | 50.9 | 2.78 ± 3.01 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.4 | 18.4 | 14.98 ± 2.51 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.2 | 18.4 | 15.02 ± 2.52 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.5 | 18.7 | 15.10 ± 2.53 |
| mattcl-ts | input-lanjian | 17.7 ± 4.0 | 16.4 | 69.3 | 15.46 ± 4.35 |
| mattcl-py | input-kcen | 25.1 ± 0.7 | 24.2 | 29.1 | 21.92 ± 3.70 |
| mattcl-py | input-mattcl | 25.5 ± 0.9 | 24.3 | 29.5 | 22.27 ± 3.78 |
| mattcl-py | input-pting | 26.0 ± 0.8 | 24.6 | 28.8 | 22.66 ± 3.84 |
| mattcl-py | input-lanjian | 26.0 ± 0.8 | 24.8 | 28.9 | 22.67 ± 3.84 |
| pting | input-kcen | 26.4 ± 0.7 | 25.4 | 30.0 | 23.06 ± 3.88 |
| pting | input-mattcl | 26.7 ± 0.9 | 25.6 | 31.0 | 23.28 ± 3.94 |
| pting | input-pting | 26.9 ± 0.9 | 25.7 | 29.7 | 23.45 ± 3.98 |
| pting | input-lanjian | 27.0 ± 0.9 | 25.8 | 29.8 | 23.53 ± 3.99 |
| kcen | input-pting | 47.1 ± 1.3 | 45.4 | 52.8 | 41.08 ± 6.92 |
| kcen | input-lanjian | 47.9 ± 1.2 | 46.3 | 51.8 | 41.80 ± 7.02 |
| kcen | input-kcen | 49.8 ± 1.1 | 48.3 | 53.3 | 43.43 ± 7.28 |
| kcen | input-mattcl | 50.8 ± 4.1 | 48.3 | 80.3 | 44.31 ± 8.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|