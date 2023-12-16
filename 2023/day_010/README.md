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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 2.0 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.2 | 1.05 ± 0.25 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 6.0 | 2.44 ± 0.44 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.1 | 5.8 | 2.45 ± 0.47 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.1 | 5.6 | 2.45 ± 0.46 |
| lanjian | input-pting | 3.0 ± 0.4 | 2.3 | 6.3 | 2.47 ± 0.48 |
| mattcl-ts | input-pting | 16.8 ± 0.4 | 15.8 | 18.3 | 13.63 ± 2.15 |
| mattcl-ts | input-mattcl | 16.8 ± 0.5 | 15.5 | 18.4 | 13.65 ± 2.16 |
| mattcl-ts | input-kcen | 16.9 ± 0.4 | 15.9 | 18.2 | 13.71 ± 2.16 |
| mattcl-ts | input-lanjian | 17.0 ± 0.4 | 16.1 | 18.2 | 13.81 ± 2.18 |
| mattcl-py | input-kcen | 26.0 ± 1.0 | 24.7 | 29.1 | 21.09 ± 3.39 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.7 | 28.7 | 21.16 ± 3.38 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 24.7 | 29.3 | 21.41 ± 3.41 |
| mattcl-py | input-pting | 26.5 ± 0.9 | 24.6 | 29.4 | 21.48 ± 3.43 |
| pting | input-mattcl | 27.0 ± 0.7 | 25.5 | 30.1 | 21.93 ± 3.46 |
| pting | input-pting | 27.2 ± 0.9 | 25.8 | 30.5 | 22.08 ± 3.52 |
| pting | input-kcen | 27.2 ± 1.1 | 26.0 | 34.2 | 22.09 ± 3.55 |
| pting | input-lanjian | 27.2 ± 0.7 | 26.3 | 30.1 | 22.09 ± 3.48 |
| kcen | input-pting | 47.3 ± 0.9 | 45.9 | 50.5 | 38.36 ± 6.02 |
| kcen | input-lanjian | 48.9 ± 1.3 | 46.9 | 52.5 | 39.64 ± 6.26 |
| kcen | input-kcen | 50.4 ± 1.1 | 48.7 | 53.4 | 40.92 ± 6.44 |
| kcen | input-mattcl | 50.7 ± 1.2 | 48.4 | 53.7 | 41.15 ± 6.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|