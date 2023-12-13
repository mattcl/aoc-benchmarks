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
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 2.0 | 1.01 ± 0.20 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.7 | 2.1 | 1.06 ± 0.23 |
| lanjian | input-mattcl | 3.1 ± 4.2 | 1.9 | 48.6 | 2.36 ± 3.23 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.4 | 6.0 | 2.40 ± 0.42 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.8 | 2.41 ± 0.43 |
| lanjian | input-lanjian | 3.2 ± 0.4 | 2.4 | 6.2 | 2.44 ± 0.45 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.2 | 18.7 | 13.23 ± 1.95 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.3 | 18.8 | 13.30 ± 1.96 |
| mattcl-ts | input-pting | 17.4 ± 0.5 | 16.4 | 19.4 | 13.38 ± 1.98 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.7 | 13.41 ± 1.98 |
| mattcl-py | input-kcen | 25.8 ± 0.9 | 24.6 | 30.2 | 19.85 ± 2.97 |
| mattcl-py | input-pting | 26.2 ± 0.7 | 25.1 | 29.4 | 20.17 ± 2.98 |
| mattcl-py | input-mattcl | 26.3 ± 1.8 | 24.5 | 42.3 | 20.21 ± 3.24 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 24.5 | 30.3 | 20.22 ± 3.03 |
| pting | input-kcen | 26.9 ± 0.7 | 25.8 | 30.1 | 20.73 ± 3.07 |
| pting | input-mattcl | 27.2 ± 0.7 | 26.0 | 30.2 | 20.94 ± 3.10 |
| pting | input-lanjian | 27.2 ± 0.8 | 25.8 | 30.2 | 20.95 ± 3.11 |
| pting | input-pting | 27.5 ± 0.9 | 26.2 | 31.3 | 21.18 ± 3.16 |
| kcen | input-pting | 47.4 ± 0.9 | 46.0 | 50.6 | 36.49 ± 5.36 |
| kcen | input-lanjian | 47.7 ± 1.0 | 46.4 | 50.2 | 36.69 ± 5.39 |
| kcen | input-mattcl | 50.2 ± 1.1 | 48.2 | 53.1 | 38.64 ± 5.69 |
| kcen | input-kcen | 50.8 ± 1.8 | 48.7 | 61.3 | 39.08 ± 5.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|