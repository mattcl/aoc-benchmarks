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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 1.8 | 1.05 ± 0.24 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 2.1 | 1.10 ± 0.25 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 5.6 | 2.51 ± 0.46 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 4.7 | 2.53 ± 0.46 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.4 | 5.7 | 2.53 ± 0.49 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.6 | 2.54 ± 0.48 |
| mattcl-ts | input-mattcl | 16.9 ± 0.4 | 16.0 | 18.4 | 14.09 ± 2.31 |
| mattcl-ts | input-kcen | 17.0 ± 0.5 | 15.7 | 18.5 | 14.10 ± 2.32 |
| mattcl-ts | input-pting | 17.0 ± 0.4 | 16.1 | 17.8 | 14.14 ± 2.32 |
| mattcl-ts | input-lanjian | 17.2 ± 0.4 | 16.0 | 18.3 | 14.27 ± 2.34 |
| mattcl-py | input-kcen | 25.8 ± 1.0 | 24.3 | 29.3 | 21.43 ± 3.58 |
| mattcl-py | input-mattcl | 25.8 ± 0.9 | 24.7 | 29.4 | 21.46 ± 3.56 |
| mattcl-py | input-pting | 26.2 ± 1.0 | 24.8 | 29.6 | 21.77 ± 3.62 |
| mattcl-py | input-lanjian | 26.3 ± 1.2 | 24.8 | 32.7 | 21.89 ± 3.68 |
| pting | input-kcen | 26.9 ± 0.6 | 25.3 | 29.4 | 22.33 ± 3.66 |
| pting | input-mattcl | 27.0 ± 0.6 | 25.5 | 29.8 | 22.48 ± 3.68 |
| pting | input-lanjian | 27.0 ± 0.6 | 26.0 | 29.2 | 22.49 ± 3.68 |
| pting | input-pting | 27.1 ± 0.7 | 26.1 | 29.9 | 22.54 ± 3.70 |
| kcen | input-pting | 47.9 ± 5.3 | 45.3 | 88.1 | 39.82 ± 7.82 |
| kcen | input-lanjian | 48.3 ± 1.3 | 46.1 | 52.3 | 40.13 ± 6.60 |
| kcen | input-mattcl | 50.1 ± 1.2 | 48.4 | 52.7 | 41.68 ± 6.82 |
| kcen | input-kcen | 50.4 ± 0.9 | 48.5 | 53.1 | 41.92 ± 6.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|