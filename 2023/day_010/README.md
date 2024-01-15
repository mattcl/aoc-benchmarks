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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.21 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.9 | 1.04 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 4.7 | 2.46 ± 0.41 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.8 | 2.46 ± 0.45 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 5.6 | 2.46 ± 0.41 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.3 | 5.6 | 2.46 ± 0.41 |
| mattcl-ts | input-kcen | 16.0 ± 0.4 | 14.9 | 17.1 | 13.04 ± 2.00 |
| mattcl-ts | input-mattcl | 16.0 ± 0.4 | 14.9 | 17.1 | 13.05 ± 2.01 |
| mattcl-ts | input-pting | 16.0 ± 0.4 | 14.9 | 16.9 | 13.05 ± 2.00 |
| mattcl-ts | input-lanjian | 16.2 ± 0.4 | 15.1 | 17.6 | 13.17 ± 2.03 |
| mattcl-py | input-kcen | 25.2 ± 0.6 | 23.8 | 28.3 | 20.56 ± 3.16 |
| mattcl-py | input-mattcl | 25.4 ± 0.7 | 24.3 | 28.5 | 20.75 ± 3.20 |
| mattcl-py | input-lanjian | 25.8 ± 0.8 | 24.6 | 28.8 | 21.07 ± 3.26 |
| mattcl-py | input-pting | 25.9 ± 0.8 | 24.7 | 29.6 | 21.11 ± 3.26 |
| pting | input-kcen | 26.4 ± 0.7 | 25.4 | 29.6 | 21.53 ± 3.31 |
| pting | input-mattcl | 26.6 ± 0.9 | 25.6 | 30.0 | 21.67 ± 3.35 |
| pting | input-lanjian | 26.6 ± 0.8 | 25.6 | 30.0 | 21.68 ± 3.34 |
| pting | input-pting | 26.8 ± 0.8 | 25.7 | 29.8 | 21.86 ± 3.38 |
| kcen | input-pting | 47.0 ± 1.2 | 45.3 | 49.5 | 38.31 ± 5.88 |
| kcen | input-lanjian | 47.8 ± 1.1 | 46.3 | 52.9 | 39.00 ± 5.97 |
| kcen | input-kcen | 50.1 ± 1.0 | 48.4 | 52.9 | 40.84 ± 6.24 |
| kcen | input-mattcl | 50.2 ± 1.6 | 48.2 | 59.3 | 40.89 ± 6.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|