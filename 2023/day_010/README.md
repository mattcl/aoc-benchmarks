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
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.22 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.20 |
| lanjian | input-mattcl | 3.0 ± 0.2 | 2.4 | 4.7 | 2.45 ± 0.41 |
| lanjian | input-lanjian | 3.0 ± 0.2 | 2.3 | 3.8 | 2.45 ± 0.41 |
| lanjian | input-kcen | 3.1 ± 0.3 | 2.5 | 4.8 | 2.48 ± 0.44 |
| lanjian | input-pting | 3.1 ± 0.3 | 2.3 | 5.5 | 2.49 ± 0.45 |
| mattcl-ts | input-kcen | 17.5 ± 0.4 | 16.6 | 18.6 | 14.20 ± 2.23 |
| mattcl-ts | input-mattcl | 17.5 ± 0.4 | 16.6 | 18.8 | 14.21 ± 2.23 |
| mattcl-ts | input-pting | 17.5 ± 0.4 | 16.4 | 18.9 | 14.24 ± 2.24 |
| mattcl-ts | input-lanjian | 17.7 ± 0.5 | 16.8 | 19.4 | 14.36 ± 2.26 |
| mattcl-py | input-kcen | 25.8 ± 1.0 | 24.5 | 32.8 | 20.95 ± 3.37 |
| mattcl-py | input-mattcl | 26.1 ± 1.1 | 24.4 | 31.9 | 21.21 ± 3.42 |
| mattcl-py | input-pting | 26.2 ± 0.9 | 25.0 | 29.5 | 21.32 ± 3.39 |
| mattcl-py | input-lanjian | 26.4 ± 0.9 | 25.1 | 29.2 | 21.44 ± 3.41 |
| pting | input-kcen | 27.0 ± 0.8 | 25.5 | 30.0 | 21.91 ± 3.47 |
| pting | input-lanjian | 27.2 ± 0.7 | 26.3 | 29.8 | 22.10 ± 3.49 |
| pting | input-pting | 27.2 ± 0.7 | 26.0 | 30.2 | 22.10 ± 3.48 |
| pting | input-mattcl | 27.3 ± 0.9 | 26.0 | 30.6 | 22.14 ± 3.53 |
| kcen | input-pting | 47.0 ± 1.1 | 45.6 | 50.4 | 38.17 ± 6.00 |
| kcen | input-lanjian | 48.1 ± 1.2 | 46.2 | 52.2 | 39.08 ± 6.16 |
| kcen | input-mattcl | 50.0 ± 1.1 | 48.4 | 53.3 | 40.65 ± 6.39 |
| kcen | input-kcen | 50.4 ± 1.3 | 48.0 | 53.4 | 40.94 ± 6.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|