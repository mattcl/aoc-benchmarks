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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.9 | 1.00 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.6 | 1.00 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.24 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.24 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.8 | 1.01 ± 0.25 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.24 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.6 | 1.6 | 1.04 ± 0.22 |
| mattcl-ts | input-pting | 14.9 ± 0.4 | 13.9 | 15.7 | 13.09 ± 2.36 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 14.0 | 16.1 | 13.10 ± 2.36 |
| mattcl-ts | input-lanjian | 14.9 ± 0.4 | 13.9 | 15.9 | 13.11 ± 2.36 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 14.0 | 16.1 | 13.12 ± 2.37 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 14.1 | 16.0 | 13.12 ± 2.37 |
| mattcl-py | input-pting | 16.6 ± 0.7 | 15.2 | 19.6 | 14.59 ± 2.68 |
| mattcl-py | input-mattcl | 16.6 ± 0.7 | 15.4 | 20.3 | 14.60 ± 2.68 |
| mattcl-py | input-kcen | 16.6 ± 0.6 | 15.5 | 19.8 | 14.61 ± 2.67 |
| mattcl-py | input-chancalan | 16.7 ± 0.7 | 15.6 | 19.6 | 14.65 ± 2.68 |
| mattcl-py | input-lanjian | 16.7 ± 0.8 | 15.7 | 20.0 | 14.68 ± 2.72 |
| pting | input-mattcl | 17.2 ± 0.6 | 15.9 | 19.8 | 15.11 ± 2.75 |
| pting | input-pting | 17.2 ± 0.6 | 15.9 | 20.0 | 15.13 ± 2.75 |
| pting | input-chancalan | 17.2 ± 0.7 | 16.3 | 20.3 | 15.18 ± 2.78 |
| pting | input-kcen | 17.3 ± 0.7 | 16.1 | 20.6 | 15.20 ± 2.79 |
| pting | input-lanjian | 17.7 ± 4.1 | 16.4 | 69.1 | 15.57 ± 4.52 |
| kcen | input-mattcl | 20.4 ± 0.6 | 19.4 | 23.0 | 17.97 ± 3.25 |
| kcen | input-chancalan | 20.5 ± 0.6 | 19.1 | 22.7 | 17.99 ± 3.26 |
| kcen | input-lanjian | 20.5 ± 0.7 | 19.4 | 23.1 | 18.03 ± 3.28 |
| kcen | input-pting | 20.5 ± 0.7 | 19.4 | 23.5 | 18.04 ± 3.29 |
| kcen | input-kcen | 20.6 ± 0.8 | 19.5 | 23.4 | 18.10 ± 3.31 |
| chancalan | input-pting | 24.5 ± 0.7 | 23.2 | 27.7 | 21.52 ± 3.90 |
| chancalan | input-mattcl | 24.5 ± 0.8 | 23.3 | 27.5 | 21.53 ± 3.90 |
| chancalan | input-kcen | 24.6 ± 0.9 | 23.0 | 27.4 | 21.60 ± 3.93 |
| chancalan | input-chancalan | 24.6 ± 0.9 | 23.3 | 27.6 | 21.64 ± 3.94 |
| chancalan | input-lanjian | 24.6 ± 0.9 | 23.3 | 27.6 | 21.67 ± 3.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|