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
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.1 | 1.00 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.9 | 1.6 | 1.00 ± 0.19 |
| mattcl | input-pting | 1.4 ± 0.2 | 0.5 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.9 | 2.1 | 1.03 ± 0.22 |
| lanjian | input-kcen | 3.2 ± 0.3 | 2.5 | 5.7 | 2.34 ± 0.40 |
| lanjian | input-mattcl | 3.2 ± 0.4 | 2.5 | 6.0 | 2.34 ± 0.43 |
| lanjian | input-lanjian | 3.2 ± 0.3 | 2.5 | 5.8 | 2.35 ± 0.42 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.5 | 5.8 | 2.38 ± 0.43 |
| mattcl-ts | input-mattcl | 16.8 ± 0.4 | 15.6 | 17.6 | 12.47 ± 1.85 |
| mattcl-ts | input-pting | 17.0 ± 0.4 | 16.0 | 18.1 | 12.57 ± 1.87 |
| mattcl-ts | input-lanjian | 17.1 ± 0.4 | 15.7 | 18.5 | 12.63 ± 1.88 |
| mattcl-ts | input-kcen | 17.2 ± 2.7 | 16.0 | 51.6 | 12.71 ± 2.71 |
| mattcl-py | input-kcen | 25.5 ± 0.8 | 24.3 | 28.4 | 18.89 ± 2.83 |
| mattcl-py | input-mattcl | 25.9 ± 0.9 | 24.3 | 28.8 | 19.15 ± 2.90 |
| mattcl-py | input-lanjian | 26.1 ± 1.1 | 25.1 | 31.0 | 19.36 ± 2.95 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 25.2 | 29.4 | 19.41 ± 2.93 |
| pting | input-kcen | 26.8 ± 0.9 | 25.6 | 29.5 | 19.81 ± 2.98 |
| pting | input-mattcl | 26.8 ± 0.7 | 25.7 | 29.4 | 19.83 ± 2.95 |
| pting | input-lanjian | 26.9 ± 0.7 | 26.1 | 30.4 | 19.92 ± 2.97 |
| pting | input-pting | 26.9 ± 0.8 | 26.0 | 30.2 | 19.94 ± 2.99 |
| kcen | input-pting | 47.2 ± 1.1 | 45.5 | 50.2 | 34.94 ± 5.19 |
| kcen | input-lanjian | 47.6 ± 1.0 | 45.9 | 50.8 | 35.27 ± 5.23 |
| kcen | input-mattcl | 49.9 ± 1.1 | 48.1 | 52.9 | 36.98 ± 5.49 |
| kcen | input-kcen | 50.2 ± 1.2 | 48.2 | 54.3 | 37.20 ± 5.53 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|