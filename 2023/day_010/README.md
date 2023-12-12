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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.4 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.3 | 2.0 | 1.03 ± 0.24 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.4 | 3.7 | 2.49 ± 0.37 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 4.7 | 2.50 ± 0.39 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.4 | 5.7 | 2.54 ± 0.46 |
| lanjian | input-kcen | 3.1 ± 3.1 | 2.2 | 46.4 | 2.57 ± 2.57 |
| mattcl-ts | input-mattcl | 17.0 ± 0.4 | 15.7 | 18.7 | 13.97 ± 1.99 |
| mattcl-ts | input-kcen | 17.1 ± 0.4 | 15.8 | 18.1 | 14.02 ± 1.99 |
| mattcl-ts | input-pting | 17.1 ± 0.4 | 16.2 | 18.5 | 14.05 ± 1.99 |
| mattcl-ts | input-lanjian | 17.3 ± 0.4 | 16.3 | 18.6 | 14.17 ± 2.01 |
| mattcl-py | input-kcen | 25.7 ± 0.8 | 24.2 | 28.5 | 21.09 ± 3.02 |
| mattcl-py | input-mattcl | 25.9 ± 0.8 | 24.8 | 28.9 | 21.31 ± 3.06 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 25.0 | 29.4 | 21.45 ± 3.08 |
| mattcl-py | input-lanjian | 26.3 ± 1.0 | 25.1 | 30.2 | 21.62 ± 3.14 |
| pting | input-kcen | 26.8 ± 0.8 | 25.7 | 30.6 | 22.02 ± 3.15 |
| pting | input-pting | 27.0 ± 0.6 | 26.2 | 29.4 | 22.15 ± 3.14 |
| pting | input-mattcl | 27.0 ± 1.0 | 25.5 | 29.8 | 22.19 ± 3.20 |
| pting | input-lanjian | 27.1 ± 0.9 | 26.0 | 30.2 | 22.29 ± 3.21 |
| kcen | input-pting | 47.4 ± 1.2 | 45.3 | 52.8 | 38.91 ± 5.52 |
| kcen | input-lanjian | 48.6 ± 1.3 | 46.3 | 51.6 | 39.91 ± 5.68 |
| kcen | input-kcen | 50.3 ± 1.2 | 48.2 | 52.8 | 41.30 ± 5.86 |
| kcen | input-mattcl | 50.7 ± 1.2 | 48.6 | 53.3 | 41.63 ± 5.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|