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
| mattcl | input-pting | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.7 | 1.00 ± 0.24 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.4 | 1.7 | 1.02 ± 0.25 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.26 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.4 | 1.9 | 1.04 ± 0.25 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.9 | 1.06 ± 0.24 |
| mattcl-ts | input-pting | 14.6 ± 0.3 | 13.6 | 15.5 | 13.21 ± 2.38 |
| mattcl-ts | input-chancalan | 14.6 ± 0.4 | 13.5 | 15.5 | 13.21 ± 2.39 |
| mattcl-ts | input-kcen | 14.6 ± 0.4 | 13.7 | 15.7 | 13.22 ± 2.39 |
| mattcl-ts | input-lanjian | 14.7 ± 0.4 | 13.6 | 15.7 | 13.24 ± 2.39 |
| mattcl-ts | input-mattcl | 14.7 ± 0.3 | 13.8 | 15.7 | 13.28 ± 2.40 |
| mattcl-py | input-kcen | 16.7 ± 0.6 | 15.6 | 20.0 | 15.10 ± 2.75 |
| mattcl-py | input-chancalan | 16.7 ± 0.6 | 15.8 | 20.2 | 15.11 ± 2.77 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.8 | 20.1 | 15.18 ± 2.78 |
| mattcl-py | input-pting | 16.8 ± 0.7 | 15.4 | 19.7 | 15.19 ± 2.80 |
| pting | input-kcen | 17.2 ± 0.7 | 15.9 | 20.0 | 15.54 ± 2.86 |
| mattcl-py | input-lanjian | 17.2 ± 3.5 | 15.4 | 49.6 | 15.54 ± 4.20 |
| pting | input-chancalan | 17.2 ± 0.6 | 15.8 | 19.5 | 15.56 ± 2.83 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.3 | 19.9 | 15.62 ± 2.85 |
| pting | input-pting | 17.3 ± 0.6 | 16.2 | 20.6 | 15.62 ± 2.85 |
| pting | input-lanjian | 17.5 ± 3.0 | 16.0 | 54.6 | 15.83 ± 3.89 |
| kcen | input-kcen | 20.4 ± 0.6 | 19.4 | 23.4 | 18.40 ± 3.34 |
| kcen | input-chancalan | 20.5 ± 0.7 | 19.0 | 23.1 | 18.53 ± 3.38 |
| kcen | input-mattcl | 20.5 ± 0.7 | 19.5 | 23.5 | 18.55 ± 3.38 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.7 | 23.4 | 18.59 ± 3.38 |
| kcen | input-pting | 20.7 ± 0.8 | 19.6 | 23.6 | 18.74 ± 3.43 |
| chancalan | input-kcen | 24.5 ± 0.6 | 23.0 | 27.2 | 22.15 ± 4.00 |
| chancalan | input-lanjian | 24.5 ± 0.7 | 23.3 | 27.5 | 22.17 ± 4.02 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.5 | 26.7 | 22.28 ± 4.04 |
| chancalan | input-pting | 24.7 ± 0.9 | 23.5 | 28.0 | 22.35 ± 4.09 |
| chancalan | input-mattcl | 24.8 ± 0.9 | 23.6 | 28.0 | 22.40 ± 4.08 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|