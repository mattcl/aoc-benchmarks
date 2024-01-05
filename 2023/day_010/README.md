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
| mattcl | input-kcen | 1.4 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.6 | 2.1 | 1.05 ± 0.22 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.1 | 1.05 ± 0.21 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.6 | 1.07 ± 0.23 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.6 | 2.27 ± 0.41 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 5.7 | 2.27 ± 0.40 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 4.9 | 2.28 ± 0.40 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.5 | 4.1 | 2.29 ± 0.38 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.7 | 18.6 | 12.84 ± 1.94 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.6 | 18.7 | 12.86 ± 1.95 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.9 | 19.5 | 12.95 ± 1.97 |
| mattcl-ts | input-lanjian | 17.8 ± 0.4 | 16.9 | 18.9 | 12.99 ± 1.97 |
| mattcl-py | input-kcen | 25.9 ± 0.9 | 24.7 | 28.9 | 18.90 ± 2.90 |
| mattcl-py | input-mattcl | 26.0 ± 0.8 | 24.9 | 29.1 | 18.97 ± 2.91 |
| mattcl-py | input-pting | 26.1 ± 0.8 | 25.1 | 29.7 | 19.06 ± 2.92 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 24.7 | 29.1 | 19.31 ± 2.97 |
| pting | input-kcen | 27.1 ± 0.8 | 26.0 | 30.2 | 19.82 ± 3.03 |
| pting | input-mattcl | 27.3 ± 0.9 | 25.7 | 30.2 | 19.93 ± 3.07 |
| pting | input-lanjian | 27.3 ± 0.6 | 26.3 | 29.9 | 19.94 ± 3.02 |
| pting | input-pting | 27.3 ± 0.8 | 26.1 | 30.4 | 19.96 ± 3.06 |
| kcen | input-pting | 47.1 ± 1.3 | 45.2 | 50.7 | 34.43 ± 5.25 |
| kcen | input-lanjian | 48.5 ± 1.1 | 46.5 | 51.2 | 35.42 ± 5.37 |
| kcen | input-mattcl | 50.5 ± 1.0 | 48.9 | 53.7 | 36.90 ± 5.59 |
| kcen | input-kcen | 50.7 ± 1.0 | 49.6 | 53.8 | 37.06 ± 5.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|