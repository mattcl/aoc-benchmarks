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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.21 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.03 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.1 | 2.2 | 3.6 | 2.35 ± 0.33 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.6 | 2.36 ± 0.39 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.8 | 2.37 ± 0.35 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.6 | 2.38 ± 0.40 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.4 | 13.29 ± 1.82 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.4 | 18.8 | 13.31 ± 1.83 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.4 | 18.7 | 13.40 ± 1.84 |
| mattcl-ts | input-mattcl | 17.6 ± 3.5 | 16.1 | 62.3 | 13.51 ± 3.23 |
| mattcl-py | input-kcen | 25.4 ± 0.9 | 24.3 | 28.9 | 19.51 ± 2.72 |
| mattcl-py | input-mattcl | 25.8 ± 1.0 | 24.3 | 28.9 | 19.82 ± 2.79 |
| mattcl-py | input-lanjian | 25.9 ± 0.8 | 24.8 | 29.0 | 19.89 ± 2.76 |
| mattcl-py | input-pting | 26.2 ± 1.0 | 24.7 | 29.1 | 20.10 ± 2.82 |
| pting | input-kcen | 26.6 ± 0.8 | 25.7 | 29.5 | 20.44 ± 2.82 |
| pting | input-mattcl | 26.9 ± 0.8 | 26.0 | 30.1 | 20.68 ± 2.87 |
| pting | input-pting | 27.0 ± 0.7 | 25.9 | 29.8 | 20.72 ± 2.85 |
| pting | input-lanjian | 27.1 ± 0.8 | 26.0 | 29.9 | 20.78 ± 2.87 |
| kcen | input-pting | 46.7 ± 0.8 | 45.5 | 49.3 | 35.81 ± 4.88 |
| kcen | input-lanjian | 47.9 ± 1.0 | 46.5 | 50.8 | 36.76 ± 5.03 |
| kcen | input-mattcl | 50.1 ± 1.2 | 48.2 | 52.9 | 38.41 ± 5.27 |
| kcen | input-kcen | 50.3 ± 1.2 | 48.3 | 53.7 | 38.58 ± 5.30 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|