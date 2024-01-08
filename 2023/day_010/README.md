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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.00 ± 0.23 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.23 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.6 | 2.41 ± 0.46 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.7 | 2.41 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 6.1 | 2.43 ± 0.49 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 5.7 | 2.44 ± 0.47 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.1 | 18.7 | 13.68 ± 2.24 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.4 | 18.6 | 13.68 ± 2.24 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.4 | 18.5 | 13.73 ± 2.24 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.4 | 18.5 | 13.80 ± 2.26 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.1 | 28.4 | 20.19 ± 3.34 |
| mattcl-py | input-mattcl | 25.9 ± 1.0 | 24.5 | 28.5 | 20.53 ± 3.41 |
| mattcl-py | input-lanjian | 26.0 ± 0.9 | 24.9 | 29.0 | 20.63 ± 3.41 |
| mattcl-py | input-pting | 26.1 ± 2.1 | 24.5 | 47.0 | 20.68 ± 3.74 |
| pting | input-kcen | 26.7 ± 1.0 | 25.5 | 30.2 | 21.17 ± 3.51 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.7 | 29.5 | 21.29 ± 3.50 |
| pting | input-pting | 27.0 ± 0.8 | 25.9 | 29.8 | 21.42 ± 3.53 |
| pting | input-lanjian | 27.2 ± 1.0 | 25.9 | 32.6 | 21.54 ± 3.58 |
| kcen | input-lanjian | 47.9 ± 1.2 | 46.2 | 52.0 | 38.01 ± 6.23 |
| kcen | input-pting | 48.6 ± 5.9 | 45.5 | 88.8 | 38.53 ± 7.78 |
| kcen | input-kcen | 50.0 ± 0.9 | 48.6 | 52.2 | 39.69 ± 6.46 |
| kcen | input-mattcl | 50.1 ± 1.0 | 48.1 | 52.5 | 39.70 ± 6.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|