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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.4 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 2.0 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.22 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.0 | 5.7 | 2.53 ± 0.44 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.6 | 2.54 ± 0.44 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.5 | 2.54 ± 0.45 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.5 | 2.58 ± 0.49 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.2 | 18.3 | 14.46 ± 2.23 |
| mattcl-ts | input-pting | 17.2 ± 0.4 | 16.1 | 18.5 | 14.52 ± 2.24 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.3 | 18.3 | 14.53 ± 2.24 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.4 | 14.65 ± 2.25 |
| mattcl-py | input-kcen | 25.3 ± 1.0 | 24.2 | 30.8 | 21.32 ± 3.36 |
| mattcl-py | input-mattcl | 25.5 ± 0.9 | 24.4 | 28.2 | 21.53 ± 3.36 |
| mattcl-py | input-pting | 26.0 ± 1.0 | 24.9 | 29.0 | 21.88 ± 3.43 |
| mattcl-py | input-lanjian | 26.0 ± 1.0 | 24.9 | 29.5 | 21.95 ± 3.44 |
| pting | input-mattcl | 26.6 ± 0.7 | 25.5 | 29.6 | 22.46 ± 3.47 |
| pting | input-kcen | 26.7 ± 0.8 | 25.6 | 29.9 | 22.52 ± 3.50 |
| pting | input-pting | 27.0 ± 0.8 | 25.9 | 30.1 | 22.72 ± 3.53 |
| pting | input-lanjian | 27.0 ± 1.0 | 26.0 | 34.4 | 22.78 ± 3.57 |
| kcen | input-pting | 46.9 ± 1.0 | 45.7 | 49.7 | 39.49 ± 6.06 |
| kcen | input-lanjian | 47.5 ± 1.0 | 46.0 | 52.2 | 40.03 ± 6.15 |
| kcen | input-kcen | 49.7 ± 0.9 | 48.2 | 52.1 | 41.89 ± 6.42 |
| kcen | input-mattcl | 49.8 ± 1.0 | 48.2 | 52.4 | 41.94 ± 6.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|