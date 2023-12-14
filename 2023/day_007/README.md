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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.22 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.5 | 1.6 | 1.04 ± 0.21 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.06 ± 0.24 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.7 | 1.7 | 1.07 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.08 ± 0.22 |
| mattcl-ts | input-lanjian | 14.3 ± 0.4 | 13.3 | 15.3 | 12.74 ± 2.06 |
| mattcl-ts | input-chancalan | 14.3 ± 0.4 | 13.4 | 15.5 | 12.77 ± 2.08 |
| mattcl-ts | input-pting | 14.3 ± 0.4 | 13.3 | 15.9 | 12.78 ± 2.08 |
| mattcl-ts | input-mattcl | 14.4 ± 0.4 | 13.4 | 15.4 | 12.84 ± 2.09 |
| mattcl-ts | input-kcen | 15.5 ± 7.6 | 13.6 | 65.3 | 13.87 ± 7.14 |
| mattcl-py | input-kcen | 16.4 ± 0.5 | 15.6 | 19.5 | 14.61 ± 2.39 |
| mattcl-py | input-pting | 16.5 ± 0.7 | 15.4 | 19.8 | 14.77 ± 2.45 |
| mattcl-py | input-mattcl | 16.6 ± 0.6 | 15.5 | 19.7 | 14.78 ± 2.43 |
| mattcl-py | input-lanjian | 16.6 ± 0.7 | 15.5 | 19.6 | 14.78 ± 2.44 |
| mattcl-py | input-chancalan | 16.6 ± 0.8 | 15.4 | 19.5 | 14.82 ± 2.47 |
| pting | input-pting | 17.0 ± 0.7 | 15.9 | 19.9 | 15.19 ± 2.51 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.9 | 19.8 | 15.20 ± 2.50 |
| pting | input-chancalan | 17.0 ± 0.7 | 16.0 | 20.2 | 15.21 ± 2.50 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.2 | 20.3 | 15.24 ± 2.51 |
| pting | input-kcen | 17.7 ± 5.1 | 16.1 | 69.5 | 15.84 ± 5.19 |
| kcen | input-chancalan | 20.2 ± 0.6 | 19.2 | 23.0 | 18.03 ± 2.93 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.1 | 24.5 | 18.09 ± 2.96 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.1 | 22.7 | 18.14 ± 2.96 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.5 | 23.4 | 18.14 ± 2.98 |
| kcen | input-pting | 20.3 ± 0.8 | 19.2 | 23.3 | 18.16 ± 2.99 |
| chancalan | input-pting | 24.3 ± 0.6 | 23.1 | 27.1 | 21.68 ± 3.51 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.4 | 27.2 | 21.70 ± 3.53 |
| chancalan | input-mattcl | 24.3 ± 0.7 | 23.3 | 26.8 | 21.71 ± 3.53 |
| chancalan | input-chancalan | 24.4 ± 0.9 | 23.3 | 27.8 | 21.79 ± 3.58 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.5 | 27.8 | 21.83 ± 3.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|