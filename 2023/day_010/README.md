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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.5 | 1.8 | 1.00 ± 0.20 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.8 | 2.0 | 1.04 ± 0.21 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.2 | 1.05 ± 0.20 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 5.0 | 2.27 ± 0.35 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.4 | 2.31 ± 0.38 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.5 | 4.7 | 2.32 ± 0.37 |
| lanjian | input-kcen | 3.2 ± 0.4 | 2.5 | 6.5 | 2.34 ± 0.45 |
| mattcl-ts | input-mattcl | 17.0 ± 0.4 | 15.9 | 18.2 | 12.58 ± 1.76 |
| mattcl-ts | input-kcen | 17.0 ± 0.4 | 16.0 | 18.7 | 12.60 ± 1.76 |
| mattcl-ts | input-pting | 17.1 ± 0.5 | 16.0 | 18.8 | 12.61 ± 1.77 |
| mattcl-ts | input-lanjian | 17.2 ± 0.5 | 16.4 | 18.5 | 12.74 ± 1.78 |
| mattcl-py | input-kcen | 25.7 ± 0.7 | 24.5 | 30.0 | 18.98 ± 2.66 |
| mattcl-py | input-mattcl | 25.9 ± 0.9 | 24.2 | 29.5 | 19.12 ± 2.70 |
| mattcl-py | input-lanjian | 26.2 ± 0.9 | 24.8 | 29.9 | 19.39 ± 2.74 |
| mattcl-py | input-pting | 26.5 ± 1.9 | 24.8 | 44.6 | 19.61 ± 3.06 |
| pting | input-kcen | 27.0 ± 0.6 | 26.0 | 29.8 | 19.99 ± 2.79 |
| pting | input-lanjian | 27.1 ± 0.6 | 26.1 | 29.8 | 20.04 ± 2.79 |
| pting | input-mattcl | 27.1 ± 0.8 | 25.9 | 30.1 | 20.05 ± 2.82 |
| pting | input-pting | 27.4 ± 1.7 | 26.0 | 43.6 | 20.27 ± 3.06 |
| kcen | input-pting | 47.2 ± 1.1 | 45.0 | 50.4 | 34.90 ± 4.86 |
| kcen | input-lanjian | 48.2 ± 1.1 | 46.5 | 52.0 | 35.67 ± 4.97 |
| kcen | input-kcen | 50.2 ± 1.3 | 48.3 | 53.5 | 37.15 ± 5.19 |
| kcen | input-mattcl | 50.3 ± 1.2 | 48.3 | 55.1 | 37.19 ± 5.19 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|