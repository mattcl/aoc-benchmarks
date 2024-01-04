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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.0 | 1.05 ± 0.24 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.06 ± 0.24 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.07 ± 0.25 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 6.0 | 2.41 ± 0.49 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.6 | 2.42 ± 0.48 |
| lanjian | input-kcen | 3.0 ± 0.4 | 2.2 | 5.7 | 2.44 ± 0.54 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.3 | 5.7 | 2.45 ± 0.52 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.7 | 19.5 | 14.00 ± 2.48 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.7 | 18.8 | 14.11 ± 2.50 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.7 | 18.7 | 14.12 ± 2.50 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.9 | 19.0 | 14.22 ± 2.52 |
| mattcl-py | input-kcen | 25.8 ± 1.0 | 24.1 | 29.3 | 20.71 ± 3.72 |
| mattcl-py | input-mattcl | 25.8 ± 1.0 | 24.3 | 29.0 | 20.72 ± 3.72 |
| mattcl-py | input-lanjian | 26.0 ± 0.8 | 24.8 | 28.8 | 20.87 ± 3.71 |
| mattcl-py | input-pting | 26.1 ± 0.8 | 24.9 | 29.2 | 20.92 ± 3.73 |
| pting | input-kcen | 27.1 ± 0.8 | 25.9 | 30.2 | 21.69 ± 3.86 |
| pting | input-mattcl | 27.2 ± 0.8 | 25.7 | 30.1 | 21.79 ± 3.87 |
| pting | input-lanjian | 27.2 ± 0.8 | 25.6 | 30.0 | 21.81 ± 3.88 |
| pting | input-pting | 27.5 ± 1.0 | 26.0 | 30.7 | 22.04 ± 3.95 |
| kcen | input-pting | 47.9 ± 3.8 | 44.8 | 75.2 | 38.40 ± 7.41 |
| kcen | input-lanjian | 48.3 ± 1.3 | 46.4 | 51.9 | 38.75 ± 6.88 |
| kcen | input-kcen | 50.0 ± 1.1 | 48.3 | 53.4 | 40.06 ± 7.08 |
| kcen | input-mattcl | 50.4 ± 1.0 | 48.7 | 52.4 | 40.43 ± 7.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|