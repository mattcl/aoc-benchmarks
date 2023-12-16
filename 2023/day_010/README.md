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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.4 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.5 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-kcen | 3.0 ± 0.2 | 2.2 | 4.7 | 2.56 ± 0.42 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.2 | 4.6 | 2.57 ± 0.42 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.2 | 5.6 | 2.58 ± 0.44 |
| lanjian | input-lanjian | 3.0 ± 0.4 | 2.3 | 6.0 | 2.61 ± 0.54 |
| mattcl-ts | input-mattcl | 17.1 ± 0.4 | 16.1 | 18.5 | 14.79 ± 2.27 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.3 | 18.3 | 14.90 ± 2.28 |
| mattcl-ts | input-lanjian | 17.3 ± 0.4 | 16.2 | 18.6 | 14.92 ± 2.29 |
| mattcl-ts | input-kcen | 18.3 ± 7.0 | 16.2 | 68.8 | 15.80 ± 6.52 |
| mattcl-py | input-kcen | 25.3 ± 0.9 | 24.4 | 28.3 | 21.86 ± 3.40 |
| mattcl-py | input-mattcl | 25.4 ± 0.8 | 24.1 | 28.6 | 21.93 ± 3.39 |
| mattcl-py | input-pting | 25.8 ± 0.8 | 24.6 | 29.1 | 22.26 ± 3.45 |
| mattcl-py | input-lanjian | 25.9 ± 0.8 | 24.9 | 28.8 | 22.39 ± 3.47 |
| pting | input-kcen | 26.5 ± 0.7 | 25.5 | 29.5 | 22.90 ± 3.53 |
| pting | input-mattcl | 26.8 ± 0.9 | 25.3 | 29.7 | 23.16 ± 3.61 |
| pting | input-lanjian | 26.9 ± 0.6 | 26.0 | 29.3 | 23.19 ± 3.56 |
| pting | input-pting | 27.0 ± 0.8 | 26.1 | 29.9 | 23.27 ± 3.59 |
| kcen | input-pting | 46.7 ± 1.1 | 45.4 | 50.6 | 40.35 ± 6.19 |
| kcen | input-lanjian | 47.7 ± 1.1 | 46.1 | 50.4 | 41.21 ± 6.32 |
| kcen | input-kcen | 49.8 ± 1.0 | 48.5 | 52.4 | 43.00 ± 6.59 |
| kcen | input-mattcl | 50.1 ± 1.8 | 48.2 | 59.6 | 43.25 ± 6.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|