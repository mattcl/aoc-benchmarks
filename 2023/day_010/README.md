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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.7 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.9 | 1.00 ± 0.19 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.01 ± 0.19 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 2.3 | 1.04 ± 0.21 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 4.8 | 2.42 ± 0.37 |
| lanjian | input-lanjian | 3.1 ± 0.1 | 2.8 | 3.5 | 2.44 ± 0.35 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.6 | 5.6 | 2.45 ± 0.39 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.9 | 2.46 ± 0.44 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.3 | 18.5 | 13.78 ± 1.92 |
| mattcl-ts | input-kcen | 17.3 ± 0.3 | 16.4 | 18.4 | 13.80 ± 1.92 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.5 | 18.9 | 13.88 ± 1.93 |
| mattcl-ts | input-mattcl | 17.5 ± 3.9 | 16.1 | 67.2 | 13.92 ± 3.65 |
| mattcl-py | input-kcen | 25.4 ± 0.8 | 24.3 | 28.2 | 20.20 ± 2.84 |
| mattcl-py | input-mattcl | 25.6 ± 0.7 | 24.7 | 28.2 | 20.38 ± 2.86 |
| mattcl-py | input-pting | 25.9 ± 0.9 | 24.8 | 29.4 | 20.63 ± 2.92 |
| mattcl-py | input-lanjian | 25.9 ± 0.8 | 24.8 | 29.1 | 20.66 ± 2.91 |
| pting | input-kcen | 26.8 ± 0.8 | 25.8 | 30.4 | 21.33 ± 3.00 |
| pting | input-lanjian | 27.0 ± 0.8 | 26.1 | 29.5 | 21.53 ± 3.02 |
| pting | input-pting | 27.1 ± 0.9 | 25.9 | 30.5 | 21.56 ± 3.05 |
| pting | input-mattcl | 27.2 ± 2.7 | 25.8 | 53.3 | 21.62 ± 3.65 |
| kcen | input-pting | 46.8 ± 1.0 | 45.4 | 49.8 | 37.25 ± 5.18 |
| kcen | input-lanjian | 47.6 ± 1.0 | 46.5 | 50.7 | 37.92 ± 5.27 |
| kcen | input-kcen | 49.7 ± 0.9 | 48.4 | 51.8 | 39.56 ± 5.48 |
| kcen | input-mattcl | 50.0 ± 1.3 | 48.3 | 53.9 | 39.84 ± 5.57 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|