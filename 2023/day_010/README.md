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
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.6 | 1.01 ± 0.19 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 2.0 | 1.04 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.2 | 1.07 ± 0.24 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.1 | 5.2 | 2.54 ± 0.42 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.6 | 2.54 ± 0.43 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.6 | 4.7 | 2.55 ± 0.38 |
| lanjian | input-lanjian | 3.0 ± 0.4 | 2.7 | 5.8 | 2.57 ± 0.46 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.3 | 18.8 | 14.87 ± 2.01 |
| mattcl-ts | input-mattcl | 17.5 ± 0.5 | 16.3 | 18.7 | 14.87 ± 2.02 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 18.7 | 14.92 ± 2.02 |
| mattcl-ts | input-lanjian | 17.6 ± 0.4 | 16.7 | 19.0 | 14.98 ± 2.02 |
| mattcl-py | input-kcen | 25.8 ± 0.9 | 24.1 | 28.5 | 21.92 ± 3.03 |
| mattcl-py | input-mattcl | 26.0 ± 1.0 | 24.6 | 29.1 | 22.10 ± 3.07 |
| mattcl-py | input-pting | 26.3 ± 1.0 | 24.7 | 29.4 | 22.35 ± 3.09 |
| mattcl-py | input-lanjian | 26.3 ± 1.0 | 24.4 | 29.6 | 22.40 ± 3.10 |
| pting | input-kcen | 26.7 ± 0.7 | 25.7 | 29.5 | 22.72 ± 3.08 |
| pting | input-mattcl | 27.0 ± 0.9 | 25.7 | 30.2 | 23.00 ± 3.15 |
| pting | input-pting | 27.1 ± 0.7 | 25.6 | 30.2 | 23.07 ± 3.14 |
| pting | input-lanjian | 27.3 ± 0.9 | 25.8 | 30.2 | 23.23 ± 3.19 |
| kcen | input-pting | 47.2 ± 1.2 | 45.0 | 50.1 | 40.15 ± 5.44 |
| kcen | input-lanjian | 49.1 ± 6.0 | 46.0 | 94.2 | 41.73 ± 7.54 |
| kcen | input-kcen | 50.3 ± 1.0 | 48.5 | 53.0 | 42.81 ± 5.77 |
| kcen | input-mattcl | 50.5 ± 1.3 | 48.4 | 54.3 | 42.97 ± 5.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|