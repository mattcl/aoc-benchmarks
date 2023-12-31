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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.6 | 1.00 ± 0.22 |
| mattcl | input-pting | 1.3 ± 1.6 | 0.3 | 23.3 | 1.02 ± 1.28 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-mattcl | 3.0 ± 0.4 | 2.3 | 6.1 | 2.44 ± 0.49 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 4.8 | 2.44 ± 0.46 |
| lanjian | input-lanjian | 3.1 ± 0.4 | 2.5 | 5.6 | 2.46 ± 0.49 |
| lanjian | input-pting | 3.1 ± 1.9 | 2.2 | 29.3 | 2.50 ± 1.56 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.5 | 18.5 | 13.96 ± 2.29 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.6 | 19.5 | 14.02 ± 2.31 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.8 | 18.6 | 14.03 ± 2.31 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.5 | 18.7 | 14.14 ± 2.33 |
| mattcl-py | input-kcen | 25.6 ± 0.7 | 24.3 | 28.0 | 20.46 ± 3.38 |
| mattcl-py | input-pting | 26.0 ± 0.9 | 24.9 | 29.6 | 20.80 ± 3.47 |
| mattcl-py | input-mattcl | 26.2 ± 2.3 | 24.9 | 48.3 | 20.94 ± 3.88 |
| mattcl-py | input-lanjian | 26.4 ± 1.0 | 25.0 | 29.3 | 21.06 ± 3.53 |
| pting | input-kcen | 27.0 ± 0.7 | 25.9 | 30.0 | 21.56 ± 3.56 |
| pting | input-mattcl | 27.1 ± 0.7 | 26.0 | 29.9 | 21.69 ± 3.58 |
| pting | input-pting | 27.3 ± 0.7 | 25.9 | 30.0 | 21.82 ± 3.59 |
| pting | input-lanjian | 27.3 ± 0.8 | 26.3 | 30.0 | 21.83 ± 3.61 |
| kcen | input-pting | 47.2 ± 1.0 | 45.7 | 52.3 | 37.74 ± 6.20 |
| kcen | input-lanjian | 48.2 ± 1.2 | 46.3 | 51.2 | 38.48 ± 6.34 |
| kcen | input-mattcl | 50.3 ± 1.0 | 48.6 | 52.4 | 40.21 ± 6.59 |
| kcen | input-kcen | 50.4 ± 1.0 | 48.6 | 52.7 | 40.30 ± 6.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|