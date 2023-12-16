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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.9 | 1.8 | 1.04 ± 0.19 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.1 | 1.05 ± 0.20 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.3 | 4.8 | 2.38 ± 0.37 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.7 | 2.39 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.8 | 2.40 ± 0.41 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.9 | 2.42 ± 0.43 |
| mattcl-ts | input-mattcl | 16.8 ± 0.4 | 15.8 | 18.1 | 13.19 ± 1.83 |
| mattcl-ts | input-pting | 16.8 ± 0.4 | 15.9 | 18.1 | 13.22 ± 1.83 |
| mattcl-ts | input-kcen | 16.9 ± 0.4 | 15.7 | 17.9 | 13.24 ± 1.83 |
| mattcl-ts | input-lanjian | 17.0 ± 0.5 | 15.6 | 18.4 | 13.39 ± 1.86 |
| mattcl-py | input-kcen | 25.8 ± 0.7 | 24.7 | 28.8 | 20.30 ± 2.83 |
| mattcl-py | input-mattcl | 26.2 ± 1.3 | 24.7 | 37.3 | 20.58 ± 2.98 |
| mattcl-py | input-pting | 26.4 ± 1.0 | 25.0 | 29.9 | 20.74 ± 2.93 |
| mattcl-py | input-lanjian | 27.0 ± 3.0 | 25.4 | 51.9 | 21.18 ± 3.74 |
| pting | input-kcen | 27.1 ± 0.8 | 25.7 | 30.0 | 21.30 ± 2.97 |
| pting | input-mattcl | 27.1 ± 0.7 | 25.6 | 29.9 | 21.30 ± 2.95 |
| pting | input-pting | 27.4 ± 0.8 | 26.1 | 30.3 | 21.54 ± 2.99 |
| pting | input-lanjian | 27.5 ± 0.8 | 26.1 | 30.5 | 21.59 ± 3.01 |
| kcen | input-pting | 47.4 ± 1.2 | 45.5 | 50.4 | 37.28 ± 5.16 |
| kcen | input-lanjian | 49.6 ± 4.6 | 46.5 | 75.8 | 38.96 ± 6.42 |
| kcen | input-mattcl | 50.6 ± 1.2 | 48.8 | 54.1 | 39.75 ± 5.49 |
| kcen | input-kcen | 50.8 ± 1.2 | 49.0 | 55.1 | 39.92 ± 5.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|