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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 1.9 | 1.04 ± 0.21 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 1.0 | 2.0 | 1.07 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.07 ± 0.22 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 3.9 | 2.32 ± 0.35 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.32 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 2.35 ± 0.39 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 4.9 | 2.39 ± 0.42 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.5 | 18.8 | 13.35 ± 1.92 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.7 | 18.6 | 13.36 ± 1.92 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.7 | 19.9 | 13.37 ± 1.92 |
| mattcl-ts | input-lanjian | 17.7 ± 0.5 | 16.4 | 19.3 | 13.50 ± 1.95 |
| mattcl-py | input-kcen | 25.7 ± 0.8 | 23.8 | 28.8 | 19.51 ± 2.84 |
| mattcl-py | input-mattcl | 25.9 ± 0.8 | 24.7 | 29.3 | 19.73 ± 2.88 |
| mattcl-py | input-pting | 26.1 ± 0.8 | 24.9 | 29.3 | 19.84 ± 2.88 |
| mattcl-py | input-lanjian | 26.3 ± 1.0 | 24.9 | 30.6 | 19.99 ± 2.94 |
| pting | input-kcen | 27.0 ± 0.9 | 25.8 | 29.8 | 20.56 ± 3.00 |
| pting | input-pting | 27.2 ± 0.6 | 26.3 | 30.4 | 20.71 ± 2.98 |
| pting | input-lanjian | 27.4 ± 0.9 | 25.7 | 30.6 | 20.84 ± 3.04 |
| pting | input-mattcl | 27.4 ± 1.0 | 26.1 | 33.7 | 20.87 ± 3.07 |
| kcen | input-pting | 47.5 ± 1.1 | 45.0 | 50.9 | 36.16 ± 5.20 |
| kcen | input-lanjian | 48.5 ± 1.3 | 46.5 | 52.0 | 36.90 ± 5.33 |
| kcen | input-mattcl | 50.4 ± 1.4 | 47.9 | 54.2 | 38.35 ± 5.55 |
| kcen | input-kcen | 50.6 ± 1.3 | 48.0 | 53.3 | 38.51 ± 5.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|