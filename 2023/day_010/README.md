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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-pting | 1.5 ± 0.2 | 0.8 | 2.4 | 1.08 ± 0.23 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.3 | 1.09 ± 0.23 |
| mattcl | input-lanjian | 1.5 ± 3.5 | 0.4 | 50.0 | 1.11 ± 2.58 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 5.7 | 2.29 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.5 | 5.8 | 2.31 ± 0.43 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 5.7 | 2.32 ± 0.43 |
| lanjian | input-mattcl | 3.3 ± 3.6 | 2.2 | 53.1 | 2.44 ± 2.66 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.7 | 18.7 | 13.03 ± 2.00 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.5 | 18.7 | 13.07 ± 2.00 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.7 | 18.8 | 13.08 ± 2.01 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.6 | 19.2 | 13.19 ± 2.03 |
| mattcl-py | input-kcen | 25.8 ± 0.9 | 24.5 | 29.2 | 19.16 ± 2.98 |
| mattcl-py | input-mattcl | 26.2 ± 0.8 | 24.6 | 28.8 | 19.43 ± 3.01 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 24.6 | 29.7 | 19.52 ± 3.04 |
| mattcl-py | input-lanjian | 26.3 ± 0.8 | 25.1 | 28.7 | 19.53 ± 3.02 |
| pting | input-kcen | 27.0 ± 0.8 | 25.5 | 30.3 | 20.03 ± 3.10 |
| pting | input-mattcl | 27.1 ± 0.7 | 25.5 | 29.5 | 20.14 ± 3.10 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.2 | 29.5 | 20.27 ± 3.12 |
| pting | input-pting | 27.3 ± 0.8 | 26.1 | 30.2 | 20.28 ± 3.13 |
| kcen | input-pting | 47.5 ± 1.1 | 45.7 | 51.4 | 35.26 ± 5.41 |
| kcen | input-lanjian | 48.6 ± 1.1 | 46.9 | 51.4 | 36.06 ± 5.53 |
| kcen | input-mattcl | 50.4 ± 1.0 | 48.9 | 52.6 | 37.44 ± 5.73 |
| kcen | input-kcen | 50.7 ± 1.2 | 48.7 | 53.8 | 37.64 ± 5.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|