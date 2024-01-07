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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.5 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.9 | 1.00 ± 0.18 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.2 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.7 | 2.3 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.8 | 2.21 ± 0.35 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.6 | 3.8 | 2.23 ± 0.32 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.2 | 5.6 | 2.23 ± 0.37 |
| lanjian | input-kcen | 3.1 ± 0.4 | 2.4 | 6.0 | 2.23 ± 0.40 |
| mattcl-ts | input-mattcl | 17.7 ± 0.4 | 16.5 | 18.8 | 12.63 ± 1.74 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.7 | 19.1 | 12.65 ± 1.73 |
| mattcl-ts | input-kcen | 17.7 ± 0.4 | 16.7 | 19.2 | 12.65 ± 1.74 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.6 | 18.7 | 12.69 ± 1.74 |
| mattcl-py | input-mattcl | 26.2 ± 1.0 | 24.8 | 29.3 | 18.74 ± 2.64 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 24.9 | 29.8 | 18.75 ± 2.61 |
| mattcl-py | input-kcen | 26.3 ± 4.5 | 24.4 | 74.1 | 18.80 ± 4.13 |
| mattcl-py | input-lanjian | 26.3 ± 1.0 | 25.3 | 31.7 | 18.82 ± 2.64 |
| pting | input-mattcl | 27.2 ± 0.7 | 26.1 | 29.9 | 19.49 ± 2.68 |
| pting | input-kcen | 27.2 ± 1.0 | 25.8 | 30.4 | 19.49 ± 2.72 |
| pting | input-pting | 27.3 ± 0.8 | 26.3 | 29.8 | 19.56 ± 2.71 |
| pting | input-lanjian | 27.4 ± 0.8 | 26.0 | 30.3 | 19.59 ± 2.71 |
| kcen | input-pting | 47.7 ± 1.0 | 46.2 | 51.1 | 34.11 ± 4.67 |
| kcen | input-lanjian | 48.4 ± 1.1 | 47.0 | 51.6 | 34.62 ± 4.75 |
| kcen | input-mattcl | 50.6 ± 1.5 | 48.6 | 58.5 | 36.20 ± 5.01 |
| kcen | input-kcen | 51.0 ± 1.1 | 49.0 | 53.6 | 36.51 ± 5.00 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|