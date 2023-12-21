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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.1 | 1.03 ± 0.25 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.22 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.3 | 1.05 ± 0.25 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 5.6 | 2.36 ± 0.45 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.6 | 2.39 ± 0.47 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.6 | 5.6 | 2.39 ± 0.45 |
| lanjian | input-mattcl | 3.2 ± 2.7 | 1.9 | 41.1 | 2.45 ± 2.14 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.5 | 19.3 | 13.57 ± 2.25 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.7 | 18.9 | 13.61 ± 2.25 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.8 | 19.1 | 13.66 ± 2.26 |
| mattcl-ts | input-lanjian | 17.7 ± 0.4 | 16.7 | 18.9 | 13.73 ± 2.28 |
| mattcl-py | input-kcen | 25.8 ± 0.8 | 24.6 | 28.5 | 19.96 ± 3.32 |
| mattcl-py | input-mattcl | 25.8 ± 0.8 | 24.5 | 29.9 | 19.97 ± 3.33 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 24.5 | 29.8 | 20.33 ± 3.40 |
| mattcl-py | input-pting | 26.3 ± 1.1 | 24.9 | 30.9 | 20.39 ± 3.45 |
| pting | input-kcen | 27.1 ± 0.8 | 25.8 | 29.9 | 20.95 ± 3.49 |
| pting | input-pting | 27.3 ± 0.7 | 26.2 | 29.7 | 21.14 ± 3.51 |
| pting | input-mattcl | 27.4 ± 1.1 | 26.2 | 34.5 | 21.20 ± 3.57 |
| pting | input-lanjian | 27.8 ± 2.7 | 26.5 | 54.7 | 21.55 ± 4.12 |
| kcen | input-pting | 47.5 ± 1.0 | 46.0 | 50.3 | 36.78 ± 6.08 |
| kcen | input-lanjian | 48.7 ± 1.6 | 46.5 | 54.0 | 37.70 ± 6.30 |
| kcen | input-kcen | 50.5 ± 1.1 | 48.4 | 53.0 | 39.06 ± 6.46 |
| kcen | input-mattcl | 50.7 ± 1.1 | 48.7 | 52.9 | 39.25 ± 6.49 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|