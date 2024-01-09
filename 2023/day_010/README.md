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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.5 | 1.9 | 1.00 ± 0.19 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 1.9 | 1.01 ± 0.19 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.3 | 1.02 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 4.9 | 2.18 ± 0.33 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 3.8 | 2.19 ± 0.32 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.4 | 5.7 | 2.21 ± 0.37 |
| lanjian | input-lanjian | 3.2 ± 0.3 | 2.5 | 5.8 | 2.23 ± 0.38 |
| mattcl-ts | input-mattcl | 17.7 ± 0.4 | 16.4 | 18.9 | 12.28 ± 1.70 |
| mattcl-ts | input-kcen | 17.7 ± 0.4 | 16.5 | 19.3 | 12.31 ± 1.70 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.8 | 18.8 | 12.32 ± 1.70 |
| mattcl-ts | input-lanjian | 18.1 ± 3.0 | 16.7 | 55.7 | 12.61 ± 2.70 |
| mattcl-py | input-kcen | 25.9 ± 1.0 | 24.5 | 29.4 | 18.03 ± 2.56 |
| mattcl-py | input-mattcl | 26.0 ± 1.0 | 24.8 | 30.0 | 18.07 ± 2.55 |
| mattcl-py | input-lanjian | 26.3 ± 0.8 | 25.2 | 30.3 | 18.27 ± 2.55 |
| mattcl-py | input-pting | 26.5 ± 1.1 | 24.9 | 30.4 | 18.47 ± 2.63 |
| pting | input-lanjian | 27.3 ± 0.5 | 26.4 | 29.5 | 18.98 ± 2.61 |
| pting | input-kcen | 27.4 ± 1.0 | 25.8 | 30.1 | 19.04 ± 2.68 |
| pting | input-pting | 27.4 ± 0.7 | 26.2 | 30.6 | 19.08 ± 2.64 |
| pting | input-mattcl | 27.5 ± 1.1 | 25.6 | 33.2 | 19.12 ± 2.72 |
| kcen | input-pting | 47.6 ± 1.2 | 45.2 | 52.4 | 33.13 ± 4.59 |
| kcen | input-lanjian | 49.5 ± 3.9 | 47.3 | 75.2 | 34.42 ± 5.43 |
| kcen | input-mattcl | 50.5 ± 1.2 | 48.9 | 54.2 | 35.13 ± 4.86 |
| kcen | input-kcen | 50.9 ± 1.4 | 48.4 | 55.4 | 35.37 ± 4.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|