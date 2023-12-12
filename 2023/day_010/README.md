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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.4 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.05 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.24 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 1.7 | 1.10 ± 0.26 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.8 | 2.57 ± 0.52 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 3.6 | 2.59 ± 0.49 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.4 | 3.8 | 2.60 ± 0.50 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.5 | 2.61 ± 0.52 |
| mattcl-ts | input-mattcl | 16.4 ± 0.5 | 15.2 | 17.6 | 14.11 ± 2.61 |
| mattcl-ts | input-pting | 16.5 ± 0.4 | 15.8 | 17.7 | 14.18 ± 2.62 |
| mattcl-ts | input-kcen | 16.6 ± 0.4 | 15.7 | 17.7 | 14.24 ± 2.63 |
| mattcl-ts | input-lanjian | 16.6 ± 0.5 | 15.3 | 18.0 | 14.31 ± 2.65 |
| pting | input-kcen | 26.8 ± 0.8 | 25.6 | 29.4 | 23.10 ± 4.28 |
| pting | input-mattcl | 27.1 ± 0.7 | 26.0 | 29.7 | 23.31 ± 4.31 |
| pting | input-pting | 27.2 ± 0.7 | 26.0 | 29.7 | 23.40 ± 4.32 |
| pting | input-lanjian | 27.5 ± 1.2 | 26.2 | 37.5 | 23.65 ± 4.45 |
| mattcl-py | input-kcen | 36.3 ± 0.9 | 34.9 | 39.6 | 31.23 ± 5.76 |
| mattcl-py | input-mattcl | 37.0 ± 1.0 | 35.4 | 39.7 | 31.85 ± 5.89 |
| mattcl-py | input-lanjian | 37.4 ± 1.1 | 35.5 | 40.3 | 32.16 ± 5.95 |
| mattcl-py | input-pting | 37.5 ± 1.2 | 36.0 | 42.9 | 32.27 ± 5.99 |
| kcen | input-pting | 47.5 ± 1.4 | 45.7 | 53.5 | 40.87 ± 7.56 |
| kcen | input-lanjian | 48.5 ± 1.8 | 46.2 | 57.0 | 41.72 ± 7.78 |
| kcen | input-kcen | 50.6 ± 1.2 | 48.4 | 53.2 | 43.49 ± 8.02 |
| kcen | input-mattcl | 50.6 ± 1.1 | 48.4 | 53.2 | 43.54 ± 8.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|