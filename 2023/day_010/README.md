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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 2.0 | 1.00 ± 0.21 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.04 ± 0.22 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.3 | 1.04 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.3 | 3.7 | 2.27 ± 0.34 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.4 | 4.8 | 2.28 ± 0.36 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.4 | 6.2 | 2.31 ± 0.41 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.7 | 2.32 ± 0.37 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.6 | 18.6 | 13.28 ± 1.87 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 18.6 | 13.30 ± 1.87 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.5 | 18.6 | 13.30 ± 1.88 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.7 | 19.0 | 13.40 ± 1.89 |
| mattcl-py | input-mattcl | 25.9 ± 1.0 | 24.6 | 29.3 | 19.64 ± 2.85 |
| mattcl-py | input-kcen | 25.9 ± 2.7 | 24.1 | 53.9 | 19.65 ± 3.42 |
| mattcl-py | input-pting | 26.1 ± 0.8 | 25.0 | 28.8 | 19.82 ± 2.83 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 24.9 | 29.8 | 19.86 ± 2.85 |
| pting | input-kcen | 26.9 ± 0.7 | 25.8 | 29.5 | 20.38 ± 2.89 |
| pting | input-mattcl | 27.1 ± 0.8 | 25.7 | 30.7 | 20.56 ± 2.92 |
| pting | input-pting | 27.4 ± 1.1 | 26.0 | 34.4 | 20.79 ± 3.02 |
| pting | input-lanjian | 27.8 ± 4.8 | 26.1 | 75.4 | 21.06 ± 4.69 |
| kcen | input-pting | 47.4 ± 1.1 | 46.0 | 52.0 | 35.94 ± 5.07 |
| kcen | input-lanjian | 48.1 ± 1.3 | 46.3 | 51.8 | 36.47 ± 5.18 |
| kcen | input-kcen | 50.4 ± 1.3 | 48.6 | 53.6 | 38.21 ± 5.41 |
| kcen | input-mattcl | 50.7 ± 1.9 | 48.2 | 62.8 | 38.42 ± 5.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|