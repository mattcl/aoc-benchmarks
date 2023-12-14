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
| mattcl | input-mattcl | 1.3 ± 0.1 | 0.8 | 1.5 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.00 ± 0.17 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 1.6 | 1.00 ± 0.16 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 0.9 | 1.5 | 1.01 ± 0.16 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 4.8 | 2.38 ± 0.31 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.1 | 2.38 ± 0.34 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 4.8 | 2.38 ± 0.31 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.3 | 5.8 | 2.39 ± 0.33 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.2 | 18.3 | 13.26 ± 1.54 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.6 | 13.29 ± 1.54 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.5 | 18.5 | 13.32 ± 1.55 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.7 | 13.35 ± 1.55 |
| mattcl-py | input-kcen | 25.6 ± 1.0 | 24.5 | 31.6 | 19.60 ± 2.37 |
| mattcl-py | input-mattcl | 25.7 ± 0.8 | 24.8 | 28.8 | 19.70 ± 2.33 |
| mattcl-py | input-pting | 26.3 ± 1.6 | 24.9 | 40.7 | 20.14 ± 2.59 |
| mattcl-py | input-lanjian | 26.5 ± 2.2 | 25.1 | 46.9 | 20.31 ± 2.88 |
| pting | input-kcen | 26.7 ± 0.9 | 25.5 | 30.1 | 20.45 ± 2.43 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.8 | 29.6 | 20.56 ± 2.42 |
| pting | input-pting | 27.0 ± 0.8 | 26.2 | 30.4 | 20.73 ± 2.43 |
| pting | input-lanjian | 27.1 ± 0.9 | 26.1 | 30.3 | 20.79 ± 2.47 |
| kcen | input-pting | 47.2 ± 1.5 | 45.1 | 54.8 | 36.19 ± 4.28 |
| kcen | input-lanjian | 47.9 ± 1.2 | 46.3 | 50.5 | 36.72 ± 4.28 |
| kcen | input-kcen | 49.9 ± 1.1 | 48.5 | 53.0 | 38.24 ± 4.43 |
| kcen | input-mattcl | 50.0 ± 1.2 | 48.6 | 53.5 | 38.33 ± 4.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|