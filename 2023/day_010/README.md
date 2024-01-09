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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.6 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.8 | 2.0 | 1.04 ± 0.23 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.04 ± 0.23 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.5 | 2.2 | 1.12 ± 0.28 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.3 | 4.9 | 2.37 ± 0.45 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 4.8 | 2.38 ± 0.45 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.3 | 4.8 | 2.40 ± 0.44 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 5.7 | 2.40 ± 0.46 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.4 | 18.5 | 13.38 ± 2.37 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.4 | 18.5 | 13.41 ± 2.37 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.2 | 18.7 | 13.47 ± 2.38 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.3 | 18.9 | 13.55 ± 2.40 |
| mattcl-py | input-mattcl | 25.6 ± 0.7 | 24.6 | 28.1 | 19.83 ± 3.52 |
| mattcl-py | input-kcen | 25.7 ± 0.9 | 24.5 | 29.0 | 19.91 ± 3.56 |
| mattcl-py | input-pting | 25.8 ± 0.7 | 24.8 | 28.3 | 19.94 ± 3.53 |
| mattcl-py | input-lanjian | 26.1 ± 0.9 | 25.0 | 29.1 | 20.15 ± 3.60 |
| pting | input-kcen | 26.8 ± 1.0 | 25.3 | 30.3 | 20.69 ± 3.70 |
| pting | input-mattcl | 26.9 ± 0.7 | 26.1 | 29.6 | 20.80 ± 3.69 |
| pting | input-lanjian | 26.9 ± 0.7 | 25.9 | 30.2 | 20.83 ± 3.70 |
| pting | input-pting | 27.0 ± 0.8 | 25.9 | 30.4 | 20.91 ± 3.72 |
| kcen | input-pting | 47.1 ± 0.9 | 45.8 | 49.5 | 36.43 ± 6.43 |
| kcen | input-lanjian | 48.3 ± 1.1 | 46.6 | 52.1 | 37.34 ± 6.61 |
| kcen | input-kcen | 50.0 ± 1.0 | 48.5 | 52.6 | 38.63 ± 6.82 |
| kcen | input-mattcl | 50.1 ± 1.0 | 48.8 | 53.3 | 38.74 ± 6.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|