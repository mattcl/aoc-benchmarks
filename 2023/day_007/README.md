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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.28 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.28 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.24 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.8 | 1.05 ± 0.26 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.8 | 1.06 ± 0.27 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 2.6 | 1.08 ± 0.29 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.8 | 15.8 | 13.92 ± 2.56 |
| mattcl-ts | input-mattcl | 14.8 ± 0.3 | 13.9 | 15.8 | 13.95 ± 2.57 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.9 | 16.0 | 13.96 ± 2.57 |
| mattcl-ts | input-chancalan | 15.0 ± 3.0 | 13.9 | 56.7 | 14.15 ± 3.84 |
| mattcl-ts | input-pting | 15.1 ± 2.2 | 13.7 | 44.4 | 14.17 ± 3.29 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.5 | 19.7 | 15.52 ± 2.89 |
| mattcl-py | input-kcen | 16.5 ± 0.7 | 15.4 | 19.7 | 15.54 ± 2.91 |
| mattcl-py | input-lanjian | 16.5 ± 0.6 | 15.7 | 19.9 | 15.55 ± 2.90 |
| mattcl-py | input-pting | 16.6 ± 0.7 | 15.9 | 19.4 | 15.59 ± 2.92 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.5 | 20.2 | 15.63 ± 2.93 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 19.7 | 15.91 ± 2.95 |
| pting | input-pting | 17.0 ± 0.6 | 16.2 | 19.9 | 16.02 ± 2.98 |
| pting | input-kcen | 17.0 ± 0.6 | 16.1 | 19.8 | 16.05 ± 2.99 |
| pting | input-chancalan | 17.1 ± 0.8 | 15.9 | 20.1 | 16.07 ± 3.02 |
| pting | input-lanjian | 17.1 ± 0.7 | 16.1 | 20.1 | 16.08 ± 3.01 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.4 | 23.2 | 19.11 ± 3.55 |
| kcen | input-kcen | 20.3 ± 0.8 | 19.1 | 23.0 | 19.15 ± 3.58 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.6 | 23.3 | 19.17 ± 3.57 |
| kcen | input-pting | 20.4 ± 0.7 | 19.3 | 23.3 | 19.22 ± 3.57 |
| kcen | input-chancalan | 20.6 ± 3.6 | 19.1 | 63.8 | 19.43 ± 4.93 |
| chancalan | input-pting | 24.3 ± 0.7 | 23.0 | 27.5 | 22.91 ± 4.23 |
| chancalan | input-chancalan | 24.3 ± 0.7 | 23.3 | 27.1 | 22.92 ± 4.24 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.3 | 27.1 | 22.98 ± 4.26 |
| chancalan | input-mattcl | 24.4 ± 0.7 | 23.3 | 27.0 | 23.01 ± 4.25 |
| chancalan | input-lanjian | 24.5 ± 0.8 | 23.5 | 26.9 | 23.01 ± 4.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|