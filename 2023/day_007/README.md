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
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.5 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.27 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.24 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 2.4 | 1.03 ± 0.26 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.23 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.8 | 1.04 ± 0.24 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 13.9 | 15.8 | 13.02 ± 2.37 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.7 | 15.9 | 13.04 ± 2.37 |
| mattcl-ts | input-kcen | 14.8 ± 0.4 | 13.8 | 17.8 | 13.06 ± 2.38 |
| mattcl-ts | input-mattcl | 14.8 ± 0.4 | 13.9 | 15.7 | 13.06 ± 2.37 |
| mattcl-ts | input-pting | 15.1 ± 3.8 | 13.9 | 68.1 | 13.31 ± 4.11 |
| mattcl-py | input-pting | 16.4 ± 0.5 | 15.4 | 18.9 | 14.46 ± 2.65 |
| mattcl-py | input-mattcl | 16.4 ± 0.6 | 15.6 | 19.6 | 14.49 ± 2.66 |
| mattcl-py | input-kcen | 16.5 ± 0.6 | 15.5 | 19.5 | 14.52 ± 2.67 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.4 | 19.4 | 14.52 ± 2.68 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.5 | 19.3 | 14.53 ± 2.67 |
| pting | input-mattcl | 17.0 ± 0.6 | 16.2 | 20.8 | 15.02 ± 2.75 |
| pting | input-chancalan | 17.1 ± 0.6 | 16.2 | 19.9 | 15.08 ± 2.77 |
| pting | input-lanjian | 17.1 ± 0.6 | 15.8 | 20.2 | 15.08 ± 2.77 |
| pting | input-kcen | 17.2 ± 0.9 | 16.1 | 20.6 | 15.20 ± 2.84 |
| pting | input-pting | 17.4 ± 4.0 | 16.0 | 69.0 | 15.35 ± 4.50 |
| kcen | input-lanjian | 20.1 ± 0.6 | 18.9 | 23.4 | 17.72 ± 3.24 |
| kcen | input-pting | 20.1 ± 0.6 | 19.0 | 23.1 | 17.73 ± 3.24 |
| kcen | input-kcen | 20.1 ± 0.6 | 19.2 | 22.9 | 17.76 ± 3.24 |
| kcen | input-chancalan | 20.2 ± 0.8 | 18.9 | 23.3 | 17.82 ± 3.28 |
| kcen | input-mattcl | 20.2 ± 0.7 | 18.8 | 22.5 | 17.83 ± 3.26 |
| chancalan | input-pting | 24.2 ± 0.6 | 23.3 | 27.6 | 21.30 ± 3.87 |
| chancalan | input-chancalan | 24.2 ± 0.8 | 23.2 | 27.8 | 21.32 ± 3.90 |
| chancalan | input-mattcl | 24.3 ± 0.9 | 23.1 | 27.5 | 21.39 ± 3.93 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.0 | 26.6 | 21.42 ± 3.90 |
| chancalan | input-kcen | 24.3 ± 0.8 | 23.4 | 27.5 | 21.45 ± 3.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|