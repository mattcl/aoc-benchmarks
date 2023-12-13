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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.7 | 1.00 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.6 | 1.6 | 1.02 ± 0.26 |
| mattcl | input-pting | 1.1 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.27 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.04 ± 0.29 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.8 | 1.04 ± 0.29 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.26 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.05 ± 0.26 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.6 | 1.08 ± 0.27 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.7 | 1.09 ± 0.27 |
| lanjian | input-pting | 1.2 ± 0.1 | 0.5 | 1.7 | 1.10 ± 0.26 |
| mattcl-ts | input-lanjian | 14.8 ± 0.4 | 13.7 | 15.8 | 14.08 ± 2.89 |
| mattcl-ts | input-pting | 14.8 ± 0.3 | 13.9 | 15.6 | 14.10 ± 2.89 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 14.0 | 15.8 | 14.12 ± 2.90 |
| mattcl-ts | input-mattcl | 14.9 ± 0.4 | 14.0 | 15.8 | 14.15 ± 2.91 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 14.1 | 17.1 | 14.16 ± 2.92 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.3 | 19.7 | 15.65 ± 3.25 |
| mattcl-py | input-kcen | 16.5 ± 0.5 | 15.6 | 19.2 | 15.69 ± 3.24 |
| mattcl-py | input-mattcl | 16.6 ± 0.8 | 15.5 | 19.6 | 15.75 ± 3.31 |
| mattcl-py | input-lanjian | 16.6 ± 0.8 | 15.6 | 19.6 | 15.77 ± 3.30 |
| mattcl-py | input-pting | 16.6 ± 0.8 | 15.5 | 19.8 | 15.78 ± 3.31 |
| pting | input-kcen | 16.9 ± 0.6 | 15.8 | 19.6 | 16.10 ± 3.34 |
| pting | input-mattcl | 16.9 ± 0.6 | 16.0 | 20.1 | 16.10 ± 3.34 |
| pting | input-pting | 17.0 ± 0.6 | 16.0 | 19.7 | 16.16 ± 3.35 |
| pting | input-lanjian | 17.1 ± 0.7 | 15.9 | 20.4 | 16.24 ± 3.39 |
| pting | input-chancalan | 17.1 ± 0.8 | 15.8 | 20.4 | 16.25 ± 3.39 |
| kcen | input-chancalan | 20.3 ± 0.8 | 19.1 | 23.6 | 19.30 ± 4.00 |
| kcen | input-kcen | 20.3 ± 0.8 | 19.1 | 24.0 | 19.34 ± 4.02 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.2 | 23.2 | 19.35 ± 4.01 |
| kcen | input-mattcl | 20.4 ± 0.7 | 19.3 | 23.9 | 19.41 ± 4.02 |
| kcen | input-pting | 20.4 ± 1.5 | 19.1 | 36.7 | 19.42 ± 4.21 |
| chancalan | input-kcen | 24.5 ± 0.8 | 23.4 | 27.4 | 23.30 ± 4.82 |
| chancalan | input-lanjian | 24.5 ± 0.9 | 23.3 | 27.7 | 23.30 ± 4.83 |
| chancalan | input-chancalan | 24.5 ± 0.9 | 23.5 | 27.8 | 23.33 ± 4.84 |
| chancalan | input-mattcl | 24.6 ± 0.9 | 23.4 | 27.5 | 23.36 ± 4.85 |
| chancalan | input-pting | 24.7 ± 3.2 | 22.9 | 53.7 | 23.51 ± 5.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|