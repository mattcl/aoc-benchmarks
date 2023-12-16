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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 1.00 ± 0.21 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.20 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 1.9 | 1.04 ± 0.21 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.5 | 2.34 ± 0.39 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.9 | 6.1 | 2.35 ± 0.42 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.4 | 5.6 | 2.35 ± 0.40 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.4 | 5.7 | 2.36 ± 0.43 |
| mattcl-ts | input-pting | 16.5 ± 0.4 | 15.6 | 17.6 | 12.43 ± 1.82 |
| mattcl-ts | input-mattcl | 16.6 ± 0.5 | 15.7 | 18.1 | 12.45 ± 1.83 |
| mattcl-ts | input-kcen | 16.7 ± 0.5 | 15.4 | 18.2 | 12.51 ± 1.83 |
| mattcl-ts | input-lanjian | 16.8 ± 0.4 | 16.0 | 18.0 | 12.63 ± 1.85 |
| mattcl-py | input-kcen | 26.0 ± 0.8 | 24.7 | 29.6 | 19.50 ± 2.88 |
| mattcl-py | input-mattcl | 26.1 ± 0.7 | 24.8 | 29.4 | 19.63 ± 2.88 |
| mattcl-py | input-pting | 26.4 ± 0.8 | 25.2 | 30.0 | 19.80 ± 2.91 |
| mattcl-py | input-lanjian | 26.6 ± 0.9 | 25.3 | 30.1 | 19.99 ± 2.96 |
| pting | input-kcen | 27.3 ± 1.2 | 26.1 | 37.1 | 20.48 ± 3.09 |
| pting | input-lanjian | 27.5 ± 0.7 | 26.2 | 30.5 | 20.64 ± 3.02 |
| pting | input-mattcl | 27.5 ± 0.8 | 26.3 | 30.5 | 20.66 ± 3.04 |
| pting | input-pting | 27.6 ± 0.9 | 26.2 | 31.1 | 20.72 ± 3.07 |
| kcen | input-pting | 47.9 ± 1.3 | 46.1 | 51.3 | 36.00 ± 5.28 |
| kcen | input-lanjian | 49.1 ± 5.3 | 46.8 | 89.5 | 36.84 ± 6.64 |
| kcen | input-mattcl | 50.6 ± 1.0 | 48.7 | 53.4 | 37.96 ± 5.52 |
| kcen | input-kcen | 51.0 ± 2.0 | 49.1 | 62.2 | 38.27 ± 5.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|