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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.5 | 1.00 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.9 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.0 | 1.02 ± 0.22 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.6 | 2.41 ± 0.44 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 6.0 | 2.43 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 4.8 | 2.44 ± 0.42 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.5 | 4.8 | 2.44 ± 0.41 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.4 | 18.7 | 13.80 ± 2.20 |
| mattcl-ts | input-mattcl | 17.4 ± 0.4 | 16.2 | 18.6 | 13.82 ± 2.21 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.5 | 18.4 | 13.83 ± 2.21 |
| mattcl-ts | input-lanjian | 17.8 ± 4.8 | 16.5 | 79.0 | 14.18 ± 4.40 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.4 | 29.2 | 20.27 ± 3.29 |
| mattcl-py | input-mattcl | 25.5 ± 0.6 | 24.6 | 29.0 | 20.30 ± 3.25 |
| mattcl-py | input-lanjian | 26.0 ± 0.8 | 25.0 | 29.0 | 20.73 ± 3.34 |
| mattcl-py | input-pting | 26.2 ± 1.4 | 25.2 | 37.0 | 20.87 ± 3.47 |
| pting | input-kcen | 26.8 ± 0.8 | 25.7 | 29.6 | 21.35 ± 3.44 |
| pting | input-mattcl | 27.0 ± 0.8 | 26.0 | 29.8 | 21.48 ± 3.45 |
| pting | input-lanjian | 27.1 ± 0.8 | 26.1 | 30.0 | 21.56 ± 3.47 |
| pting | input-pting | 27.2 ± 0.8 | 26.1 | 29.6 | 21.65 ± 3.48 |
| kcen | input-pting | 47.2 ± 1.1 | 45.6 | 49.7 | 37.57 ± 6.01 |
| kcen | input-lanjian | 48.0 ± 1.2 | 46.9 | 53.3 | 38.24 ± 6.12 |
| kcen | input-mattcl | 50.0 ± 1.2 | 48.4 | 55.1 | 39.85 ± 6.38 |
| kcen | input-kcen | 50.2 ± 1.5 | 47.7 | 57.4 | 40.00 ± 6.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|