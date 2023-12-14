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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.1 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.1 | 1.05 ± 0.21 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.6 | 2.3 | 1.08 ± 0.25 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.7 | 5.7 | 2.42 ± 0.42 |
| lanjian | input-mattcl | 3.2 ± 0.3 | 2.4 | 5.7 | 2.43 ± 0.43 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.7 | 5.7 | 2.44 ± 0.44 |
| lanjian | input-lanjian | 3.2 ± 0.3 | 2.5 | 4.8 | 2.45 ± 0.41 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.4 | 18.6 | 13.50 ± 1.99 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.3 | 18.9 | 13.57 ± 2.00 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.8 | 19.1 | 13.60 ± 2.01 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.7 | 19.1 | 13.73 ± 2.03 |
| mattcl-py | input-kcen | 25.9 ± 1.0 | 24.4 | 28.9 | 20.03 ± 3.02 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.4 | 29.6 | 20.16 ± 3.02 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 25.2 | 29.8 | 20.32 ± 3.03 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.0 | 29.3 | 20.40 ± 3.05 |
| pting | input-kcen | 26.9 ± 0.6 | 25.8 | 29.3 | 20.82 ± 3.07 |
| pting | input-mattcl | 27.2 ± 0.9 | 26.0 | 30.0 | 21.04 ± 3.14 |
| pting | input-lanjian | 27.3 ± 0.8 | 26.0 | 29.8 | 21.12 ± 3.13 |
| pting | input-pting | 27.4 ± 0.8 | 25.7 | 30.3 | 21.17 ± 3.15 |
| kcen | input-pting | 47.4 ± 1.0 | 45.7 | 49.8 | 36.62 ± 5.39 |
| kcen | input-lanjian | 48.2 ± 1.3 | 46.6 | 51.0 | 37.26 ± 5.51 |
| kcen | input-mattcl | 50.4 ± 1.0 | 48.7 | 52.6 | 38.91 ± 5.72 |
| kcen | input-kcen | 50.6 ± 0.9 | 48.9 | 52.7 | 39.13 ± 5.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|