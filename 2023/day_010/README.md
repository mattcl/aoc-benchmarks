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
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.5 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 1.9 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 2.2 | 1.03 ± 0.21 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.7 | 2.28 ± 0.39 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 4.9 | 2.29 ± 0.38 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.5 | 4.1 | 2.29 ± 0.36 |
| lanjian | input-kcen | 3.1 ± 0.4 | 2.8 | 6.0 | 2.30 ± 0.43 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.6 | 19.4 | 12.86 ± 1.88 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.8 | 19.9 | 12.89 ± 1.87 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.5 | 18.8 | 12.90 ± 1.87 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.5 | 21.6 | 12.99 ± 1.91 |
| mattcl-py | input-kcen | 26.0 ± 0.8 | 24.9 | 29.3 | 18.99 ± 2.80 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.7 | 29.3 | 19.12 ± 2.82 |
| mattcl-py | input-lanjian | 26.4 ± 0.8 | 24.8 | 30.0 | 19.30 ± 2.84 |
| mattcl-py | input-pting | 26.5 ± 1.3 | 25.1 | 32.9 | 19.39 ± 2.94 |
| pting | input-kcen | 27.0 ± 0.7 | 26.0 | 29.4 | 19.74 ± 2.88 |
| pting | input-mattcl | 27.1 ± 0.6 | 26.1 | 29.7 | 19.84 ± 2.89 |
| pting | input-pting | 27.5 ± 0.9 | 26.1 | 30.9 | 20.11 ± 2.97 |
| pting | input-lanjian | 27.7 ± 4.0 | 25.8 | 69.3 | 20.26 ± 4.15 |
| kcen | input-pting | 47.5 ± 1.2 | 45.5 | 51.1 | 34.79 ± 5.08 |
| kcen | input-lanjian | 48.6 ± 1.1 | 46.5 | 51.6 | 35.59 ± 5.18 |
| kcen | input-kcen | 51.4 ± 2.2 | 49.4 | 63.1 | 37.58 ± 5.63 |
| kcen | input-mattcl | 51.6 ± 6.1 | 48.5 | 97.2 | 37.73 ± 7.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|