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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.4 | 2.1 | 1.07 ± 0.21 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 2.9 | 1.07 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.5 | 1.07 ± 0.22 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.7 | 2.30 ± 0.36 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.6 | 4.9 | 2.31 ± 0.34 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.2 | 5.6 | 2.31 ± 0.39 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.32 ± 0.40 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.7 | 18.9 | 13.19 ± 1.78 |
| mattcl-ts | input-kcen | 17.6 ± 0.5 | 16.3 | 19.7 | 13.24 ± 1.80 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.8 | 19.1 | 13.25 ± 1.79 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.6 | 18.8 | 13.36 ± 1.80 |
| mattcl-py | input-kcen | 26.1 ± 0.8 | 24.9 | 29.0 | 19.67 ± 2.69 |
| mattcl-py | input-mattcl | 26.2 ± 1.1 | 24.8 | 29.9 | 19.74 ± 2.76 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 25.3 | 30.0 | 19.79 ± 2.72 |
| mattcl-py | input-pting | 26.5 ± 0.9 | 24.7 | 29.5 | 19.97 ± 2.75 |
| pting | input-kcen | 27.1 ± 0.9 | 25.3 | 29.6 | 20.46 ± 2.80 |
| pting | input-mattcl | 27.2 ± 0.9 | 26.1 | 30.7 | 20.50 ± 2.81 |
| pting | input-lanjian | 27.2 ± 0.7 | 25.9 | 29.8 | 20.53 ± 2.78 |
| pting | input-pting | 27.3 ± 0.8 | 26.2 | 30.1 | 20.59 ± 2.81 |
| kcen | input-pting | 47.6 ± 1.3 | 45.8 | 53.0 | 35.89 ± 4.87 |
| kcen | input-lanjian | 48.2 ± 1.0 | 46.5 | 51.3 | 36.32 ± 4.89 |
| kcen | input-mattcl | 50.6 ± 1.4 | 47.9 | 55.2 | 38.17 ± 5.19 |
| kcen | input-kcen | 50.7 ± 1.2 | 48.9 | 54.0 | 38.27 ± 5.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|