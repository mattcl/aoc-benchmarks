# Day 7 benchmarks

[link to problem](https://adventofcode.com/2023/day/7)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 7)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.25 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.9 | 1.03 ± 0.22 |
| lanjian | input-pting | 1.4 ± 0.2 | 0.8 | 1.8 | 1.13 ± 0.24 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.8 | 2.0 | 1.14 ± 0.24 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.8 | 1.7 | 1.16 ± 0.24 |
| mattcl-py | input-kcen | 17.5 ± 0.7 | 16.6 | 20.8 | 14.23 ± 2.34 |
| mattcl-py | input-pting | 17.6 ± 0.7 | 16.4 | 20.7 | 14.27 ± 2.35 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.6 | 20.8 | 14.27 ± 2.35 |
| pting | input-pting | 17.9 ± 0.6 | 17.1 | 21.0 | 14.57 ± 2.39 |
| pting | input-kcen | 18.1 ± 0.7 | 17.2 | 20.9 | 14.66 ± 2.42 |
| pting | input-mattcl | 18.1 ± 0.8 | 17.0 | 21.0 | 14.67 ± 2.44 |
| mattcl-ts | input-pting | 19.4 ± 0.6 | 18.6 | 24.7 | 15.78 ± 2.58 |
| mattcl-ts | input-kcen | 19.4 ± 0.4 | 18.6 | 20.8 | 15.79 ± 2.55 |
| mattcl-ts | input-mattcl | 19.8 ± 4.5 | 18.3 | 64.7 | 16.09 ± 4.45 |
| kcen | input-mattcl | 20.9 ± 0.6 | 20.1 | 23.8 | 16.96 ± 2.77 |
| kcen | input-kcen | 20.9 ± 0.7 | 19.9 | 24.0 | 16.97 ± 2.77 |
| kcen | input-pting | 21.0 ± 2.2 | 19.7 | 45.9 | 17.07 ± 3.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|