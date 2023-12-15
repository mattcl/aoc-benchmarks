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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.2 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.5 | 2.1 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.05 ± 0.21 |
| mattcl | input-pting | 1.4 ± 0.2 | 1.1 | 2.2 | 1.05 ± 0.20 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 3.7 | 2.30 ± 0.35 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 3.9 | 2.32 ± 0.36 |
| lanjian | input-lanjian | 3.2 ± 0.3 | 2.5 | 6.0 | 2.34 ± 0.39 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.4 | 5.6 | 2.35 ± 0.41 |
| mattcl-ts | input-mattcl | 17.7 ± 0.4 | 16.8 | 18.8 | 13.10 ± 1.88 |
| mattcl-ts | input-kcen | 17.7 ± 0.5 | 16.6 | 19.3 | 13.11 ± 1.89 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.6 | 18.7 | 13.11 ± 1.88 |
| mattcl-ts | input-lanjian | 17.9 ± 0.5 | 16.5 | 19.2 | 13.26 ± 1.91 |
| mattcl-py | input-kcen | 25.9 ± 0.8 | 24.9 | 28.9 | 19.23 ± 2.79 |
| mattcl-py | input-mattcl | 26.0 ± 0.8 | 24.8 | 28.9 | 19.28 ± 2.80 |
| mattcl-py | input-pting | 26.3 ± 0.8 | 25.0 | 29.5 | 19.48 ± 2.81 |
| mattcl-py | input-lanjian | 26.5 ± 0.9 | 25.4 | 29.5 | 19.62 ± 2.85 |
| pting | input-mattcl | 27.2 ± 0.9 | 25.9 | 30.2 | 20.13 ± 2.92 |
| pting | input-kcen | 27.3 ± 1.0 | 25.9 | 30.5 | 20.21 ± 2.95 |
| pting | input-pting | 27.4 ± 0.8 | 26.2 | 30.5 | 20.27 ± 2.93 |
| pting | input-lanjian | 27.4 ± 0.8 | 26.3 | 30.7 | 20.28 ± 2.94 |
| kcen | input-pting | 47.5 ± 1.2 | 45.6 | 52.3 | 35.17 ± 5.06 |
| kcen | input-lanjian | 48.7 ± 1.3 | 46.0 | 51.3 | 36.08 ± 5.19 |
| kcen | input-kcen | 50.5 ± 1.0 | 48.5 | 53.3 | 37.45 ± 5.35 |
| kcen | input-mattcl | 50.7 ± 2.0 | 48.3 | 61.5 | 37.54 ± 5.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|