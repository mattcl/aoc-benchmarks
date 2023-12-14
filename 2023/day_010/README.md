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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.8 | 1.8 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.8 | 1.8 | 1.05 ± 0.24 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.0 | 1.08 ± 0.26 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 5.7 | 2.43 ± 0.49 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 4.1 | 2.45 ± 0.48 |
| lanjian | input-pting | 3.2 ± 0.4 | 2.5 | 6.3 | 2.49 ± 0.56 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.5 | 6.2 | 2.50 ± 0.56 |
| mattcl-ts | input-kcen | 17.6 ± 0.5 | 16.4 | 19.9 | 13.78 ± 2.60 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.6 | 19.0 | 13.83 ± 2.60 |
| mattcl-ts | input-lanjian | 17.7 ± 0.5 | 16.4 | 19.2 | 13.85 ± 2.61 |
| mattcl-ts | input-mattcl | 17.8 ± 0.5 | 16.6 | 19.1 | 13.93 ± 2.63 |
| mattcl-py | input-kcen | 25.9 ± 1.0 | 24.8 | 29.1 | 20.28 ± 3.86 |
| mattcl-py | input-pting | 26.4 ± 0.9 | 25.1 | 29.5 | 20.62 ± 3.90 |
| mattcl-py | input-lanjian | 26.6 ± 3.3 | 25.0 | 59.8 | 20.80 ± 4.65 |
| mattcl-py | input-mattcl | 27.1 ± 0.8 | 25.8 | 30.3 | 21.17 ± 3.99 |
| pting | input-kcen | 27.2 ± 0.8 | 26.0 | 29.9 | 21.25 ± 4.01 |
| pting | input-pting | 27.3 ± 0.7 | 26.0 | 30.1 | 21.31 ± 4.01 |
| pting | input-mattcl | 27.3 ± 0.7 | 26.2 | 29.6 | 21.32 ± 4.01 |
| pting | input-lanjian | 27.3 ± 0.8 | 26.3 | 30.4 | 21.36 ± 4.03 |
| kcen | input-pting | 47.6 ± 1.0 | 46.2 | 51.0 | 37.22 ± 6.99 |
| kcen | input-lanjian | 48.6 ± 1.4 | 46.8 | 54.9 | 37.98 ± 7.16 |
| kcen | input-kcen | 50.8 ± 1.5 | 48.9 | 58.1 | 39.72 ± 7.50 |
| kcen | input-mattcl | 51.0 ± 1.4 | 48.6 | 54.9 | 39.89 ± 7.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|