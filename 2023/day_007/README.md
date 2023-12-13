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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.9 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.24 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.2 | 1.9 | 1.04 ± 0.27 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.5 | 1.7 | 1.04 ± 0.23 |
| lanjian | input-pting | 1.1 ± 0.1 | 0.5 | 1.3 | 1.05 ± 0.22 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.9 | 1.05 ± 0.28 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.25 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.08 ± 0.24 |
| mattcl-ts | input-chancalan | 14.6 ± 0.4 | 13.7 | 15.7 | 13.67 ± 2.47 |
| mattcl-ts | input-pting | 14.7 ± 0.4 | 13.8 | 15.8 | 13.72 ± 2.49 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.8 | 16.0 | 13.77 ± 2.50 |
| mattcl-ts | input-mattcl | 15.0 ± 2.7 | 13.9 | 52.6 | 14.02 ± 3.58 |
| mattcl-ts | input-kcen | 15.3 ± 5.4 | 13.7 | 74.6 | 14.26 ± 5.70 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.8 | 19.1 | 15.65 ± 2.86 |
| mattcl-py | input-chancalan | 16.8 ± 0.8 | 15.9 | 20.4 | 15.70 ± 2.90 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 15.3 | 19.6 | 15.71 ± 2.88 |
| mattcl-py | input-mattcl | 16.9 ± 0.8 | 15.8 | 20.3 | 15.79 ± 2.92 |
| mattcl-py | input-kcen | 17.0 ± 2.7 | 15.3 | 51.2 | 15.85 ± 3.80 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.2 | 20.8 | 16.16 ± 2.96 |
| pting | input-kcen | 17.3 ± 0.7 | 16.1 | 20.7 | 16.17 ± 2.98 |
| pting | input-pting | 17.4 ± 0.7 | 15.8 | 20.9 | 16.22 ± 2.98 |
| pting | input-lanjian | 17.4 ± 0.6 | 16.4 | 20.6 | 16.23 ± 2.96 |
| pting | input-mattcl | 17.4 ± 0.7 | 16.2 | 20.6 | 16.28 ± 3.00 |
| kcen | input-kcen | 20.5 ± 0.7 | 19.5 | 24.1 | 19.17 ± 3.50 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.3 | 23.3 | 19.17 ± 3.51 |
| kcen | input-pting | 20.5 ± 0.7 | 19.4 | 23.1 | 19.18 ± 3.49 |
| kcen | input-lanjian | 20.5 ± 0.7 | 19.3 | 23.6 | 19.19 ± 3.50 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.3 | 24.4 | 19.21 ± 3.52 |
| chancalan | input-mattcl | 24.5 ± 0.6 | 23.5 | 26.9 | 22.93 ± 4.15 |
| chancalan | input-kcen | 24.6 ± 0.8 | 23.6 | 27.9 | 23.03 ± 4.19 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.5 | 27.3 | 23.05 ± 4.19 |
| chancalan | input-lanjian | 24.7 ± 0.8 | 23.3 | 27.2 | 23.10 ± 4.20 |
| chancalan | input-pting | 24.8 ± 1.0 | 23.3 | 27.8 | 23.14 ± 4.25 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|