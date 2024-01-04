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
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.7 | 2.2 | 1.04 ± 0.23 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.0 | 1.04 ± 0.20 |
| mattcl | input-pting | 1.4 ± 2.1 | 0.4 | 30.0 | 1.05 ± 1.58 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 5.6 | 2.35 ± 0.37 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.2 | 5.6 | 2.36 ± 0.40 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.4 | 4.8 | 2.37 ± 0.35 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.9 | 2.38 ± 0.41 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.4 | 18.4 | 13.22 ± 1.80 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.3 | 18.6 | 13.24 ± 1.81 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.4 | 18.4 | 13.28 ± 1.81 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.7 | 13.32 ± 1.82 |
| mattcl-py | input-kcen | 25.5 ± 0.8 | 24.4 | 28.6 | 19.55 ± 2.69 |
| mattcl-py | input-mattcl | 25.7 ± 0.7 | 24.5 | 28.5 | 19.65 ± 2.70 |
| mattcl-py | input-lanjian | 26.0 ± 0.7 | 24.7 | 29.2 | 19.94 ± 2.74 |
| mattcl-py | input-pting | 26.2 ± 1.2 | 25.2 | 36.1 | 20.07 ± 2.85 |
| pting | input-kcen | 26.6 ± 0.8 | 25.6 | 29.5 | 20.38 ± 2.81 |
| pting | input-mattcl | 26.8 ± 0.9 | 25.6 | 29.6 | 20.54 ± 2.84 |
| pting | input-pting | 27.0 ± 0.8 | 25.8 | 29.8 | 20.69 ± 2.85 |
| pting | input-lanjian | 27.1 ± 0.9 | 25.9 | 30.3 | 20.74 ± 2.88 |
| kcen | input-pting | 47.5 ± 1.1 | 45.5 | 50.3 | 36.33 ± 4.97 |
| kcen | input-lanjian | 47.8 ± 1.2 | 46.1 | 52.2 | 36.63 ± 5.01 |
| kcen | input-mattcl | 49.9 ± 0.9 | 48.5 | 52.2 | 38.23 ± 5.20 |
| kcen | input-kcen | 50.2 ± 1.6 | 48.1 | 58.7 | 38.42 ± 5.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|