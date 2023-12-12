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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.1 | 0.8 | 1.5 | 1.02 ± 0.18 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 2.0 | 1.04 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.1 | 1.08 ± 0.23 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 6.4 | 2.42 ± 0.41 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.8 | 2.43 ± 0.43 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.8 | 6.0 | 2.43 ± 0.40 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.3 | 5.8 | 2.45 ± 0.45 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.7 | 18.9 | 13.71 ± 1.95 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.2 | 18.7 | 13.76 ± 1.96 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.5 | 18.6 | 13.76 ± 1.96 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.6 | 18.8 | 13.85 ± 1.97 |
| mattcl-py | input-mattcl | 26.1 ± 0.9 | 24.9 | 29.1 | 20.41 ± 2.95 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 24.9 | 29.4 | 20.45 ± 2.95 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 24.9 | 30.5 | 20.53 ± 2.96 |
| mattcl-py | input-kcen | 26.6 ± 4.6 | 24.9 | 67.6 | 20.75 ± 4.62 |
| pting | input-kcen | 27.0 ± 0.9 | 25.9 | 33.8 | 21.10 ± 3.05 |
| pting | input-pting | 27.4 ± 1.0 | 26.0 | 30.9 | 21.37 ± 3.10 |
| pting | input-lanjian | 27.4 ± 0.9 | 26.2 | 30.4 | 21.42 ± 3.09 |
| pting | input-mattcl | 27.5 ± 2.0 | 25.6 | 44.2 | 21.45 ± 3.38 |
| kcen | input-pting | 47.2 ± 1.1 | 45.6 | 51.7 | 36.89 ± 5.26 |
| kcen | input-lanjian | 48.2 ± 1.1 | 46.3 | 51.6 | 37.66 ± 5.36 |
| kcen | input-mattcl | 50.8 ± 1.3 | 48.9 | 53.9 | 39.71 ± 5.67 |
| kcen | input-kcen | 51.0 ± 4.4 | 48.5 | 83.0 | 39.86 ± 6.58 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|