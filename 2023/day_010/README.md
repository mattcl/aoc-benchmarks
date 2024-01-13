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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.6 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.21 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.7 | 1.01 ± 0.19 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.8 | 1.01 ± 0.19 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.4 | 5.4 | 2.28 ± 0.35 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.8 | 2.29 ± 0.37 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.8 | 5.6 | 2.29 ± 0.36 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.8 | 5.7 | 2.33 ± 0.40 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.5 | 18.6 | 13.05 ± 1.77 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.4 | 18.8 | 13.08 ± 1.78 |
| mattcl-ts | input-mattcl | 17.7 ± 0.4 | 16.6 | 19.9 | 13.13 ± 1.79 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.9 | 18.6 | 13.17 ± 1.79 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.7 | 29.7 | 19.35 ± 2.68 |
| mattcl-py | input-pting | 26.3 ± 0.9 | 25.0 | 29.7 | 19.57 ± 2.70 |
| mattcl-py | input-lanjian | 26.4 ± 1.0 | 24.8 | 29.4 | 19.63 ± 2.72 |
| mattcl-py | input-kcen | 26.6 ± 4.4 | 24.7 | 67.3 | 19.74 ± 4.20 |
| pting | input-kcen | 27.1 ± 1.0 | 25.4 | 33.4 | 20.13 ± 2.80 |
| pting | input-mattcl | 27.2 ± 0.9 | 25.6 | 30.3 | 20.20 ± 2.78 |
| pting | input-lanjian | 27.2 ± 0.7 | 25.6 | 29.2 | 20.20 ± 2.75 |
| pting | input-pting | 27.3 ± 1.1 | 26.0 | 34.8 | 20.25 ± 2.84 |
| kcen | input-pting | 47.1 ± 1.0 | 45.0 | 50.0 | 34.97 ± 4.74 |
| kcen | input-lanjian | 48.2 ± 1.1 | 46.3 | 50.5 | 35.82 ± 4.86 |
| kcen | input-mattcl | 50.2 ± 1.1 | 48.3 | 53.1 | 37.29 ± 5.06 |
| kcen | input-kcen | 50.5 ± 1.0 | 49.0 | 53.0 | 37.53 ± 5.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|