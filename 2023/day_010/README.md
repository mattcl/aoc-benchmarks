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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.8 | 1.01 ± 0.20 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.18 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 5.5 | 2.41 ± 0.35 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.7 | 2.42 ± 0.39 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.8 | 2.43 ± 0.38 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.2 | 6.1 | 2.44 ± 0.44 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.2 | 18.8 | 13.86 ± 1.77 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.7 | 18.5 | 13.90 ± 1.78 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.4 | 19.4 | 13.91 ± 1.78 |
| mattcl-ts | input-lanjian | 17.6 ± 0.5 | 16.3 | 18.8 | 13.96 ± 1.80 |
| mattcl-py | input-kcen | 25.8 ± 0.7 | 24.8 | 28.8 | 20.45 ± 2.64 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.9 | 29.3 | 20.58 ± 2.68 |
| mattcl-py | input-lanjian | 26.4 ± 0.8 | 25.2 | 29.5 | 20.89 ± 2.71 |
| mattcl-py | input-pting | 26.5 ± 0.8 | 25.1 | 29.4 | 20.95 ± 2.71 |
| pting | input-kcen | 27.0 ± 0.8 | 25.7 | 29.8 | 21.36 ± 2.75 |
| pting | input-mattcl | 27.0 ± 0.6 | 26.0 | 29.8 | 21.41 ± 2.73 |
| pting | input-pting | 27.3 ± 0.8 | 25.8 | 30.1 | 21.61 ± 2.79 |
| pting | input-lanjian | 28.1 ± 5.8 | 26.2 | 74.3 | 22.29 ± 5.38 |
| kcen | input-pting | 47.3 ± 0.8 | 45.7 | 49.5 | 37.44 ± 4.75 |
| kcen | input-lanjian | 48.7 ± 1.1 | 46.6 | 51.2 | 38.55 ± 4.92 |
| kcen | input-mattcl | 50.5 ± 1.5 | 48.5 | 57.5 | 40.04 ± 5.18 |
| kcen | input-kcen | 50.7 ± 1.4 | 48.4 | 53.8 | 40.15 ± 5.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|