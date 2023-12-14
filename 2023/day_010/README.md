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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.0 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.4 | 5.6 | 2.43 ± 0.41 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.8 | 4.7 | 2.44 ± 0.37 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 5.6 | 2.46 ± 0.41 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.6 | 4.9 | 2.47 ± 0.41 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 18.9 | 13.80 ± 1.95 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.5 | 18.6 | 13.81 ± 1.95 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.3 | 18.6 | 13.83 ± 1.95 |
| mattcl-ts | input-lanjian | 17.7 ± 0.5 | 16.7 | 19.6 | 13.94 ± 1.97 |
| mattcl-py | input-kcen | 25.7 ± 0.8 | 24.1 | 28.9 | 20.24 ± 2.89 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.9 | 29.4 | 20.46 ± 2.93 |
| mattcl-py | input-pting | 26.1 ± 0.8 | 25.0 | 29.4 | 20.56 ± 2.92 |
| mattcl-py | input-lanjian | 26.3 ± 1.0 | 24.8 | 30.0 | 20.67 ± 2.98 |
| pting | input-kcen | 27.1 ± 0.9 | 25.9 | 30.2 | 21.31 ± 3.05 |
| pting | input-mattcl | 27.2 ± 1.1 | 26.0 | 36.7 | 21.38 ± 3.09 |
| pting | input-pting | 27.2 ± 0.8 | 25.9 | 30.5 | 21.40 ± 3.05 |
| pting | input-lanjian | 28.0 ± 5.5 | 25.6 | 72.2 | 22.02 ± 5.30 |
| kcen | input-pting | 47.6 ± 1.8 | 45.5 | 58.5 | 37.46 ± 5.39 |
| kcen | input-lanjian | 48.2 ± 1.1 | 46.3 | 51.0 | 37.91 ± 5.35 |
| kcen | input-kcen | 50.4 ± 1.0 | 47.9 | 53.3 | 39.60 ± 5.57 |
| kcen | input-mattcl | 51.0 ± 3.5 | 48.9 | 76.0 | 40.08 ± 6.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|