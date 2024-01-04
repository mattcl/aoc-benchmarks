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
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.9 | 1.00 ± 0.22 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.00 ± 0.23 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.7 | 1.7 | 1.01 ± 0.22 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.3 | 1.8 | 1.01 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.8 | 1.02 ± 0.23 |
| lanjian | input-lanjian | 1.3 ± 0.2 | 0.6 | 1.8 | 1.03 ± 0.22 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-chancalan | 1.3 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.23 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 13.9 | 16.0 | 12.34 ± 1.96 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.3 | 16.0 | 12.34 ± 1.96 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.0 | 16.3 | 12.34 ± 1.96 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.2 | 16.2 | 12.36 ± 1.96 |
| mattcl-ts | input-chancalan | 16.4 ± 7.1 | 14.2 | 64.8 | 13.45 ± 6.16 |
| mattcl-py | input-kcen | 16.7 ± 0.7 | 15.5 | 19.8 | 13.71 ± 2.22 |
| mattcl-py | input-mattcl | 16.7 ± 0.7 | 15.7 | 20.3 | 13.72 ± 2.22 |
| mattcl-py | input-chancalan | 16.7 ± 0.7 | 15.6 | 19.8 | 13.74 ± 2.24 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 15.6 | 19.7 | 13.75 ± 2.24 |
| mattcl-py | input-lanjian | 16.8 ± 0.7 | 15.7 | 19.8 | 13.80 ± 2.23 |
| pting | input-chancalan | 17.2 ± 0.7 | 16.1 | 20.4 | 14.10 ± 2.28 |
| pting | input-kcen | 17.2 ± 0.6 | 16.0 | 20.2 | 14.12 ± 2.27 |
| pting | input-mattcl | 17.2 ± 0.6 | 15.8 | 19.9 | 14.14 ± 2.26 |
| pting | input-lanjian | 17.2 ± 0.7 | 16.0 | 20.5 | 14.15 ± 2.29 |
| pting | input-pting | 17.3 ± 0.7 | 15.8 | 19.8 | 14.21 ± 2.30 |
| kcen | input-chancalan | 20.4 ± 0.7 | 19.0 | 23.5 | 16.77 ± 2.68 |
| kcen | input-pting | 20.5 ± 0.7 | 19.3 | 23.7 | 16.85 ± 2.71 |
| kcen | input-lanjian | 20.5 ± 0.8 | 19.5 | 24.0 | 16.85 ± 2.72 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.5 | 24.0 | 16.89 ± 2.72 |
| kcen | input-kcen | 21.2 ± 4.7 | 19.1 | 65.4 | 17.39 ± 4.71 |
| chancalan | input-lanjian | 24.6 ± 0.7 | 23.5 | 27.4 | 20.15 ± 3.22 |
| chancalan | input-pting | 24.6 ± 0.7 | 23.5 | 27.3 | 20.17 ± 3.21 |
| chancalan | input-kcen | 24.6 ± 0.8 | 23.5 | 27.4 | 20.20 ± 3.24 |
| chancalan | input-mattcl | 24.7 ± 0.7 | 23.4 | 27.3 | 20.24 ± 3.23 |
| chancalan | input-chancalan | 24.7 ± 1.0 | 22.8 | 28.8 | 20.26 ± 3.28 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|