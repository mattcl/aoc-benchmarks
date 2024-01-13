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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 3.6 | 2.37 ± 0.38 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 4.8 | 2.39 ± 0.41 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.6 | 2.40 ± 0.44 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 6.2 | 2.40 ± 0.46 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.1 | 18.4 | 13.64 ± 2.09 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.4 | 13.67 ± 2.09 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.2 | 18.6 | 13.68 ± 2.09 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.4 | 18.7 | 13.79 ± 2.11 |
| mattcl-py | input-kcen | 25.4 ± 0.7 | 24.4 | 28.5 | 20.06 ± 3.09 |
| mattcl-py | input-mattcl | 25.6 ± 0.8 | 24.4 | 28.9 | 20.22 ± 3.12 |
| mattcl-py | input-pting | 25.9 ± 0.9 | 24.8 | 29.1 | 20.48 ± 3.17 |
| mattcl-py | input-lanjian | 25.9 ± 0.7 | 25.0 | 28.9 | 20.49 ± 3.15 |
| pting | input-kcen | 26.6 ± 0.8 | 25.6 | 30.5 | 21.04 ± 3.25 |
| pting | input-mattcl | 26.8 ± 0.6 | 25.7 | 29.6 | 21.17 ± 3.24 |
| pting | input-lanjian | 26.9 ± 0.7 | 26.1 | 29.4 | 21.29 ± 3.26 |
| pting | input-pting | 27.0 ± 0.8 | 25.8 | 29.9 | 21.31 ± 3.28 |
| kcen | input-pting | 47.0 ± 1.0 | 45.7 | 50.2 | 37.15 ± 5.67 |
| kcen | input-lanjian | 48.3 ± 1.4 | 46.3 | 52.5 | 38.16 ± 5.87 |
| kcen | input-mattcl | 50.3 ± 1.7 | 48.3 | 60.5 | 39.77 ± 6.15 |
| kcen | input-kcen | 50.5 ± 2.5 | 48.6 | 68.1 | 39.87 ± 6.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|