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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.1 | 1.05 ± 0.23 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 5.6 | 2.34 ± 0.43 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 2.36 ± 0.48 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.2 | 5.6 | 2.36 ± 0.47 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 6.1 | 2.37 ± 0.45 |
| mattcl-ts | input-mattcl | 16.8 ± 0.4 | 15.9 | 18.0 | 12.96 ± 2.22 |
| mattcl-ts | input-pting | 16.8 ± 0.4 | 15.9 | 18.1 | 13.00 ± 2.23 |
| mattcl-ts | input-kcen | 16.9 ± 0.4 | 16.0 | 18.1 | 13.02 ± 2.24 |
| mattcl-ts | input-lanjian | 17.2 ± 2.0 | 15.8 | 41.6 | 13.30 ± 2.72 |
| mattcl-py | input-mattcl | 25.8 ± 0.9 | 24.6 | 28.8 | 19.94 ± 3.46 |
| mattcl-py | input-kcen | 25.9 ± 0.8 | 24.8 | 28.7 | 19.96 ± 3.44 |
| mattcl-py | input-pting | 26.4 ± 1.0 | 25.2 | 29.8 | 20.37 ± 3.54 |
| mattcl-py | input-lanjian | 26.5 ± 1.0 | 25.1 | 29.8 | 20.46 ± 3.56 |
| pting | input-kcen | 27.0 ± 0.6 | 26.0 | 29.5 | 20.82 ± 3.57 |
| pting | input-mattcl | 27.2 ± 0.9 | 25.7 | 30.3 | 20.97 ± 3.62 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.2 | 29.6 | 21.05 ± 3.62 |
| pting | input-pting | 27.4 ± 0.7 | 26.2 | 29.9 | 21.15 ± 3.64 |
| kcen | input-pting | 47.5 ± 1.0 | 45.6 | 50.2 | 36.62 ± 6.27 |
| kcen | input-lanjian | 48.4 ± 1.2 | 46.5 | 52.3 | 37.39 ± 6.42 |
| kcen | input-kcen | 50.1 ± 1.2 | 48.4 | 53.7 | 38.70 ± 6.63 |
| kcen | input-mattcl | 50.4 ± 1.3 | 48.3 | 54.2 | 38.88 ± 6.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|