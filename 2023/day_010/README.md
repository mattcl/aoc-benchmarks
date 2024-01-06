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
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 2.3 | 1.00 |
| mattcl | input-pting | 1.5 ± 0.2 | 0.6 | 2.2 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 0.9 | 2.3 | 1.03 ± 0.21 |
| mattcl | input-kcen | 1.5 ± 0.2 | 0.8 | 2.3 | 1.04 ± 0.22 |
| lanjian | input-kcen | 3.2 ± 0.2 | 2.8 | 4.3 | 2.20 ± 0.37 |
| lanjian | input-pting | 3.2 ± 0.3 | 2.5 | 6.3 | 2.21 ± 0.40 |
| lanjian | input-mattcl | 3.2 ± 0.3 | 2.4 | 5.8 | 2.21 ± 0.40 |
| lanjian | input-lanjian | 3.2 ± 0.2 | 2.7 | 5.0 | 2.22 ± 0.39 |
| mattcl-ts | input-mattcl | 17.3 ± 0.4 | 16.3 | 18.9 | 11.97 ± 1.93 |
| mattcl-ts | input-pting | 17.4 ± 0.4 | 16.2 | 18.6 | 12.01 ± 1.94 |
| mattcl-ts | input-lanjian | 17.5 ± 0.4 | 16.4 | 18.7 | 12.10 ± 1.96 |
| mattcl-ts | input-kcen | 17.9 ± 4.8 | 16.2 | 67.3 | 12.35 ± 3.85 |
| mattcl-py | input-kcen | 26.0 ± 1.0 | 24.9 | 31.3 | 17.99 ± 2.96 |
| mattcl-py | input-pting | 26.2 ± 0.8 | 25.0 | 29.3 | 18.09 ± 2.94 |
| mattcl-py | input-mattcl | 26.2 ± 1.0 | 24.4 | 30.5 | 18.09 ± 2.98 |
| mattcl-py | input-lanjian | 26.3 ± 0.8 | 25.2 | 29.2 | 18.18 ± 2.96 |
| pting | input-mattcl | 27.3 ± 0.8 | 26.1 | 30.7 | 18.86 ± 3.07 |
| pting | input-lanjian | 27.3 ± 0.8 | 26.3 | 30.6 | 18.91 ± 3.07 |
| pting | input-pting | 27.5 ± 0.8 | 26.3 | 30.3 | 19.02 ± 3.09 |
| pting | input-kcen | 27.6 ± 4.1 | 25.5 | 69.0 | 19.10 ± 4.19 |
| kcen | input-pting | 47.4 ± 0.9 | 45.4 | 49.6 | 32.75 ± 5.27 |
| kcen | input-lanjian | 48.7 ± 1.1 | 46.8 | 51.2 | 33.67 ± 5.43 |
| kcen | input-kcen | 50.4 ± 1.1 | 48.5 | 53.0 | 34.87 ± 5.62 |
| kcen | input-mattcl | 50.6 ± 1.1 | 48.7 | 53.2 | 34.97 ± 5.64 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|
|input-pting|<pre>7005</pre>|<pre>417</pre>|