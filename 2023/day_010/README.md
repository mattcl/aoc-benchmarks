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
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 2.0 | 1.00 |
| mattcl | input-pting | 1.3 ± 0.2 | 0.4 | 2.1 | 1.00 ± 0.23 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.0 | 1.01 ± 0.21 |
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.8 | 2.1 | 1.03 ± 0.21 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.4 | 6.0 | 2.33 ± 0.40 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.6 | 5.9 | 2.35 ± 0.43 |
| lanjian | input-kcen | 3.1 ± 0.4 | 2.2 | 5.8 | 2.35 ± 0.45 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 5.8 | 2.36 ± 0.43 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.5 | 18.6 | 13.29 ± 2.00 |
| mattcl-ts | input-mattcl | 17.6 ± 0.4 | 16.5 | 18.8 | 13.30 ± 2.01 |
| mattcl-ts | input-pting | 17.7 ± 0.4 | 16.6 | 19.5 | 13.36 ± 2.02 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.8 | 19.9 | 13.43 ± 2.03 |
| mattcl-py | input-kcen | 26.0 ± 0.9 | 24.8 | 29.4 | 19.65 ± 3.01 |
| mattcl-py | input-mattcl | 26.2 ± 0.9 | 24.9 | 29.3 | 19.83 ± 3.03 |
| mattcl-py | input-lanjian | 26.5 ± 0.8 | 25.2 | 29.3 | 20.02 ± 3.04 |
| mattcl-py | input-pting | 26.5 ± 1.0 | 24.8 | 29.6 | 20.02 ± 3.07 |
| pting | input-kcen | 27.0 ± 0.7 | 25.9 | 29.9 | 20.45 ± 3.09 |
| pting | input-mattcl | 27.2 ± 0.8 | 25.8 | 30.2 | 20.60 ± 3.13 |
| pting | input-lanjian | 27.3 ± 0.7 | 26.3 | 30.2 | 20.69 ± 3.13 |
| pting | input-pting | 27.4 ± 0.9 | 26.2 | 30.8 | 20.71 ± 3.16 |
| kcen | input-pting | 47.7 ± 1.3 | 45.7 | 52.0 | 36.10 ± 5.47 |
| kcen | input-lanjian | 48.4 ± 1.2 | 46.6 | 51.7 | 36.65 ± 5.54 |
| kcen | input-kcen | 50.6 ± 1.0 | 48.7 | 53.2 | 38.27 ± 5.76 |
| kcen | input-mattcl | 50.8 ± 1.2 | 48.6 | 53.2 | 38.42 ± 5.79 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|