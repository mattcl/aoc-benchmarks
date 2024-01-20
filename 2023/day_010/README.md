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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.9 | 1.00 ± 0.22 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.1 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 3.6 | 2.36 ± 0.39 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 4.8 | 2.37 ± 0.40 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.3 | 3.9 | 2.38 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.8 | 2.39 ± 0.44 |
| mattcl-ts | input-mattcl | 16.7 ± 0.4 | 15.8 | 17.8 | 13.00 ± 2.07 |
| mattcl-ts | input-kcen | 16.8 ± 0.4 | 15.9 | 17.7 | 13.03 ± 2.08 |
| mattcl-ts | input-pting | 16.9 ± 0.4 | 15.9 | 18.0 | 13.10 ± 2.09 |
| mattcl-ts | input-lanjian | 16.9 ± 0.4 | 15.9 | 18.4 | 13.13 ± 2.10 |
| mattcl-py | input-kcen | 25.4 ± 0.8 | 24.2 | 28.6 | 19.71 ± 3.17 |
| mattcl-py | input-mattcl | 25.5 ± 0.7 | 24.7 | 28.5 | 19.81 ± 3.17 |
| mattcl-py | input-lanjian | 25.9 ± 0.7 | 24.7 | 28.0 | 20.10 ± 3.21 |
| mattcl-py | input-pting | 26.1 ± 0.9 | 24.9 | 28.9 | 20.26 ± 3.26 |
| pting | input-kcen | 26.5 ± 0.7 | 25.6 | 29.9 | 20.62 ± 3.29 |
| pting | input-mattcl | 26.7 ± 0.8 | 25.7 | 32.2 | 20.72 ± 3.33 |
| pting | input-lanjian | 27.0 ± 0.7 | 25.9 | 29.4 | 20.98 ± 3.35 |
| pting | input-pting | 27.0 ± 0.9 | 26.0 | 29.9 | 21.01 ± 3.38 |
| kcen | input-pting | 47.4 ± 1.0 | 45.8 | 49.5 | 36.84 ± 5.86 |
| kcen | input-lanjian | 47.9 ± 1.1 | 46.3 | 52.1 | 37.19 ± 5.92 |
| kcen | input-kcen | 50.1 ± 1.1 | 48.3 | 53.1 | 38.93 ± 6.20 |
| kcen | input-mattcl | 50.3 ± 1.3 | 48.3 | 54.1 | 39.08 ± 6.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|