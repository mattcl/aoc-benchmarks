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
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.1 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.7 | 2.32 ± 0.38 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.6 | 2.34 ± 0.41 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.5 | 2.35 ± 0.41 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.3 | 5.7 | 2.37 ± 0.44 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.5 | 18.9 | 13.60 ± 2.02 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.7 | 18.6 | 13.62 ± 2.01 |
| mattcl-ts | input-lanjian | 17.6 ± 0.4 | 16.7 | 18.9 | 13.70 ± 2.03 |
| mattcl-ts | input-pting | 18.1 ± 4.9 | 16.7 | 68.1 | 14.06 ± 4.30 |
| mattcl-py | input-kcen | 25.8 ± 1.0 | 24.3 | 28.8 | 20.02 ± 3.04 |
| mattcl-py | input-mattcl | 25.9 ± 1.0 | 24.6 | 28.8 | 20.11 ± 3.04 |
| mattcl-py | input-pting | 26.1 ± 1.1 | 24.9 | 32.6 | 20.28 ± 3.09 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 25.0 | 30.0 | 20.32 ± 3.05 |
| pting | input-kcen | 27.0 ± 0.9 | 25.7 | 30.1 | 21.00 ± 3.14 |
| pting | input-mattcl | 27.1 ± 0.9 | 26.0 | 30.9 | 21.06 ± 3.15 |
| pting | input-pting | 27.3 ± 0.8 | 26.2 | 29.8 | 21.19 ± 3.16 |
| pting | input-lanjian | 27.3 ± 0.8 | 26.2 | 30.2 | 21.24 ± 3.16 |
| kcen | input-pting | 47.3 ± 1.3 | 45.1 | 50.6 | 36.74 ± 5.46 |
| kcen | input-lanjian | 48.1 ± 1.3 | 46.0 | 51.1 | 37.36 ± 5.55 |
| kcen | input-mattcl | 50.4 ± 1.2 | 48.2 | 54.7 | 39.16 ± 5.80 |
| kcen | input-kcen | 50.7 ± 1.2 | 48.5 | 53.9 | 39.41 ± 5.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|