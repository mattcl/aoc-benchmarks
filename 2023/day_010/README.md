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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.04 ± 0.22 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.6 | 2.55 ± 0.44 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.9 | 2.57 ± 0.47 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.6 | 2.57 ± 0.47 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.9 | 2.59 ± 0.49 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.3 | 18.2 | 14.55 ± 2.23 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.6 | 14.58 ± 2.23 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.4 | 18.3 | 14.66 ± 2.24 |
| mattcl-ts | input-lanjian | 17.5 ± 2.2 | 16.4 | 45.3 | 14.81 ± 2.90 |
| mattcl-py | input-kcen | 25.5 ± 0.8 | 24.4 | 28.5 | 21.50 ± 3.33 |
| mattcl-py | input-mattcl | 25.9 ± 0.9 | 24.7 | 30.2 | 21.85 ± 3.39 |
| mattcl-py | input-pting | 26.2 ± 0.8 | 25.1 | 28.8 | 22.10 ± 3.42 |
| mattcl-py | input-lanjian | 26.2 ± 0.8 | 25.1 | 29.0 | 22.11 ± 3.42 |
| pting | input-kcen | 26.7 ± 0.9 | 25.4 | 29.4 | 22.52 ± 3.49 |
| pting | input-mattcl | 26.8 ± 0.7 | 26.0 | 30.0 | 22.65 ± 3.49 |
| pting | input-lanjian | 27.0 ± 2.4 | 25.3 | 50.6 | 22.83 ± 3.99 |
| pting | input-pting | 27.1 ± 0.7 | 26.0 | 30.0 | 22.86 ± 3.52 |
| kcen | input-pting | 47.3 ± 1.4 | 45.5 | 52.6 | 39.97 ± 6.16 |
| kcen | input-lanjian | 47.7 ± 0.9 | 46.2 | 50.5 | 40.29 ± 6.16 |
| kcen | input-kcen | 49.9 ± 1.0 | 48.6 | 52.6 | 42.14 ± 6.44 |
| kcen | input-mattcl | 50.0 ± 1.1 | 48.4 | 53.3 | 42.27 ± 6.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|