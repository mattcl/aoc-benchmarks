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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.5 | 1.6 | 1.00 ± 0.21 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.2 | 1.04 ± 0.23 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 2.2 | 1.05 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.26 ± 0.41 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.3 | 2.27 ± 0.41 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.7 | 2.27 ± 0.42 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 6.0 | 2.29 ± 0.43 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.4 | 18.5 | 12.79 ± 2.06 |
| mattcl-ts | input-mattcl | 17.4 ± 0.4 | 16.4 | 18.6 | 12.81 ± 2.07 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.7 | 18.6 | 12.88 ± 2.08 |
| mattcl-ts | input-lanjian | 17.6 ± 0.4 | 16.6 | 18.7 | 13.00 ± 2.10 |
| mattcl-py | input-kcen | 25.8 ± 0.9 | 24.4 | 29.0 | 19.01 ± 3.12 |
| mattcl-py | input-mattcl | 25.8 ± 0.8 | 24.4 | 29.0 | 19.06 ± 3.10 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 24.3 | 30.0 | 19.36 ± 3.17 |
| mattcl-py | input-pting | 26.3 ± 1.0 | 24.8 | 29.6 | 19.38 ± 3.18 |
| pting | input-kcen | 27.1 ± 0.9 | 26.1 | 30.0 | 20.00 ± 3.26 |
| pting | input-pting | 27.2 ± 0.7 | 26.1 | 30.2 | 20.07 ± 3.25 |
| pting | input-mattcl | 27.2 ± 0.6 | 26.0 | 30.0 | 20.07 ± 3.24 |
| pting | input-lanjian | 27.3 ± 0.9 | 26.0 | 30.1 | 20.14 ± 3.29 |
| kcen | input-pting | 47.5 ± 1.1 | 45.8 | 50.1 | 35.06 ± 5.66 |
| kcen | input-lanjian | 48.5 ± 1.2 | 46.4 | 51.4 | 35.77 ± 5.78 |
| kcen | input-kcen | 50.4 ± 1.0 | 48.3 | 53.8 | 37.19 ± 5.99 |
| kcen | input-mattcl | 50.4 ± 1.3 | 48.5 | 54.3 | 37.20 ± 6.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|