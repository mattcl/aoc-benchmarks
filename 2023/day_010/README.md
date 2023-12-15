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
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.20 |
| mattcl | input-pting | 1.7 ± 0.1 | 1.5 | 2.3 | 1.39 ± 0.24 |
| lanjian | input-lanjian | 3.1 ± 0.1 | 2.2 | 3.3 | 2.47 ± 0.39 |
| lanjian | input-kcen | 3.1 ± 0.2 | 2.1 | 5.2 | 2.47 ± 0.41 |
| lanjian | input-mattcl | 3.1 ± 0.4 | 2.2 | 5.8 | 2.49 ± 0.48 |
| lanjian | input-pting | 6.8 ± 5.2 | 4.8 | 27.2 | 5.47 ± 4.31 |
| mattcl-ts | input-kcen | 17.3 ± 0.3 | 16.3 | 18.4 | 13.91 ± 2.15 |
| mattcl-ts | input-mattcl | 17.4 ± 0.4 | 16.3 | 18.6 | 13.97 ± 2.17 |
| mattcl-ts | input-lanjian | 17.4 ± 0.4 | 16.6 | 18.6 | 14.04 ± 2.18 |
| mattcl-py | input-kcen | 25.6 ± 0.9 | 24.4 | 28.8 | 20.60 ± 3.24 |
| mattcl-py | input-mattcl | 25.8 ± 0.9 | 24.6 | 29.9 | 20.75 ± 3.26 |
| mattcl-py | input-lanjian | 26.3 ± 0.9 | 25.0 | 29.4 | 21.15 ± 3.33 |
| pting | input-kcen | 26.5 ± 0.6 | 25.6 | 29.1 | 21.35 ± 3.31 |
| pting | input-mattcl | 27.1 ± 0.9 | 25.9 | 30.7 | 21.81 ± 3.42 |
| pting | input-lanjian | 27.2 ± 1.0 | 25.8 | 31.2 | 21.90 ± 3.46 |
| kcen | input-lanjian | 47.8 ± 1.0 | 46.4 | 50.7 | 38.46 ± 5.96 |
| kcen | input-mattcl | 50.1 ± 1.1 | 48.7 | 53.5 | 40.34 ± 6.26 |
| kcen | input-kcen | 50.3 ± 1.4 | 48.7 | 57.7 | 40.49 ± 6.32 |
| pting | input-pting | 60.2 ± 13.3 | 36.2 | 77.1 | 48.48 ± 13.07 |
| mattcl-py | input-pting | 61.7 ± 4.0 | 53.5 | 70.8 | 49.67 ± 8.27 |
| kcen | input-pting | 84.8 ± 36.3 | 46.5 | 139.3 | 68.24 ± 31.03 |
| mattcl-ts | input-pting | 182.1 ± 65.9 | 83.4 | 287.6 | 146.53 ± 57.63 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|