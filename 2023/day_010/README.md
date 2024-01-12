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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.0 | 1.02 ± 0.24 |
| mattcl | input-kcen | 1.4 ± 0.2 | 0.8 | 2.0 | 1.03 ± 0.22 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.9 | 1.06 ± 0.23 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.3 | 3.7 | 2.34 ± 0.40 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.3 | 3.9 | 2.34 ± 0.40 |
| lanjian | input-pting | 3.1 ± 0.2 | 2.2 | 4.9 | 2.34 ± 0.42 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 6.1 | 2.37 ± 0.45 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.3 | 18.4 | 13.10 ± 2.14 |
| mattcl-ts | input-kcen | 17.3 ± 0.4 | 16.2 | 18.6 | 13.12 ± 2.14 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.3 | 18.5 | 13.14 ± 2.15 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.7 | 18.3 | 13.22 ± 2.15 |
| mattcl-py | input-kcen | 25.5 ± 0.9 | 24.5 | 28.9 | 19.31 ± 3.19 |
| mattcl-py | input-mattcl | 25.5 ± 0.8 | 24.6 | 28.9 | 19.36 ± 3.18 |
| mattcl-py | input-lanjian | 25.8 ± 0.7 | 24.5 | 28.4 | 19.53 ± 3.20 |
| mattcl-py | input-pting | 25.9 ± 0.9 | 24.6 | 29.5 | 19.66 ± 3.25 |
| pting | input-lanjian | 26.9 ± 0.8 | 25.8 | 30.3 | 20.36 ± 3.34 |
| pting | input-kcen | 26.9 ± 0.9 | 25.7 | 29.6 | 20.36 ± 3.35 |
| pting | input-pting | 27.0 ± 0.9 | 25.9 | 30.2 | 20.44 ± 3.37 |
| pting | input-mattcl | 27.0 ± 0.8 | 26.0 | 29.6 | 20.45 ± 3.36 |
| kcen | input-lanjian | 47.9 ± 1.0 | 46.3 | 50.7 | 36.28 ± 5.91 |
| kcen | input-pting | 48.2 ± 4.7 | 45.3 | 80.9 | 36.50 ± 6.89 |
| kcen | input-mattcl | 50.0 ± 0.9 | 48.2 | 52.5 | 37.86 ± 6.15 |
| kcen | input-kcen | 50.1 ± 1.3 | 48.0 | 54.2 | 37.95 ± 6.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|