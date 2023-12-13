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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.6 | 1.4 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 2.5 | 1.06 ± 0.26 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.4 | 2.1 | 1.08 ± 0.27 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 3.3 | 2.57 ± 0.45 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.9 | 2.59 ± 0.48 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.4 | 5.6 | 2.62 ± 0.51 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.2 | 6.1 | 2.62 ± 0.52 |
| mattcl-ts | input-mattcl | 17.2 ± 0.3 | 16.4 | 18.2 | 14.83 ± 2.49 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.3 | 18.6 | 14.90 ± 2.51 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.2 | 18.3 | 14.90 ± 2.51 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.4 | 15.03 ± 2.53 |
| mattcl-py | input-kcen | 25.5 ± 1.3 | 24.3 | 35.2 | 22.00 ± 3.83 |
| mattcl-py | input-mattcl | 25.7 ± 1.0 | 24.5 | 29.1 | 22.15 ± 3.78 |
| mattcl-py | input-lanjian | 25.9 ± 0.8 | 25.0 | 29.2 | 22.28 ± 3.77 |
| mattcl-py | input-pting | 26.0 ± 0.8 | 24.8 | 29.1 | 22.38 ± 3.78 |
| pting | input-kcen | 26.5 ± 0.7 | 25.5 | 29.4 | 22.82 ± 3.85 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.9 | 29.5 | 23.08 ± 3.90 |
| pting | input-pting | 26.9 ± 0.8 | 25.6 | 30.0 | 23.19 ± 3.92 |
| pting | input-lanjian | 27.0 ± 0.9 | 25.7 | 29.9 | 23.24 ± 3.95 |
| kcen | input-lanjian | 47.8 ± 1.0 | 46.4 | 50.8 | 41.13 ± 6.91 |
| kcen | input-pting | 48.5 ± 6.7 | 45.8 | 92.1 | 41.79 ± 9.03 |
| kcen | input-mattcl | 49.9 ± 1.0 | 48.4 | 52.6 | 43.02 ± 7.22 |
| kcen | input-kcen | 50.7 ± 4.3 | 48.5 | 81.9 | 43.66 ± 8.17 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|