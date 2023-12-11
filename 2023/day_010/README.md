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


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.8 ± 0.2 | 0.8 | 2.3 | 1.00 |
| mattcl | input-mattcl | 1.9 ± 0.2 | 0.9 | 2.5 | 1.00 ± 0.18 |
| mattcl | input-kcen | 1.9 ± 0.1 | 1.1 | 2.2 | 1.03 ± 0.14 |
| lanjian | input-lanjian | 3.1 ± 0.3 | 2.4 | 4.7 | 1.67 ± 0.26 |
| lanjian | input-mattcl | 3.1 ± 0.3 | 2.3 | 5.7 | 1.69 ± 0.27 |
| lanjian | input-kcen | 3.2 ± 0.4 | 2.3 | 5.8 | 1.71 ± 0.29 |
| mattcl-ts | input-kcen | 17.6 ± 0.4 | 16.7 | 18.7 | 9.53 ± 1.14 |
| mattcl-ts | input-lanjian | 17.8 ± 0.5 | 16.6 | 19.8 | 9.64 ± 1.17 |
| mattcl-ts | input-mattcl | 17.8 ± 3.5 | 16.3 | 63.1 | 9.65 ± 2.22 |
| mattcl-py | input-kcen | 39.0 ± 0.9 | 37.6 | 41.9 | 21.07 ± 2.53 |
| mattcl-py | input-lanjian | 40.0 ± 1.0 | 38.0 | 42.7 | 21.62 ± 2.61 |
| mattcl-py | input-mattcl | 40.0 ± 4.1 | 37.7 | 70.9 | 21.63 ± 3.37 |
| kcen | input-lanjian | 49.5 ± 1.0 | 48.1 | 52.9 | 26.80 ± 3.20 |
| kcen | input-kcen | 51.5 ± 1.0 | 49.6 | 54.2 | 27.85 ± 3.33 |
| kcen | input-mattcl | 51.5 ± 0.8 | 49.9 | 53.8 | 27.88 ± 3.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6778</pre>|<pre>433</pre>|
|input-lanjian|<pre>7066</pre>|<pre>401</pre>|
|input-mattcl|<pre>6860</pre>|<pre>343</pre>|