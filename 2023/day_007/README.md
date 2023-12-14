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
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.6 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.28 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.3 | 1.05 ± 0.26 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.29 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.08 ± 0.29 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.6 | 1.6 | 1.08 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.8 | 1.08 ± 0.27 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.7 | 1.10 ± 0.27 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.8 | 1.10 ± 0.29 |
| mattcl-ts | input-chancalan | 14.7 ± 0.4 | 13.6 | 15.8 | 14.46 ± 2.88 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.8 | 15.8 | 14.52 ± 2.89 |
| mattcl-ts | input-pting | 14.8 ± 0.4 | 13.9 | 16.0 | 14.53 ± 2.89 |
| mattcl-ts | input-kcen | 14.8 ± 0.3 | 14.0 | 15.6 | 14.55 ± 2.89 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 14.0 | 15.9 | 14.59 ± 2.90 |
| mattcl-py | input-lanjian | 16.4 ± 0.7 | 15.4 | 19.7 | 16.15 ± 3.25 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.4 | 19.6 | 16.17 ± 3.25 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.3 | 19.5 | 16.18 ± 3.25 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.7 | 19.4 | 16.22 ± 3.25 |
| mattcl-py | input-pting | 16.7 ± 2.6 | 15.5 | 50.7 | 16.39 ± 4.12 |
| pting | input-chancalan | 17.0 ± 0.7 | 16.0 | 20.3 | 16.66 ± 3.36 |
| pting | input-kcen | 17.0 ± 0.6 | 15.8 | 19.6 | 16.67 ± 3.35 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.0 | 20.1 | 16.68 ± 3.34 |
| pting | input-lanjian | 17.0 ± 0.6 | 15.9 | 19.3 | 16.69 ± 3.35 |
| pting | input-pting | 17.1 ± 0.8 | 16.0 | 20.5 | 16.78 ± 3.39 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.3 | 23.2 | 19.92 ± 3.99 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.2 | 23.3 | 19.93 ± 3.99 |
| kcen | input-lanjian | 20.4 ± 0.8 | 19.4 | 23.7 | 20.01 ± 4.02 |
| kcen | input-pting | 20.4 ± 0.8 | 19.1 | 23.3 | 20.06 ± 4.03 |
| kcen | input-chancalan | 20.4 ± 1.6 | 19.4 | 37.8 | 20.08 ± 4.27 |
| chancalan | input-lanjian | 24.4 ± 0.7 | 23.3 | 26.8 | 23.94 ± 4.77 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.1 | 27.0 | 23.96 ± 4.80 |
| chancalan | input-mattcl | 24.4 ± 0.8 | 23.4 | 27.1 | 24.00 ± 4.80 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.3 | 27.5 | 24.01 ± 4.79 |
| chancalan | input-chancalan | 24.6 ± 2.6 | 23.4 | 52.0 | 24.19 ± 5.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|