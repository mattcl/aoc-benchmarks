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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 2.1 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.9 | 1.8 | 1.05 ± 0.23 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.6 | 2.3 | 1.13 ± 0.27 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.7 | 2.46 ± 0.51 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 4.9 | 2.47 ± 0.48 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.7 | 2.48 ± 0.52 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.7 | 5.9 | 2.48 ± 0.51 |
| mattcl-ts | input-pting | 17.6 ± 0.5 | 16.5 | 19.0 | 14.25 ± 2.65 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.5 | 18.6 | 14.28 ± 2.65 |
| mattcl-ts | input-kcen | 17.8 ± 2.9 | 16.6 | 54.7 | 14.41 ± 3.55 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.6 | 18.9 | 14.44 ± 2.68 |
| mattcl-py | input-kcen | 25.8 ± 0.9 | 24.4 | 29.0 | 20.91 ± 3.91 |
| mattcl-py | input-mattcl | 26.0 ± 0.8 | 24.8 | 29.1 | 21.08 ± 3.93 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 24.5 | 30.2 | 21.31 ± 3.99 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.1 | 30.1 | 21.42 ± 4.01 |
| pting | input-mattcl | 27.2 ± 0.9 | 25.8 | 30.4 | 22.08 ± 4.12 |
| pting | input-pting | 27.3 ± 0.8 | 26.1 | 30.3 | 22.12 ± 4.12 |
| pting | input-lanjian | 27.3 ± 0.9 | 26.1 | 30.5 | 22.15 ± 4.13 |
| pting | input-kcen | 27.4 ± 2.5 | 25.9 | 51.9 | 22.19 ± 4.57 |
| kcen | input-pting | 47.6 ± 1.1 | 45.3 | 50.2 | 38.59 ± 7.15 |
| kcen | input-lanjian | 48.6 ± 0.9 | 46.9 | 50.8 | 39.43 ± 7.29 |
| kcen | input-mattcl | 50.1 ± 1.1 | 48.3 | 53.3 | 40.61 ± 7.52 |
| kcen | input-kcen | 50.7 ± 1.4 | 48.3 | 55.9 | 41.13 ± 7.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|