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
| mattcl | input-pting | 1.3 ± 0.2 | 0.6 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.8 | 1.01 ± 0.24 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.02 ± 0.22 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.22 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.4 | 5.5 | 2.39 ± 0.44 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.4 | 4.8 | 2.40 ± 0.43 |
| lanjian | input-pting | 3.1 ± 0.4 | 2.4 | 6.1 | 2.41 ± 0.49 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.5 | 4.6 | 2.43 ± 0.45 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.5 | 18.9 | 13.60 ± 2.22 |
| mattcl-ts | input-pting | 17.6 ± 0.4 | 16.7 | 19.0 | 13.67 ± 2.23 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.8 | 19.0 | 13.79 ± 2.25 |
| mattcl-ts | input-kcen | 17.9 ± 3.8 | 16.4 | 65.7 | 13.85 ± 3.67 |
| mattcl-py | input-kcen | 26.0 ± 1.0 | 24.7 | 29.3 | 20.19 ± 3.34 |
| mattcl-py | input-mattcl | 26.2 ± 1.1 | 24.9 | 29.4 | 20.31 ± 3.38 |
| mattcl-py | input-pting | 26.3 ± 0.8 | 24.9 | 29.4 | 20.38 ± 3.34 |
| mattcl-py | input-lanjian | 26.4 ± 0.7 | 25.2 | 29.7 | 20.44 ± 3.34 |
| pting | input-mattcl | 27.0 ± 0.7 | 26.0 | 29.7 | 20.97 ± 3.42 |
| pting | input-kcen | 27.2 ± 0.8 | 26.2 | 29.9 | 21.10 ± 3.46 |
| pting | input-lanjian | 27.3 ± 0.6 | 26.4 | 29.7 | 21.17 ± 3.44 |
| pting | input-pting | 27.4 ± 1.2 | 25.9 | 35.5 | 21.24 ± 3.54 |
| kcen | input-pting | 47.2 ± 1.1 | 45.1 | 50.7 | 36.61 ± 5.97 |
| kcen | input-lanjian | 48.6 ± 1.2 | 46.8 | 51.8 | 37.69 ± 6.15 |
| kcen | input-mattcl | 50.4 ± 0.9 | 48.9 | 53.5 | 39.09 ± 6.34 |
| kcen | input-kcen | 50.4 ± 1.1 | 48.5 | 53.3 | 39.11 ± 6.36 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|