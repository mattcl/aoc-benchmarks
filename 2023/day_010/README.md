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
| mattcl | input-pting | 1.3 ± 0.2 | 0.7 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.5 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.8 | 1.03 ± 0.19 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 1.8 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 3.1 ± 0.2 | 2.4 | 5.9 | 2.47 ± 0.40 |
| lanjian | input-lanjian | 3.1 ± 0.2 | 2.7 | 4.9 | 2.49 ± 0.39 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 5.8 | 2.49 ± 0.42 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.3 | 4.9 | 2.49 ± 0.40 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.2 | 18.7 | 13.79 ± 1.97 |
| mattcl-ts | input-kcen | 17.4 ± 0.4 | 16.5 | 18.8 | 13.81 ± 1.96 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.4 | 19.0 | 13.85 ± 1.98 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.5 | 18.5 | 13.88 ± 1.97 |
| mattcl-py | input-kcen | 25.6 ± 0.8 | 24.6 | 29.1 | 20.38 ± 2.93 |
| mattcl-py | input-mattcl | 26.0 ± 0.9 | 24.8 | 29.3 | 20.67 ± 2.98 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 25.1 | 29.5 | 20.84 ± 3.01 |
| mattcl-py | input-lanjian | 26.3 ± 0.8 | 25.2 | 29.6 | 20.94 ± 3.01 |
| pting | input-kcen | 26.8 ± 1.0 | 25.6 | 29.5 | 21.34 ± 3.09 |
| pting | input-lanjian | 27.1 ± 0.8 | 25.6 | 29.6 | 21.52 ± 3.09 |
| pting | input-mattcl | 27.1 ± 0.9 | 25.7 | 29.9 | 21.53 ± 3.11 |
| pting | input-pting | 27.2 ± 0.7 | 26.4 | 29.9 | 21.60 ± 3.08 |
| kcen | input-pting | 47.2 ± 1.1 | 45.7 | 51.0 | 37.54 ± 5.35 |
| kcen | input-lanjian | 47.9 ± 1.0 | 46.5 | 50.3 | 38.07 ± 5.40 |
| kcen | input-kcen | 50.1 ± 1.2 | 48.6 | 53.5 | 39.80 ± 5.67 |
| kcen | input-mattcl | 50.3 ± 1.2 | 48.8 | 53.1 | 40.02 ± 5.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|