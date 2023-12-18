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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 2.0 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.9 | 2.2 | 1.04 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.5 | 2.1 | 1.04 ± 0.20 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.1 | 2.4 | 1.11 ± 0.21 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 4.0 | 2.29 ± 0.32 |
| lanjian | input-mattcl | 3.2 ± 0.3 | 2.5 | 5.6 | 2.30 ± 0.35 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.5 | 5.7 | 2.31 ± 0.38 |
| lanjian | input-lanjian | 3.2 ± 0.2 | 2.5 | 4.9 | 2.32 ± 0.35 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.7 | 19.0 | 12.85 ± 1.71 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.5 | 18.8 | 12.88 ± 1.71 |
| mattcl-ts | input-pting | 17.9 ± 3.9 | 16.8 | 67.6 | 13.06 ± 3.31 |
| mattcl-ts | input-kcen | 18.1 ± 3.9 | 16.8 | 56.6 | 13.17 ± 3.35 |
| mattcl-py | input-mattcl | 26.0 ± 1.0 | 24.8 | 29.1 | 18.95 ± 2.57 |
| mattcl-py | input-kcen | 26.2 ± 4.8 | 24.4 | 71.2 | 19.12 ± 4.28 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 25.1 | 29.5 | 19.18 ± 2.59 |
| mattcl-py | input-lanjian | 26.5 ± 1.1 | 25.0 | 29.6 | 19.30 ± 2.64 |
| pting | input-kcen | 27.1 ± 0.8 | 25.9 | 29.5 | 19.76 ± 2.65 |
| pting | input-mattcl | 27.2 ± 0.8 | 26.2 | 30.0 | 19.81 ± 2.65 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.3 | 29.9 | 19.92 ± 2.65 |
| pting | input-pting | 27.4 ± 0.9 | 25.8 | 31.7 | 19.96 ± 2.68 |
| kcen | input-pting | 47.6 ± 1.1 | 45.7 | 50.0 | 34.73 ± 4.60 |
| kcen | input-lanjian | 48.3 ± 1.1 | 46.6 | 51.3 | 35.21 ± 4.67 |
| kcen | input-kcen | 50.6 ± 1.4 | 48.8 | 54.8 | 36.87 ± 4.92 |
| kcen | input-mattcl | 50.8 ± 1.2 | 48.9 | 53.9 | 37.02 ± 4.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|