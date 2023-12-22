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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 2.0 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.9 | 1.03 ± 0.26 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.2 | 1.10 ± 0.28 |
| lanjian | input-mattcl | 2.9 ± 0.2 | 2.2 | 3.7 | 2.57 ± 0.50 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.2 | 3.6 | 2.58 ± 0.49 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 4.7 | 2.59 ± 0.52 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.3 | 4.8 | 2.60 ± 0.51 |
| mattcl-ts | input-mattcl | 17.1 ± 0.4 | 16.2 | 17.9 | 14.93 ± 2.74 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.2 | 18.5 | 14.99 ± 2.76 |
| mattcl-ts | input-pting | 17.2 ± 0.4 | 16.3 | 18.3 | 15.01 ± 2.76 |
| mattcl-ts | input-lanjian | 17.3 ± 0.4 | 16.2 | 18.9 | 15.10 ± 2.78 |
| mattcl-py | input-kcen | 25.3 ± 0.8 | 24.2 | 28.5 | 22.05 ± 4.09 |
| mattcl-py | input-mattcl | 25.6 ± 0.9 | 24.5 | 29.2 | 22.34 ± 4.16 |
| mattcl-py | input-pting | 26.0 ± 0.8 | 24.7 | 28.7 | 22.66 ± 4.20 |
| mattcl-py | input-lanjian | 26.0 ± 0.9 | 25.0 | 28.9 | 22.69 ± 4.22 |
| pting | input-kcen | 26.4 ± 0.7 | 25.5 | 29.2 | 23.05 ± 4.25 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.7 | 29.5 | 23.34 ± 4.32 |
| pting | input-pting | 26.8 ± 0.7 | 25.8 | 29.6 | 23.35 ± 4.30 |
| pting | input-lanjian | 26.9 ± 0.9 | 25.4 | 29.6 | 23.47 ± 4.36 |
| kcen | input-pting | 47.2 ± 1.1 | 45.7 | 50.0 | 41.13 ± 7.57 |
| kcen | input-lanjian | 47.9 ± 1.4 | 46.0 | 55.1 | 41.80 ± 7.73 |
| kcen | input-mattcl | 49.9 ± 1.1 | 48.4 | 55.2 | 43.52 ± 8.00 |
| kcen | input-kcen | 50.0 ± 1.0 | 48.0 | 53.1 | 43.63 ± 8.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|