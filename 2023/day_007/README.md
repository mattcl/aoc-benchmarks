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
| lanjian | input-pting | 1.1 ± 0.3 | 0.3 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.15 ± 0.42 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.15 ± 0.41 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.16 ± 0.41 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.7 | 1.9 | 1.17 ± 0.41 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.5 | 1.18 ± 0.40 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.5 | 2.0 | 1.18 ± 0.42 |
| lanjian | input-chancalan | 1.3 ± 0.1 | 0.7 | 1.8 | 1.19 ± 0.40 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.7 | 1.8 | 1.20 ± 0.41 |
| mattcl | input-chancalan | 1.3 ± 0.1 | 0.5 | 1.9 | 1.22 ± 0.41 |
| mattcl-ts | input-pting | 14.5 ± 0.4 | 13.6 | 15.7 | 13.73 ± 4.35 |
| mattcl-ts | input-kcen | 14.5 ± 0.3 | 13.6 | 15.3 | 13.75 ± 4.35 |
| mattcl-ts | input-lanjian | 14.5 ± 0.4 | 13.6 | 15.5 | 13.78 ± 4.36 |
| mattcl-ts | input-mattcl | 14.7 ± 2.7 | 13.6 | 51.8 | 13.94 ± 5.07 |
| mattcl-ts | input-chancalan | 14.9 ± 3.8 | 13.6 | 60.0 | 14.16 ± 5.74 |
| mattcl-py | input-mattcl | 16.5 ± 0.5 | 15.5 | 19.4 | 15.62 ± 4.95 |
| mattcl-py | input-chancalan | 16.5 ± 0.6 | 15.3 | 19.9 | 15.65 ± 4.97 |
| mattcl-py | input-kcen | 16.6 ± 0.7 | 15.5 | 19.8 | 15.69 ± 5.00 |
| mattcl-py | input-pting | 16.6 ± 0.7 | 15.4 | 19.6 | 15.74 ± 5.02 |
| mattcl-py | input-lanjian | 16.7 ± 0.7 | 15.5 | 20.0 | 15.81 ± 5.04 |
| pting | input-pting | 16.9 ± 0.5 | 16.0 | 19.6 | 16.05 ± 5.09 |
| pting | input-kcen | 17.0 ± 0.7 | 15.8 | 20.2 | 16.07 ± 5.12 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.2 | 19.9 | 16.12 ± 5.12 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.1 | 20.5 | 16.17 ± 5.15 |
| pting | input-chancalan | 17.1 ± 1.1 | 16.0 | 28.9 | 16.19 ± 5.21 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.3 | 23.1 | 19.21 ± 6.10 |
| kcen | input-chancalan | 20.3 ± 0.8 | 19.1 | 23.7 | 19.22 ± 6.11 |
| kcen | input-pting | 20.3 ± 0.7 | 19.4 | 23.9 | 19.24 ± 6.11 |
| kcen | input-lanjian | 20.3 ± 0.7 | 19.2 | 23.1 | 19.27 ± 6.12 |
| kcen | input-mattcl | 20.4 ± 0.9 | 19.2 | 23.5 | 19.32 ± 6.15 |
| chancalan | input-lanjian | 24.3 ± 0.7 | 23.3 | 26.8 | 23.00 ± 7.29 |
| chancalan | input-chancalan | 24.4 ± 0.7 | 23.5 | 26.9 | 23.11 ± 7.32 |
| chancalan | input-pting | 24.4 ± 0.9 | 23.1 | 27.5 | 23.13 ± 7.35 |
| chancalan | input-kcen | 24.4 ± 0.7 | 22.8 | 27.0 | 23.14 ± 7.34 |
| chancalan | input-mattcl | 24.7 ± 2.2 | 23.2 | 46.4 | 23.40 ± 7.67 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|