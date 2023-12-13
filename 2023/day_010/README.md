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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.18 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.3 | 1.05 ± 0.23 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 5.6 | 2.53 ± 0.41 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.8 | 2.55 ± 0.45 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.9 | 2.55 ± 0.47 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.7 | 2.55 ± 0.46 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.4 | 18.5 | 14.41 ± 2.11 |
| mattcl-ts | input-kcen | 17.3 ± 0.5 | 16.3 | 19.8 | 14.43 ± 2.13 |
| mattcl-ts | input-pting | 17.3 ± 0.3 | 16.5 | 18.5 | 14.44 ± 2.11 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.6 | 14.54 ± 2.14 |
| mattcl-py | input-kcen | 25.5 ± 0.8 | 24.5 | 28.8 | 21.22 ± 3.15 |
| mattcl-py | input-mattcl | 25.7 ± 0.8 | 24.5 | 29.4 | 21.39 ± 3.18 |
| mattcl-py | input-lanjian | 26.1 ± 0.9 | 24.8 | 29.1 | 21.71 ± 3.24 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 24.9 | 30.5 | 21.74 ± 3.25 |
| pting | input-kcen | 26.6 ± 0.9 | 25.6 | 30.2 | 22.13 ± 3.29 |
| pting | input-pting | 27.0 ± 0.7 | 26.0 | 29.8 | 22.46 ± 3.30 |
| pting | input-lanjian | 27.0 ± 0.8 | 25.9 | 30.0 | 22.47 ± 3.32 |
| pting | input-mattcl | 27.0 ± 0.9 | 25.9 | 29.7 | 22.50 ± 3.34 |
| kcen | input-pting | 47.4 ± 1.1 | 46.0 | 51.2 | 39.48 ± 5.79 |
| kcen | input-lanjian | 48.0 ± 1.1 | 46.4 | 52.2 | 39.99 ± 5.87 |
| kcen | input-kcen | 50.1 ± 0.9 | 48.3 | 52.8 | 41.76 ± 6.10 |
| kcen | input-mattcl | 50.5 ± 2.1 | 48.4 | 63.5 | 42.08 ± 6.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|