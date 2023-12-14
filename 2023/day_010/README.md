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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.6 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.17 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.5 | 1.8 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.1 | 1.02 ± 0.19 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 3.5 | 2.36 ± 0.30 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 4.9 | 2.36 ± 0.32 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 6.0 | 2.37 ± 0.34 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.8 | 2.39 ± 0.32 |
| mattcl-ts | input-mattcl | 16.3 ± 0.5 | 15.1 | 18.1 | 12.44 ± 1.51 |
| mattcl-ts | input-kcen | 16.3 ± 0.4 | 15.2 | 18.0 | 12.45 ± 1.50 |
| mattcl-ts | input-pting | 16.4 ± 0.4 | 15.3 | 17.4 | 12.48 ± 1.51 |
| mattcl-ts | input-lanjian | 16.5 ± 0.5 | 15.2 | 18.0 | 12.57 ± 1.52 |
| mattcl-py | input-kcen | 25.5 ± 0.8 | 24.6 | 28.6 | 19.46 ± 2.38 |
| mattcl-py | input-mattcl | 26.0 ± 1.0 | 24.9 | 29.5 | 19.78 ± 2.45 |
| mattcl-py | input-pting | 26.2 ± 0.7 | 25.2 | 28.9 | 19.95 ± 2.42 |
| mattcl-py | input-lanjian | 26.5 ± 1.1 | 25.0 | 29.7 | 20.15 ± 2.52 |
| pting | input-mattcl | 27.0 ± 0.9 | 25.6 | 29.9 | 20.55 ± 2.52 |
| pting | input-lanjian | 27.0 ± 0.8 | 25.6 | 30.1 | 20.60 ± 2.50 |
| pting | input-kcen | 27.1 ± 3.3 | 25.8 | 60.2 | 20.64 ± 3.47 |
| pting | input-pting | 27.1 ± 0.7 | 26.0 | 29.4 | 20.66 ± 2.49 |
| kcen | input-pting | 47.3 ± 1.1 | 45.6 | 50.6 | 36.04 ± 4.33 |
| kcen | input-lanjian | 48.7 ± 4.4 | 46.4 | 81.7 | 37.14 ± 5.51 |
| kcen | input-mattcl | 50.2 ± 1.2 | 48.4 | 54.5 | 38.28 ± 4.60 |
| kcen | input-kcen | 50.4 ± 1.4 | 48.5 | 56.3 | 38.38 ± 4.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|