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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.8 | 1.04 ± 0.21 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.1 | 1.9 | 1.08 ± 0.22 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 3.8 | 2.45 ± 0.43 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 4.9 | 2.46 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.5 | 4.9 | 2.48 ± 0.45 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.5 | 6.1 | 2.49 ± 0.51 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.6 | 19.3 | 13.92 ± 2.35 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.6 | 18.7 | 13.97 ± 2.37 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.5 | 18.9 | 14.04 ± 2.38 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.9 | 18.9 | 14.12 ± 2.39 |
| mattcl-py | input-kcen | 25.7 ± 0.8 | 24.3 | 28.6 | 20.34 ± 3.47 |
| mattcl-py | input-mattcl | 25.9 ± 0.8 | 24.6 | 28.7 | 20.50 ± 3.50 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 24.9 | 29.5 | 20.76 ± 3.55 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 25.0 | 29.4 | 20.84 ± 3.57 |
| pting | input-kcen | 27.0 ± 0.8 | 25.7 | 30.2 | 21.41 ± 3.65 |
| pting | input-lanjian | 27.3 ± 1.0 | 26.0 | 30.9 | 21.64 ± 3.71 |
| pting | input-pting | 27.4 ± 0.9 | 26.2 | 30.7 | 21.72 ± 3.72 |
| pting | input-mattcl | 27.9 ± 3.9 | 26.1 | 55.1 | 22.14 ± 4.82 |
| kcen | input-pting | 47.4 ± 1.4 | 45.7 | 53.9 | 37.57 ± 6.39 |
| kcen | input-lanjian | 48.0 ± 1.0 | 45.9 | 50.8 | 38.02 ± 6.43 |
| kcen | input-kcen | 50.3 ± 1.3 | 48.5 | 53.3 | 39.91 ± 6.78 |
| kcen | input-mattcl | 50.6 ± 1.3 | 48.4 | 54.5 | 40.11 ± 6.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|