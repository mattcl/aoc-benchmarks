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
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 2.0 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.22 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 2.0 | 1.02 ± 0.22 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.21 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.2 | 0.7 | 1.7 | 1.02 ± 0.21 |
| mattcl | input-lanjian | 1.3 ± 0.1 | 0.6 | 1.7 | 1.02 ± 0.21 |
| lanjian | input-chancalan | 1.3 ± 0.2 | 0.5 | 2.0 | 1.02 ± 0.23 |
| lanjian | input-kcen | 1.3 ± 0.2 | 0.7 | 1.8 | 1.05 ± 0.22 |
| mattcl-ts | input-pting | 14.7 ± 0.4 | 13.7 | 15.6 | 12.01 ± 2.08 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.8 | 15.8 | 12.02 ± 2.08 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.5 | 15.9 | 12.04 ± 2.08 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.6 | 17.1 | 12.05 ± 2.09 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 14.0 | 15.9 | 12.05 ± 2.08 |
| mattcl-py | input-mattcl | 16.7 ± 0.6 | 15.3 | 20.1 | 13.61 ± 2.38 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.7 | 19.3 | 13.67 ± 2.39 |
| mattcl-py | input-chancalan | 16.8 ± 0.8 | 15.5 | 20.2 | 13.73 ± 2.43 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 15.5 | 20.0 | 13.74 ± 2.41 |
| mattcl-py | input-kcen | 16.9 ± 0.7 | 15.9 | 20.2 | 13.75 ± 2.42 |
| pting | input-chancalan | 17.3 ± 0.8 | 16.2 | 20.9 | 14.12 ± 2.51 |
| pting | input-pting | 17.3 ± 0.8 | 16.1 | 21.1 | 14.14 ± 2.50 |
| pting | input-kcen | 17.4 ± 0.8 | 16.2 | 20.5 | 14.21 ± 2.52 |
| pting | input-mattcl | 17.4 ± 0.8 | 16.0 | 20.3 | 14.21 ± 2.51 |
| pting | input-lanjian | 17.7 ± 4.3 | 16.3 | 53.6 | 14.46 ± 4.30 |
| kcen | input-pting | 20.5 ± 0.8 | 19.1 | 23.5 | 16.72 ± 2.92 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.1 | 23.7 | 16.72 ± 2.92 |
| kcen | input-kcen | 20.5 ± 0.8 | 19.5 | 23.9 | 16.74 ± 2.93 |
| kcen | input-mattcl | 20.5 ± 0.8 | 19.2 | 23.8 | 16.75 ± 2.94 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.6 | 23.2 | 16.85 ± 2.93 |
| chancalan | input-chancalan | 24.6 ± 0.7 | 23.0 | 27.7 | 20.04 ± 3.48 |
| chancalan | input-mattcl | 24.6 ± 0.9 | 23.5 | 27.5 | 20.11 ± 3.51 |
| chancalan | input-pting | 24.8 ± 0.8 | 23.5 | 27.4 | 20.20 ± 3.52 |
| chancalan | input-kcen | 24.8 ± 1.0 | 22.9 | 27.9 | 20.27 ± 3.57 |
| chancalan | input-lanjian | 24.9 ± 0.9 | 23.6 | 28.5 | 20.35 ± 3.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|