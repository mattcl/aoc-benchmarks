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
| lanjian | input-kcen | 1.0 ± 0.3 | 0.3 | 2.4 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.34 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.6 | 1.08 ± 0.32 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.09 ± 0.32 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.5 | 1.10 ± 0.32 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.3 | 1.10 ± 0.33 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.7 | 1.11 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.12 ± 0.33 |
| mattcl-ts | input-lanjian | 14.4 ± 0.4 | 13.7 | 15.4 | 14.27 ± 3.58 |
| mattcl-ts | input-kcen | 14.4 ± 0.4 | 13.6 | 15.7 | 14.27 ± 3.58 |
| mattcl-ts | input-pting | 14.5 ± 0.4 | 13.4 | 15.7 | 14.29 ± 3.58 |
| mattcl-ts | input-mattcl | 14.5 ± 0.4 | 13.5 | 18.3 | 14.30 ± 3.59 |
| mattcl-py | input-kcen | 16.3 ± 0.5 | 15.5 | 19.6 | 16.14 ± 4.06 |
| mattcl-py | input-mattcl | 16.4 ± 0.5 | 15.4 | 19.4 | 16.18 ± 4.07 |
| mattcl-py | input-pting | 16.4 ± 0.5 | 15.5 | 19.0 | 16.21 ± 4.07 |
| mattcl-py | input-lanjian | 16.6 ± 2.7 | 15.2 | 50.4 | 16.43 ± 4.87 |
| pting | input-kcen | 16.8 ± 0.5 | 16.1 | 19.6 | 16.58 ± 4.17 |
| pting | input-lanjian | 16.8 ± 0.6 | 15.9 | 19.7 | 16.63 ± 4.20 |
| pting | input-pting | 16.9 ± 0.7 | 15.8 | 20.3 | 16.67 ± 4.21 |
| pting | input-mattcl | 16.9 ± 0.7 | 15.8 | 20.4 | 16.73 ± 4.24 |
| kcen | input-kcen | 20.0 ± 0.6 | 18.9 | 22.9 | 19.77 ± 4.97 |
| kcen | input-pting | 20.1 ± 0.6 | 19.4 | 23.0 | 19.87 ± 5.00 |
| kcen | input-lanjian | 20.2 ± 0.7 | 19.2 | 23.5 | 19.94 ± 5.03 |
| kcen | input-mattcl | 20.2 ± 0.8 | 19.0 | 24.7 | 19.97 ± 5.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|