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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.8 | 2.1 | 1.03 ± 0.23 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.2 | 1.11 ± 0.25 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 5.1 | 2.37 ± 0.43 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 5.0 | 2.37 ± 0.43 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 6.1 | 2.39 ± 0.47 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 2.39 ± 0.46 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.5 | 13.29 ± 2.29 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.4 | 18.4 | 13.34 ± 2.30 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.5 | 18.8 | 13.35 ± 2.30 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.2 | 18.7 | 13.41 ± 2.32 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.4 | 28.5 | 19.62 ± 3.43 |
| mattcl-py | input-mattcl | 25.6 ± 1.0 | 24.6 | 29.6 | 19.75 ± 3.45 |
| mattcl-py | input-lanjian | 26.0 ± 1.0 | 24.9 | 29.7 | 20.01 ± 3.51 |
| mattcl-py | input-pting | 26.0 ± 0.9 | 24.7 | 29.2 | 20.01 ± 3.50 |
| pting | input-kcen | 26.6 ± 0.8 | 25.6 | 29.7 | 20.50 ± 3.55 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.6 | 30.1 | 20.60 ± 3.58 |
| pting | input-lanjian | 26.8 ± 0.5 | 25.9 | 29.4 | 20.63 ± 3.55 |
| pting | input-pting | 27.1 ± 0.9 | 25.8 | 30.4 | 20.88 ± 3.64 |
| kcen | input-pting | 46.6 ± 0.7 | 45.3 | 48.4 | 35.90 ± 6.16 |
| kcen | input-lanjian | 47.8 ± 1.5 | 46.1 | 56.0 | 36.81 ± 6.39 |
| kcen | input-kcen | 49.7 ± 0.9 | 48.4 | 52.4 | 38.29 ± 6.58 |
| kcen | input-mattcl | 50.5 ± 2.6 | 48.6 | 67.6 | 38.90 ± 6.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|