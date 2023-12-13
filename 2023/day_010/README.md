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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.05 ± 0.22 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.1 | 1.10 ± 0.24 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.1 | 2.44 ± 0.38 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.7 | 2.45 ± 0.43 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 2.45 ± 0.43 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.8 | 6.0 | 2.49 ± 0.45 |
| mattcl-ts | input-mattcl | 17.1 ± 0.4 | 16.1 | 18.4 | 13.54 ± 2.02 |
| mattcl-ts | input-kcen | 17.1 ± 0.4 | 16.1 | 17.9 | 13.56 ± 2.02 |
| mattcl-ts | input-lanjian | 17.3 ± 0.4 | 16.2 | 18.9 | 13.72 ± 2.05 |
| mattcl-ts | input-pting | 17.7 ± 6.5 | 16.0 | 100.5 | 14.05 ± 5.57 |
| mattcl-py | input-kcen | 25.9 ± 1.0 | 24.4 | 29.9 | 20.54 ± 3.12 |
| mattcl-py | input-mattcl | 25.9 ± 0.9 | 24.7 | 29.0 | 20.57 ± 3.10 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.0 | 29.6 | 20.89 ± 3.16 |
| mattcl-py | input-pting | 26.9 ± 5.1 | 24.6 | 76.3 | 21.34 ± 5.14 |
| pting | input-kcen | 27.0 ± 0.8 | 25.9 | 29.7 | 21.38 ± 3.20 |
| pting | input-mattcl | 27.0 ± 0.8 | 25.5 | 30.0 | 21.40 ± 3.20 |
| pting | input-lanjian | 27.4 ± 0.8 | 26.2 | 30.2 | 21.74 ± 3.26 |
| pting | input-pting | 27.5 ± 0.9 | 26.2 | 31.0 | 21.82 ± 3.28 |
| kcen | input-pting | 47.4 ± 1.0 | 45.9 | 50.6 | 37.60 ± 5.58 |
| kcen | input-lanjian | 48.6 ± 1.2 | 46.5 | 51.7 | 38.51 ± 5.74 |
| kcen | input-kcen | 50.4 ± 1.2 | 48.4 | 53.7 | 39.94 ± 5.94 |
| kcen | input-mattcl | 50.4 ± 1.0 | 48.8 | 53.4 | 39.94 ± 5.92 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|