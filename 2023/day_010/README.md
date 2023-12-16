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
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.5 | 1.00 ± 0.22 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.5 | 1.01 ± 0.22 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.23 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 3.5 | 2.45 ± 0.43 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.2 | 5.7 | 2.47 ± 0.48 |
| lanjian | input-pting | 3.1 ± 0.1 | 2.3 | 4.1 | 2.47 ± 0.44 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 5.7 | 2.48 ± 0.47 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.4 | 19.2 | 13.88 ± 2.38 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.5 | 13.90 ± 2.38 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.3 | 18.7 | 13.95 ± 2.38 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.6 | 18.7 | 14.00 ± 2.39 |
| mattcl-py | input-mattcl | 25.5 ± 0.7 | 24.2 | 27.9 | 20.46 ± 3.52 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.2 | 28.0 | 20.47 ± 3.55 |
| mattcl-py | input-pting | 25.9 ± 0.6 | 24.8 | 28.1 | 20.79 ± 3.56 |
| mattcl-py | input-lanjian | 26.2 ± 3.4 | 25.1 | 61.6 | 21.07 ± 4.51 |
| pting | input-kcen | 26.6 ± 0.9 | 25.7 | 30.3 | 21.39 ± 3.70 |
| pting | input-mattcl | 26.9 ± 0.9 | 25.7 | 30.3 | 21.60 ± 3.74 |
| pting | input-pting | 27.0 ± 0.7 | 26.0 | 29.4 | 21.66 ± 3.72 |
| pting | input-lanjian | 27.0 ± 0.8 | 25.7 | 29.9 | 21.70 ± 3.73 |
| kcen | input-pting | 46.7 ± 1.1 | 45.1 | 49.8 | 37.50 ± 6.42 |
| kcen | input-lanjian | 47.7 ± 1.0 | 45.9 | 50.7 | 38.27 ± 6.54 |
| kcen | input-kcen | 50.0 ± 1.1 | 48.7 | 52.6 | 40.19 ± 6.87 |
| kcen | input-mattcl | 50.5 ± 4.4 | 48.2 | 82.3 | 40.53 ± 7.71 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|