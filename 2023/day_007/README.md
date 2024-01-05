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
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.26 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.9 | 1.04 ± 0.25 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.7 | 1.05 ± 0.24 |
| mattcl | input-mattcl | 1.2 ± 0.1 | 0.5 | 1.6 | 1.05 ± 0.24 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.05 ± 0.27 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.7 | 1.05 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.1 | 0.7 | 1.7 | 1.05 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.06 ± 0.26 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.25 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.2 | 16.1 | 13.18 ± 2.58 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.0 | 16.0 | 13.19 ± 2.59 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.0 | 16.1 | 13.20 ± 2.59 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 13.9 | 16.3 | 13.26 ± 2.61 |
| mattcl-ts | input-mattcl | 15.1 ± 0.4 | 14.1 | 16.2 | 13.29 ± 2.61 |
| mattcl-py | input-mattcl | 16.6 ± 0.6 | 15.5 | 19.5 | 14.62 ± 2.89 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.3 | 19.4 | 14.66 ± 2.91 |
| mattcl-py | input-chancalan | 16.8 ± 0.8 | 15.7 | 19.7 | 14.80 ± 2.96 |
| mattcl-py | input-kcen | 16.9 ± 0.7 | 15.9 | 20.5 | 14.87 ± 2.97 |
| mattcl-py | input-pting | 16.9 ± 0.9 | 16.0 | 20.3 | 14.89 ± 3.00 |
| pting | input-kcen | 17.2 ± 0.7 | 16.1 | 20.5 | 15.17 ± 3.02 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.1 | 20.2 | 15.18 ± 3.02 |
| pting | input-pting | 17.3 ± 0.7 | 16.0 | 20.1 | 15.19 ± 3.01 |
| pting | input-chancalan | 17.3 ± 0.7 | 16.1 | 20.5 | 15.22 ± 3.03 |
| pting | input-mattcl | 17.5 ± 3.6 | 16.0 | 63.6 | 15.43 ± 4.36 |
| kcen | input-chancalan | 20.4 ± 0.7 | 19.1 | 23.1 | 17.95 ± 3.55 |
| kcen | input-pting | 20.5 ± 0.8 | 19.4 | 23.5 | 18.05 ± 3.58 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.5 | 23.2 | 18.09 ± 3.57 |
| kcen | input-kcen | 20.6 ± 0.7 | 19.4 | 23.3 | 18.16 ± 3.60 |
| kcen | input-mattcl | 21.4 ± 4.9 | 19.3 | 67.8 | 18.84 ± 5.64 |
| chancalan | input-mattcl | 24.7 ± 0.9 | 23.6 | 28.1 | 21.69 ± 4.29 |
| chancalan | input-pting | 24.7 ± 1.4 | 23.4 | 37.2 | 21.76 ± 4.41 |
| chancalan | input-lanjian | 24.8 ± 1.0 | 23.4 | 27.6 | 21.78 ± 4.33 |
| chancalan | input-chancalan | 24.8 ± 0.9 | 23.5 | 28.3 | 21.80 ± 4.31 |
| chancalan | input-kcen | 24.9 ± 0.7 | 23.6 | 27.2 | 21.87 ± 4.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|