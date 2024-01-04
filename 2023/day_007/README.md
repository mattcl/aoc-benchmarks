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
| lanjian | input-chancalan | 1.0 ± 0.3 | 0.3 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.3 | 0.3 | 1.7 | 1.03 ± 0.43 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.3 | 1.7 | 1.19 ± 0.43 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.7 | 1.21 ± 0.41 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.3 | 1.9 | 1.23 ± 0.43 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.23 ± 0.42 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.24 ± 0.43 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 2.0 | 1.26 ± 0.44 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.7 | 1.7 | 1.26 ± 0.41 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 2.0 | 1.27 ± 0.45 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.1 | 16.3 | 15.36 ± 4.76 |
| mattcl-ts | input-lanjian | 15.0 ± 0.3 | 14.0 | 15.9 | 15.38 ± 4.76 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 14.1 | 16.5 | 15.41 ± 4.77 |
| mattcl-ts | input-mattcl | 15.2 ± 3.0 | 14.0 | 57.1 | 15.54 ± 5.72 |
| mattcl-ts | input-chancalan | 15.5 ± 0.5 | 14.6 | 17.1 | 15.89 ± 4.93 |
| mattcl-py | input-pting | 16.7 ± 0.6 | 15.5 | 19.8 | 17.16 ± 5.33 |
| mattcl-py | input-kcen | 16.8 ± 0.5 | 15.9 | 18.9 | 17.20 ± 5.34 |
| mattcl-py | input-mattcl | 16.8 ± 0.8 | 15.5 | 20.3 | 17.25 ± 5.39 |
| mattcl-py | input-lanjian | 17.0 ± 0.7 | 16.0 | 19.9 | 17.38 ± 5.42 |
| pting | input-pting | 17.3 ± 0.7 | 16.4 | 20.7 | 17.72 ± 5.51 |
| pting | input-lanjian | 17.4 ± 0.7 | 16.4 | 20.9 | 17.78 ± 5.53 |
| pting | input-kcen | 17.4 ± 0.7 | 16.1 | 20.6 | 17.81 ± 5.54 |
| pting | input-mattcl | 17.6 ± 1.7 | 16.1 | 36.8 | 18.00 ± 5.82 |
| mattcl-py | input-chancalan | 17.6 ± 0.5 | 16.6 | 20.5 | 18.07 ± 5.60 |
| pting | input-chancalan | 17.7 ± 0.7 | 16.6 | 20.6 | 18.10 ± 5.63 |
| kcen | input-lanjian | 20.6 ± 0.7 | 19.3 | 23.8 | 21.12 ± 6.56 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.4 | 23.4 | 21.14 ± 6.58 |
| kcen | input-pting | 20.7 ± 0.9 | 19.3 | 23.7 | 21.22 ± 6.62 |
| kcen | input-kcen | 21.2 ± 0.9 | 19.5 | 24.9 | 21.70 ± 6.76 |
| kcen | input-chancalan | 21.6 ± 0.4 | 20.5 | 23.1 | 22.13 ± 6.84 |
| chancalan | input-lanjian | 24.6 ± 0.7 | 23.5 | 27.3 | 25.21 ± 7.82 |
| chancalan | input-pting | 24.7 ± 0.8 | 23.5 | 27.9 | 25.33 ± 7.86 |
| chancalan | input-mattcl | 25.0 ± 3.7 | 23.4 | 64.2 | 25.60 ± 8.78 |
| chancalan | input-kcen | 25.3 ± 1.0 | 23.3 | 31.2 | 25.96 ± 8.08 |
| chancalan | input-chancalan | 25.6 ± 0.6 | 23.9 | 27.0 | 26.20 ± 8.11 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|