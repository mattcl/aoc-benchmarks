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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.25 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.9 | 1.04 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.25 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.22 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.9 | 1.05 ± 0.23 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.6 | 1.7 | 1.06 ± 0.23 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.23 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.7 | 1.07 ± 0.23 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.8 | 15.8 | 13.63 ± 2.31 |
| mattcl-ts | input-chancalan | 14.9 ± 0.3 | 14.1 | 16.1 | 13.64 ± 2.31 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 14.1 | 15.7 | 13.67 ± 2.31 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.9 | 15.8 | 13.67 ± 2.32 |
| mattcl-ts | input-kcen | 14.9 ± 0.3 | 14.0 | 15.8 | 13.69 ± 2.31 |
| mattcl-py | input-pting | 16.4 ± 0.5 | 15.5 | 19.7 | 15.09 ± 2.58 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.3 | 19.6 | 15.17 ± 2.61 |
| mattcl-py | input-mattcl | 16.5 ± 0.6 | 15.3 | 19.2 | 15.18 ± 2.61 |
| mattcl-py | input-chancalan | 16.6 ± 0.7 | 15.7 | 20.3 | 15.24 ± 2.65 |
| mattcl-py | input-kcen | 16.9 ± 3.3 | 15.5 | 48.4 | 15.49 ± 3.99 |
| pting | input-lanjian | 17.0 ± 0.7 | 15.8 | 20.5 | 15.59 ± 2.68 |
| pting | input-mattcl | 17.0 ± 0.6 | 15.9 | 19.7 | 15.60 ± 2.68 |
| pting | input-kcen | 17.0 ± 0.6 | 16.0 | 19.9 | 15.60 ± 2.68 |
| pting | input-chancalan | 17.0 ± 0.6 | 15.9 | 19.7 | 15.61 ± 2.67 |
| pting | input-pting | 17.0 ± 0.6 | 16.0 | 20.6 | 15.65 ± 2.69 |
| kcen | input-kcen | 20.2 ± 0.6 | 19.2 | 23.4 | 18.52 ± 3.15 |
| kcen | input-chancalan | 20.2 ± 0.7 | 19.2 | 23.2 | 18.54 ± 3.17 |
| kcen | input-pting | 20.3 ± 0.5 | 19.2 | 22.1 | 18.61 ± 3.16 |
| kcen | input-mattcl | 20.3 ± 0.6 | 19.1 | 22.9 | 18.62 ± 3.17 |
| kcen | input-lanjian | 20.5 ± 0.9 | 19.3 | 24.0 | 18.79 ± 3.25 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.1 | 27.9 | 22.34 ± 3.80 |
| chancalan | input-mattcl | 24.4 ± 0.7 | 23.3 | 27.4 | 22.38 ± 3.81 |
| chancalan | input-pting | 24.5 ± 0.7 | 23.2 | 27.5 | 22.48 ± 3.82 |
| chancalan | input-chancalan | 24.5 ± 0.9 | 23.3 | 27.4 | 22.52 ± 3.87 |
| chancalan | input-kcen | 24.7 ± 3.2 | 23.3 | 58.1 | 22.68 ± 4.78 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|