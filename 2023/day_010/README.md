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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.6 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.21 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.3 | 4.6 | 2.54 ± 0.42 |
| lanjian | input-kcen | 3.0 ± 0.3 | 2.2 | 5.7 | 2.55 ± 0.47 |
| lanjian | input-pting | 3.0 ± 0.2 | 2.3 | 5.6 | 2.55 ± 0.44 |
| lanjian | input-lanjian | 3.0 ± 0.3 | 2.3 | 5.9 | 2.56 ± 0.47 |
| mattcl-ts | input-kcen | 17.2 ± 0.4 | 16.1 | 18.5 | 14.63 ± 2.24 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.3 | 18.6 | 14.65 ± 2.24 |
| mattcl-ts | input-pting | 17.3 ± 0.4 | 16.3 | 18.5 | 14.67 ± 2.24 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.6 | 19.2 | 14.82 ± 2.27 |
| mattcl-py | input-kcen | 25.2 ± 0.9 | 24.3 | 28.8 | 21.39 ± 3.32 |
| mattcl-py | input-mattcl | 25.5 ± 0.7 | 24.3 | 28.7 | 21.64 ± 3.33 |
| mattcl-py | input-lanjian | 25.8 ± 0.7 | 24.9 | 28.8 | 21.91 ± 3.37 |
| mattcl-py | input-pting | 26.0 ± 0.9 | 24.8 | 28.9 | 22.07 ± 3.42 |
| pting | input-kcen | 26.7 ± 0.8 | 25.5 | 29.7 | 22.65 ± 3.50 |
| pting | input-mattcl | 26.8 ± 0.8 | 25.9 | 29.8 | 22.78 ± 3.51 |
| pting | input-pting | 27.0 ± 0.8 | 25.9 | 29.8 | 22.90 ± 3.53 |
| pting | input-lanjian | 27.2 ± 0.9 | 26.2 | 30.4 | 23.07 ± 3.57 |
| kcen | input-pting | 46.8 ± 0.9 | 45.4 | 49.2 | 39.78 ± 6.07 |
| kcen | input-lanjian | 47.8 ± 1.3 | 45.9 | 51.8 | 40.56 ± 6.23 |
| kcen | input-kcen | 49.9 ± 1.1 | 48.3 | 52.2 | 42.39 ± 6.48 |
| kcen | input-mattcl | 50.0 ± 0.9 | 48.7 | 52.2 | 42.44 ± 6.46 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|