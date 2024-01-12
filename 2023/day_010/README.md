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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.9 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.9 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 1.0 | 1.9 | 1.05 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.3 | 2.2 | 5.6 | 2.34 ± 0.45 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 4.9 | 2.34 ± 0.42 |
| lanjian | input-pting | 3.0 ± 0.3 | 2.3 | 5.9 | 2.36 ± 0.45 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.3 | 5.8 | 2.36 ± 0.45 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.3 | 18.7 | 13.54 ± 2.14 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.6 | 18.5 | 13.58 ± 2.14 |
| mattcl-ts | input-mattcl | 17.7 ± 3.7 | 16.4 | 66.1 | 13.76 ± 3.59 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.5 | 19.0 | 13.78 ± 2.19 |
| mattcl-py | input-kcen | 25.6 ± 0.6 | 24.2 | 27.1 | 19.84 ± 3.13 |
| mattcl-py | input-mattcl | 26.1 ± 1.0 | 24.5 | 29.7 | 20.20 ± 3.26 |
| mattcl-py | input-pting | 26.4 ± 1.1 | 24.5 | 29.1 | 20.44 ± 3.30 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.1 | 29.4 | 20.46 ± 3.27 |
| pting | input-kcen | 27.0 ± 0.6 | 26.1 | 29.6 | 20.95 ± 3.30 |
| pting | input-mattcl | 27.1 ± 0.7 | 26.1 | 29.3 | 21.01 ± 3.32 |
| pting | input-pting | 27.3 ± 0.8 | 25.7 | 30.3 | 21.15 ± 3.36 |
| pting | input-lanjian | 27.5 ± 1.4 | 26.3 | 41.0 | 21.35 ± 3.52 |
| kcen | input-pting | 47.7 ± 3.9 | 45.7 | 77.3 | 36.96 ± 6.53 |
| kcen | input-lanjian | 48.2 ± 1.0 | 46.5 | 51.2 | 37.36 ± 5.89 |
| kcen | input-mattcl | 50.4 ± 1.1 | 48.3 | 53.3 | 39.10 ± 6.16 |
| kcen | input-kcen | 50.6 ± 1.3 | 48.5 | 54.3 | 39.19 ± 6.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|