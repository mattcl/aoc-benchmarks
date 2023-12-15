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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 2.0 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.3 | 2.1 | 1.07 ± 0.24 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.8 | 2.43 ± 0.43 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 5.7 | 2.44 ± 0.44 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 6.1 | 2.49 ± 0.49 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.7 | 6.0 | 2.50 ± 0.49 |
| mattcl-ts | input-mattcl | 16.5 ± 0.5 | 15.2 | 18.2 | 13.25 ± 2.20 |
| mattcl-ts | input-kcen | 16.5 ± 0.4 | 15.6 | 17.5 | 13.26 ± 2.19 |
| mattcl-ts | input-lanjian | 16.6 ± 0.5 | 15.6 | 18.4 | 13.37 ± 2.22 |
| mattcl-ts | input-pting | 16.7 ± 3.3 | 15.4 | 59.8 | 13.42 ± 3.41 |
| mattcl-py | input-kcen | 25.9 ± 1.0 | 24.5 | 29.2 | 20.84 ± 3.50 |
| mattcl-py | input-lanjian | 26.5 ± 1.0 | 25.1 | 30.5 | 21.27 ± 3.57 |
| mattcl-py | input-mattcl | 26.5 ± 4.1 | 24.9 | 66.5 | 21.34 ± 4.83 |
| mattcl-py | input-pting | 26.6 ± 2.7 | 25.1 | 54.2 | 21.36 ± 4.13 |
| pting | input-kcen | 27.2 ± 0.9 | 25.8 | 29.9 | 21.83 ± 3.64 |
| pting | input-mattcl | 27.2 ± 0.9 | 26.1 | 30.4 | 21.90 ± 3.65 |
| pting | input-pting | 27.3 ± 1.0 | 26.1 | 33.7 | 21.96 ± 3.68 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.1 | 30.0 | 21.98 ± 3.64 |
| kcen | input-pting | 47.8 ± 2.9 | 45.6 | 69.1 | 38.40 ± 6.71 |
| kcen | input-lanjian | 48.7 ± 1.4 | 46.0 | 53.1 | 39.17 ± 6.51 |
| kcen | input-kcen | 50.4 ± 1.1 | 49.1 | 53.7 | 40.52 ± 6.68 |
| kcen | input-mattcl | 50.5 ± 1.3 | 48.3 | 53.9 | 40.62 ± 6.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|