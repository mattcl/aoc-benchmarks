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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.19 |
| mattcl | input-pting | 1.3 ± 0.1 | 1.0 | 1.7 | 1.03 ± 0.18 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.8 | 1.06 ± 0.22 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 5.6 | 2.45 ± 0.39 |
| lanjian | input-mattcl | 3.0 ± 0.1 | 2.2 | 3.7 | 2.47 ± 0.35 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.3 | 5.6 | 2.48 ± 0.39 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.5 | 2.48 ± 0.42 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.2 | 18.6 | 14.09 ± 1.96 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.1 | 18.5 | 14.12 ± 1.97 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.6 | 18.4 | 14.16 ± 1.97 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.1 | 18.6 | 14.19 ± 1.97 |
| mattcl-py | input-kcen | 25.6 ± 1.2 | 24.2 | 33.6 | 20.88 ± 3.02 |
| mattcl-py | input-mattcl | 25.7 ± 0.7 | 24.6 | 28.5 | 20.93 ± 2.93 |
| mattcl-py | input-lanjian | 26.0 ± 0.7 | 25.1 | 29.3 | 21.18 ± 2.96 |
| mattcl-py | input-pting | 26.1 ± 1.0 | 25.0 | 29.9 | 21.31 ± 3.03 |
| pting | input-kcen | 26.6 ± 0.8 | 25.7 | 29.4 | 21.72 ± 3.05 |
| pting | input-pting | 26.8 ± 0.7 | 25.8 | 29.4 | 21.82 ± 3.04 |
| pting | input-mattcl | 26.9 ± 0.8 | 26.0 | 31.4 | 21.93 ± 3.08 |
| pting | input-lanjian | 27.1 ± 1.0 | 25.8 | 30.1 | 22.11 ± 3.14 |
| kcen | input-pting | 46.9 ± 0.9 | 45.5 | 49.4 | 38.27 ± 5.30 |
| kcen | input-lanjian | 47.9 ± 1.1 | 46.3 | 51.3 | 39.08 ± 5.43 |
| kcen | input-mattcl | 50.1 ± 1.1 | 48.7 | 53.0 | 40.85 ± 5.67 |
| kcen | input-kcen | 50.3 ± 1.2 | 48.6 | 55.2 | 41.03 ± 5.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|