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
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.8 | 1.00 ± 0.18 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.18 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.1 | 1.06 ± 0.20 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 4.8 | 2.37 ± 0.36 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.7 | 2.40 ± 0.38 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.3 | 5.9 | 2.40 ± 0.43 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.4 | 5.9 | 2.41 ± 0.39 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.1 | 18.9 | 13.23 ± 1.76 |
| mattcl-ts | input-kcen | 17.4 ± 0.4 | 16.3 | 18.6 | 13.29 ± 1.76 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.3 | 19.5 | 13.31 ± 1.76 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.3 | 18.6 | 13.33 ± 1.77 |
| mattcl-py | input-kcen | 25.4 ± 0.7 | 24.3 | 28.2 | 19.44 ± 2.59 |
| mattcl-py | input-mattcl | 25.7 ± 0.8 | 24.8 | 29.0 | 19.66 ± 2.64 |
| mattcl-py | input-pting | 26.0 ± 0.7 | 24.9 | 29.0 | 19.88 ± 2.65 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 24.9 | 30.2 | 20.05 ± 2.71 |
| pting | input-kcen | 26.7 ± 0.9 | 25.7 | 29.5 | 20.41 ± 2.74 |
| pting | input-mattcl | 26.8 ± 0.7 | 25.7 | 29.5 | 20.45 ± 2.72 |
| pting | input-pting | 27.0 ± 0.6 | 25.7 | 29.6 | 20.60 ± 2.73 |
| pting | input-lanjian | 27.0 ± 0.7 | 26.0 | 29.3 | 20.60 ± 2.74 |
| kcen | input-pting | 47.6 ± 4.0 | 45.4 | 77.1 | 36.40 ± 5.64 |
| kcen | input-lanjian | 47.9 ± 0.9 | 46.4 | 50.1 | 36.59 ± 4.82 |
| kcen | input-kcen | 50.0 ± 1.2 | 48.3 | 54.1 | 38.21 ± 5.07 |
| kcen | input-mattcl | 50.1 ± 1.3 | 48.3 | 53.2 | 38.31 ± 5.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|