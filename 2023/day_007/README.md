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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.31 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.27 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.26 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.6 | 1.06 ± 0.25 |
| mattcl | input-pting | 1.2 ± 0.1 | 0.6 | 1.7 | 1.06 ± 0.26 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.08 ± 0.26 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.08 ± 0.26 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.8 | 1.4 | 1.08 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 2.1 | 1.09 ± 0.29 |
| mattcl-ts | input-chancalan | 14.4 ± 0.4 | 13.1 | 15.8 | 12.90 ± 2.73 |
| mattcl-ts | input-pting | 14.4 ± 0.4 | 13.6 | 15.2 | 12.92 ± 2.73 |
| mattcl-ts | input-kcen | 14.4 ± 0.4 | 13.5 | 15.3 | 12.95 ± 2.73 |
| mattcl-ts | input-lanjian | 14.4 ± 0.4 | 13.6 | 15.4 | 12.96 ± 2.73 |
| mattcl-ts | input-mattcl | 14.5 ± 0.4 | 13.6 | 15.7 | 12.98 ± 2.74 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.7 | 19.6 | 14.80 ± 3.15 |
| mattcl-py | input-kcen | 16.5 ± 0.5 | 15.4 | 19.5 | 14.85 ± 3.15 |
| mattcl-py | input-chancalan | 16.5 ± 0.7 | 15.7 | 19.6 | 14.85 ± 3.18 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.4 | 20.0 | 14.92 ± 3.19 |
| mattcl-py | input-pting | 16.6 ± 0.8 | 15.4 | 20.2 | 14.92 ± 3.20 |
| pting | input-kcen | 17.0 ± 0.7 | 15.9 | 20.3 | 15.28 ± 3.27 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.0 | 20.6 | 15.29 ± 3.27 |
| pting | input-chancalan | 17.0 ± 0.7 | 16.3 | 20.5 | 15.30 ± 3.27 |
| pting | input-mattcl | 17.1 ± 0.7 | 15.8 | 20.6 | 15.35 ± 3.28 |
| pting | input-pting | 17.1 ± 0.7 | 16.1 | 20.1 | 15.36 ± 3.28 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.1 | 22.9 | 18.21 ± 3.86 |
| kcen | input-pting | 20.3 ± 0.8 | 19.4 | 23.3 | 18.24 ± 3.88 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.5 | 23.1 | 18.25 ± 3.87 |
| kcen | input-chancalan | 20.4 ± 0.8 | 19.2 | 23.2 | 18.31 ± 3.90 |
| kcen | input-mattcl | 20.4 ± 0.9 | 19.4 | 23.8 | 18.34 ± 3.92 |
| chancalan | input-kcen | 24.3 ± 0.7 | 23.3 | 27.1 | 21.81 ± 4.61 |
| chancalan | input-chancalan | 24.3 ± 0.7 | 23.3 | 26.9 | 21.84 ± 4.62 |
| chancalan | input-pting | 24.4 ± 0.8 | 23.4 | 27.9 | 21.88 ± 4.64 |
| chancalan | input-mattcl | 24.4 ± 0.8 | 23.5 | 27.1 | 21.94 ± 4.65 |
| chancalan | input-lanjian | 24.5 ± 0.8 | 23.5 | 27.4 | 21.96 ± 4.65 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|