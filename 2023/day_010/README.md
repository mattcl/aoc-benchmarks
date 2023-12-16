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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.25 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.24 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 2.3 | 1.04 ± 0.24 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.6 | 2.44 ± 0.46 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.4 | 5.5 | 2.44 ± 0.44 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.5 | 5.5 | 2.44 ± 0.44 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.3 | 4.8 | 2.45 ± 0.47 |
| mattcl-ts | input-mattcl | 17.2 ± 0.4 | 16.1 | 18.7 | 13.84 ± 2.35 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.4 | 18.4 | 13.90 ± 2.35 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.1 | 19.3 | 13.93 ± 2.36 |
| mattcl-ts | input-lanjian | 17.4 ± 0.5 | 16.2 | 18.7 | 13.99 ± 2.38 |
| mattcl-py | input-kcen | 25.3 ± 0.8 | 24.3 | 28.5 | 20.34 ± 3.48 |
| mattcl-py | input-mattcl | 25.5 ± 0.7 | 24.5 | 28.8 | 20.45 ± 3.48 |
| mattcl-py | input-pting | 25.9 ± 0.8 | 24.7 | 29.3 | 20.84 ± 3.56 |
| mattcl-py | input-lanjian | 26.0 ± 0.8 | 25.0 | 28.6 | 20.90 ± 3.57 |
| pting | input-kcen | 26.8 ± 0.8 | 25.6 | 30.4 | 21.51 ± 3.67 |
| pting | input-mattcl | 26.9 ± 0.6 | 25.9 | 29.6 | 21.57 ± 3.66 |
| pting | input-pting | 27.0 ± 0.7 | 25.9 | 29.7 | 21.67 ± 3.68 |
| pting | input-lanjian | 27.0 ± 0.6 | 26.1 | 29.5 | 21.67 ± 3.68 |
| kcen | input-pting | 46.9 ± 0.9 | 45.8 | 48.9 | 37.68 ± 6.37 |
| kcen | input-lanjian | 48.0 ± 2.6 | 46.3 | 67.5 | 38.57 ± 6.81 |
| kcen | input-kcen | 49.9 ± 1.0 | 48.5 | 52.0 | 40.07 ± 6.78 |
| kcen | input-mattcl | 50.2 ± 1.2 | 48.4 | 53.8 | 40.28 ± 6.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|