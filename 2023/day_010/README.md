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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.4 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 2.0 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.9 | 1.04 ± 0.23 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.1 | 5.7 | 2.55 ± 0.49 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.8 | 2.56 ± 0.48 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.7 | 2.58 ± 0.51 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.7 | 6.0 | 2.61 ± 0.53 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.3 | 19.0 | 14.98 ± 2.62 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.5 | 18.8 | 14.99 ± 2.62 |
| mattcl-ts | input-mattcl | 17.5 ± 0.5 | 16.5 | 19.0 | 15.00 ± 2.62 |
| mattcl-ts | input-lanjian | 17.6 ± 0.4 | 16.6 | 18.7 | 15.05 ± 2.62 |
| mattcl-py | input-kcen | 25.9 ± 1.0 | 24.4 | 29.7 | 22.13 ± 3.93 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.9 | 29.1 | 22.25 ± 3.93 |
| mattcl-py | input-lanjian | 26.2 ± 0.8 | 24.7 | 29.8 | 22.42 ± 3.94 |
| mattcl-py | input-pting | 26.3 ± 1.0 | 24.9 | 29.5 | 22.50 ± 3.98 |
| pting | input-kcen | 26.8 ± 0.9 | 25.4 | 29.5 | 22.99 ± 4.04 |
| pting | input-mattcl | 26.9 ± 1.0 | 25.7 | 32.9 | 23.07 ± 4.07 |
| pting | input-pting | 27.0 ± 0.7 | 25.6 | 29.5 | 23.12 ± 4.04 |
| pting | input-lanjian | 27.1 ± 0.8 | 25.8 | 30.2 | 23.19 ± 4.06 |
| kcen | input-pting | 47.5 ± 1.8 | 45.2 | 58.9 | 40.67 ± 7.21 |
| kcen | input-lanjian | 48.0 ± 0.9 | 46.6 | 50.5 | 41.12 ± 7.16 |
| kcen | input-mattcl | 50.1 ± 1.2 | 48.0 | 53.3 | 42.89 ± 7.49 |
| kcen | input-kcen | 50.2 ± 1.0 | 48.1 | 52.9 | 42.97 ± 7.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|