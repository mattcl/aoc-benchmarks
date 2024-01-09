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
| mattcl | input-pting | 1.2 ± 0.3 | 0.5 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.9 | 1.07 ± 0.29 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.07 ± 0.28 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.1 | 1.07 ± 0.30 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 4.8 | 2.46 ± 0.60 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.5 | 2.48 ± 0.61 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.3 | 4.8 | 2.48 ± 0.60 |
| lanjian | input-pting | 3.2 ± 3.0 | 2.1 | 45.1 | 2.62 ± 2.50 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.6 | 18.9 | 14.32 ± 3.28 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.5 | 18.7 | 14.34 ± 3.28 |
| mattcl-ts | input-pting | 17.7 ± 0.5 | 16.4 | 19.2 | 14.37 ± 3.29 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.8 | 19.3 | 14.50 ± 3.32 |
| mattcl-py | input-kcen | 25.7 ± 0.9 | 24.1 | 29.2 | 20.90 ± 4.81 |
| mattcl-py | input-mattcl | 25.9 ± 0.6 | 24.7 | 28.9 | 21.07 ± 4.82 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 25.0 | 29.3 | 21.37 ± 4.91 |
| mattcl-py | input-pting | 26.3 ± 1.2 | 24.5 | 32.0 | 21.40 ± 4.97 |
| pting | input-kcen | 27.0 ± 0.9 | 25.7 | 30.4 | 21.99 ± 5.06 |
| pting | input-mattcl | 27.0 ± 0.9 | 25.6 | 30.3 | 22.00 ± 5.05 |
| pting | input-pting | 27.1 ± 0.7 | 26.1 | 30.0 | 22.09 ± 5.06 |
| pting | input-lanjian | 27.3 ± 0.8 | 25.8 | 30.7 | 22.26 ± 5.11 |
| kcen | input-pting | 47.3 ± 1.0 | 45.7 | 50.6 | 38.52 ± 8.80 |
| kcen | input-lanjian | 48.3 ± 1.1 | 46.7 | 51.7 | 39.33 ± 9.00 |
| kcen | input-kcen | 50.6 ± 1.2 | 48.3 | 53.2 | 41.22 ± 9.43 |
| kcen | input-mattcl | 50.7 ± 1.2 | 48.9 | 54.0 | 41.31 ± 9.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|