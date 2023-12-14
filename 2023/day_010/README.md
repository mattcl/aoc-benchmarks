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
| mattcl | input-mattcl | 1.1 ± 1.7 | 0.3 | 25.2 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.4 | 1.04 ± 1.60 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.9 | 1.07 ± 1.63 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.07 ± 1.64 |
| lanjian | input-mattcl | 3.0 ± 3.0 | 1.8 | 45.1 | 2.61 ± 4.77 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.2 | 5.6 | 2.63 ± 4.01 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.3 | 5.6 | 2.63 ± 4.02 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 6.0 | 2.65 ± 4.05 |
| mattcl-ts | input-mattcl | 16.4 ± 0.5 | 15.4 | 17.4 | 14.32 ± 21.81 |
| mattcl-ts | input-kcen | 16.4 ± 0.5 | 15.4 | 17.7 | 14.36 ± 21.88 |
| mattcl-ts | input-pting | 16.6 ± 0.4 | 15.6 | 18.0 | 14.47 ± 22.04 |
| mattcl-ts | input-lanjian | 16.7 ± 0.4 | 15.6 | 17.8 | 14.54 ± 22.15 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.4 | 28.3 | 22.26 ± 33.91 |
| mattcl-py | input-pting | 25.9 ± 0.7 | 25.2 | 28.6 | 22.63 ± 34.48 |
| mattcl-py | input-lanjian | 26.0 ± 0.7 | 24.8 | 29.8 | 22.68 ± 34.56 |
| mattcl-py | input-mattcl | 26.0 ± 3.8 | 24.6 | 64.8 | 22.73 ± 34.77 |
| pting | input-kcen | 26.5 ± 0.8 | 25.6 | 29.3 | 23.16 ± 35.29 |
| pting | input-mattcl | 26.9 ± 1.1 | 25.7 | 35.0 | 23.49 ± 35.79 |
| pting | input-pting | 26.9 ± 0.8 | 25.6 | 29.5 | 23.53 ± 35.85 |
| pting | input-lanjian | 27.0 ± 0.9 | 25.8 | 29.8 | 23.53 ± 35.85 |
| kcen | input-pting | 47.0 ± 1.0 | 45.5 | 49.5 | 40.99 ± 62.45 |
| kcen | input-lanjian | 47.6 ± 0.9 | 46.2 | 50.3 | 41.59 ± 63.35 |
| kcen | input-kcen | 50.0 ± 1.2 | 48.2 | 53.0 | 43.65 ± 66.50 |
| kcen | input-mattcl | 50.4 ± 3.9 | 48.4 | 78.5 | 44.00 ± 67.10 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|