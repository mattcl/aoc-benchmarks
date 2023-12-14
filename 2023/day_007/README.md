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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.26 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.7 | 1.01 ± 0.27 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.26 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.25 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.26 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.25 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.04 ± 0.25 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.26 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.6 | 1.7 | 1.06 ± 0.25 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.1 | 16.2 | 13.18 ± 2.62 |
| mattcl-ts | input-chancalan | 15.1 ± 0.4 | 14.0 | 16.2 | 13.21 ± 2.63 |
| mattcl-ts | input-mattcl | 15.1 ± 0.3 | 14.1 | 16.0 | 13.22 ± 2.63 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.1 | 16.6 | 13.22 ± 2.63 |
| mattcl-ts | input-lanjian | 15.1 ± 0.4 | 14.3 | 16.3 | 13.22 ± 2.63 |
| mattcl-py | input-lanjian | 16.7 ± 0.6 | 15.5 | 19.7 | 14.69 ± 2.95 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.4 | 19.9 | 14.75 ± 2.97 |
| mattcl-py | input-chancalan | 16.8 ± 0.6 | 16.0 | 19.8 | 14.78 ± 2.97 |
| mattcl-py | input-mattcl | 16.9 ± 0.8 | 15.8 | 20.5 | 14.81 ± 3.00 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 15.4 | 20.7 | 14.86 ± 3.01 |
| pting | input-chancalan | 17.3 ± 0.6 | 16.2 | 20.6 | 15.20 ± 3.05 |
| pting | input-pting | 17.3 ± 0.6 | 16.4 | 20.8 | 15.21 ± 3.06 |
| pting | input-lanjian | 17.4 ± 0.8 | 16.4 | 20.5 | 15.29 ± 3.10 |
| pting | input-mattcl | 17.5 ± 0.9 | 16.5 | 20.9 | 15.36 ± 3.12 |
| pting | input-kcen | 17.8 ± 4.7 | 15.8 | 58.1 | 15.63 ± 5.14 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.1 | 23.8 | 17.95 ± 3.60 |
| kcen | input-pting | 20.5 ± 0.7 | 19.4 | 23.4 | 17.98 ± 3.60 |
| kcen | input-chancalan | 20.5 ± 0.8 | 18.9 | 23.4 | 18.00 ± 3.62 |
| kcen | input-lanjian | 20.5 ± 0.7 | 19.6 | 23.4 | 18.02 ± 3.61 |
| kcen | input-kcen | 20.6 ± 0.6 | 19.5 | 23.4 | 18.07 ± 3.61 |
| chancalan | input-mattcl | 24.6 ± 0.7 | 23.3 | 27.5 | 21.57 ± 4.31 |
| chancalan | input-kcen | 24.6 ± 0.7 | 23.4 | 27.9 | 21.60 ± 4.31 |
| chancalan | input-lanjian | 24.7 ± 0.7 | 23.1 | 28.6 | 21.65 ± 4.32 |
| chancalan | input-pting | 24.7 ± 0.7 | 23.5 | 27.9 | 21.66 ± 4.32 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.7 | 27.7 | 21.66 ± 4.32 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|