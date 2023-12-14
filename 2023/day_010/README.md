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
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.5 | 1.00 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.22 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.1 | 3.4 | 2.36 ± 0.40 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 5.7 | 2.41 ± 0.42 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 3.9 | 2.42 ± 0.40 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.8 | 2.43 ± 0.47 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 19.0 | 13.88 ± 2.16 |
| mattcl-ts | input-mattcl | 17.5 ± 0.5 | 16.5 | 18.9 | 13.88 ± 2.17 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.7 | 19.4 | 14.03 ± 2.19 |
| mattcl-ts | input-kcen | 17.9 ± 3.6 | 16.4 | 55.5 | 14.20 ± 3.62 |
| mattcl-py | input-kcen | 25.9 ± 0.9 | 24.7 | 29.3 | 20.51 ± 3.24 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.7 | 29.2 | 20.67 ± 3.27 |
| mattcl-py | input-pting | 26.1 ± 0.7 | 25.0 | 29.2 | 20.69 ± 3.24 |
| mattcl-py | input-lanjian | 26.2 ± 0.7 | 25.0 | 28.9 | 20.73 ± 3.24 |
| pting | input-kcen | 27.0 ± 0.8 | 25.7 | 30.4 | 21.39 ± 3.36 |
| pting | input-mattcl | 27.1 ± 0.8 | 25.9 | 30.6 | 21.45 ± 3.37 |
| pting | input-lanjian | 27.2 ± 0.8 | 26.2 | 30.1 | 21.56 ± 3.38 |
| pting | input-pting | 27.2 ± 0.9 | 25.6 | 30.3 | 21.57 ± 3.40 |
| kcen | input-pting | 47.3 ± 1.0 | 45.7 | 50.6 | 37.49 ± 5.84 |
| kcen | input-lanjian | 48.4 ± 1.1 | 46.9 | 51.2 | 38.31 ± 5.98 |
| kcen | input-mattcl | 50.0 ± 1.2 | 48.2 | 52.8 | 39.61 ± 6.18 |
| kcen | input-kcen | 50.3 ± 1.1 | 48.3 | 53.2 | 39.87 ± 6.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|