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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.24 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.8 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.25 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 2.1 | 1.05 ± 0.26 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.7 | 1.06 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 2.0 | 1.07 ± 0.25 |
| mattcl-ts | input-chancalan | 14.8 ± 0.3 | 14.1 | 15.9 | 13.12 ± 2.34 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 13.8 | 15.8 | 13.15 ± 2.34 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 13.9 | 15.8 | 13.15 ± 2.34 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 14.1 | 15.8 | 13.16 ± 2.34 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 14.0 | 16.1 | 13.19 ± 2.35 |
| mattcl-py | input-pting | 16.4 ± 0.5 | 15.5 | 19.7 | 14.52 ± 2.60 |
| mattcl-py | input-lanjian | 16.5 ± 0.5 | 15.8 | 19.1 | 14.59 ± 2.62 |
| mattcl-py | input-kcen | 16.6 ± 0.7 | 15.3 | 20.2 | 14.64 ± 2.65 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.4 | 19.6 | 14.68 ± 2.66 |
| mattcl-py | input-chancalan | 16.8 ± 3.2 | 15.6 | 58.5 | 14.83 ± 3.84 |
| pting | input-kcen | 16.9 ± 0.5 | 16.3 | 19.9 | 14.99 ± 2.68 |
| pting | input-lanjian | 17.0 ± 0.7 | 16.0 | 20.0 | 15.06 ± 2.72 |
| pting | input-pting | 17.1 ± 0.6 | 16.2 | 20.0 | 15.09 ± 2.72 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.1 | 20.6 | 15.09 ± 2.74 |
| pting | input-chancalan | 17.1 ± 0.7 | 16.3 | 20.8 | 15.11 ± 2.74 |
| kcen | input-kcen | 20.2 ± 0.8 | 19.1 | 23.4 | 17.90 ± 3.23 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.2 | 23.7 | 17.94 ± 3.23 |
| kcen | input-pting | 20.3 ± 0.7 | 19.4 | 23.2 | 17.96 ± 3.22 |
| kcen | input-chancalan | 20.4 ± 0.8 | 19.1 | 22.9 | 18.01 ± 3.25 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.5 | 23.3 | 18.02 ± 3.24 |
| chancalan | input-chancalan | 24.4 ± 0.6 | 23.3 | 27.5 | 21.55 ± 3.84 |
| chancalan | input-pting | 24.4 ± 0.7 | 23.3 | 27.4 | 21.58 ± 3.86 |
| chancalan | input-kcen | 24.4 ± 0.6 | 23.3 | 26.8 | 21.59 ± 3.85 |
| chancalan | input-mattcl | 24.5 ± 0.8 | 23.3 | 27.7 | 21.63 ± 3.87 |
| chancalan | input-lanjian | 24.9 ± 4.7 | 23.5 | 75.9 | 22.05 ± 5.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|