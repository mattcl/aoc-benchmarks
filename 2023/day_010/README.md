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
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.1 | 1.00 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.8 | 2.1 | 1.03 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 5.7 | 2.40 ± 0.37 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 4.2 | 2.40 ± 0.35 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 6.1 | 2.41 ± 0.42 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.2 | 5.9 | 2.44 ± 0.46 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.5 | 18.9 | 13.67 ± 1.88 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.6 | 18.7 | 13.70 ± 1.88 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.6 | 18.7 | 13.71 ± 1.88 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.8 | 19.1 | 13.81 ± 1.90 |
| mattcl-py | input-kcen | 25.8 ± 0.7 | 24.5 | 28.2 | 20.10 ± 2.78 |
| mattcl-py | input-mattcl | 26.0 ± 0.8 | 24.6 | 29.9 | 20.25 ± 2.82 |
| mattcl-py | input-pting | 26.4 ± 1.0 | 24.8 | 29.1 | 20.62 ± 2.89 |
| mattcl-py | input-lanjian | 26.5 ± 1.1 | 25.2 | 31.2 | 20.68 ± 2.92 |
| pting | input-kcen | 26.9 ± 0.8 | 25.6 | 30.0 | 20.96 ± 2.92 |
| pting | input-mattcl | 27.0 ± 0.6 | 25.7 | 29.1 | 21.07 ± 2.89 |
| pting | input-lanjian | 27.2 ± 0.8 | 26.1 | 30.0 | 21.23 ± 2.94 |
| pting | input-pting | 27.2 ± 0.7 | 25.8 | 29.9 | 21.25 ± 2.93 |
| kcen | input-pting | 47.3 ± 1.3 | 45.4 | 50.5 | 36.92 ± 5.10 |
| kcen | input-lanjian | 48.0 ± 1.0 | 46.3 | 50.6 | 37.49 ± 5.14 |
| kcen | input-mattcl | 50.2 ± 1.1 | 48.2 | 53.3 | 39.19 ± 5.38 |
| kcen | input-kcen | 50.3 ± 1.2 | 48.7 | 53.0 | 39.27 ± 5.40 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|