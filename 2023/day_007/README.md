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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.9 | 1.00 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.02 ± 0.22 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.9 | 1.02 ± 0.23 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.9 | 1.02 ± 0.22 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.22 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.7 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-chancalan | 1.2 ± 0.1 | 0.5 | 1.7 | 1.03 ± 0.21 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.22 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.7 | 2.0 | 1.04 ± 0.21 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.7 | 1.7 | 1.04 ± 0.20 |
| mattcl-ts | input-chancalan | 15.0 ± 0.3 | 14.2 | 16.0 | 12.60 ± 2.05 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.1 | 16.3 | 12.60 ± 2.06 |
| mattcl-ts | input-pting | 15.0 ± 0.3 | 14.1 | 16.0 | 12.63 ± 2.05 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 16.0 | 12.64 ± 2.06 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.0 | 16.1 | 12.65 ± 2.06 |
| mattcl-py | input-mattcl | 16.8 ± 0.8 | 15.4 | 20.4 | 14.12 ± 2.37 |
| mattcl-py | input-lanjian | 16.8 ± 0.6 | 15.8 | 19.9 | 14.13 ± 2.34 |
| mattcl-py | input-kcen | 16.9 ± 0.8 | 15.5 | 19.9 | 14.17 ± 2.38 |
| mattcl-py | input-pting | 16.9 ± 0.7 | 16.0 | 19.6 | 14.19 ± 2.36 |
| mattcl-py | input-chancalan | 16.9 ± 2.5 | 15.4 | 48.4 | 14.23 ± 3.09 |
| pting | input-pting | 17.2 ± 0.7 | 16.2 | 20.6 | 14.48 ± 2.40 |
| pting | input-lanjian | 17.3 ± 0.8 | 16.1 | 22.3 | 14.55 ± 2.43 |
| pting | input-chancalan | 17.3 ± 0.8 | 16.3 | 21.3 | 14.56 ± 2.43 |
| pting | input-kcen | 17.3 ± 0.7 | 16.3 | 20.6 | 14.57 ± 2.42 |
| pting | input-mattcl | 17.4 ± 0.8 | 16.1 | 20.7 | 14.59 ± 2.45 |
| kcen | input-chancalan | 20.4 ± 0.6 | 18.9 | 22.5 | 17.11 ± 2.80 |
| kcen | input-lanjian | 20.5 ± 0.7 | 19.3 | 23.5 | 17.24 ± 2.84 |
| kcen | input-pting | 20.6 ± 0.8 | 19.2 | 23.3 | 17.26 ± 2.86 |
| kcen | input-mattcl | 20.7 ± 2.3 | 19.3 | 44.6 | 17.41 ± 3.39 |
| kcen | input-kcen | 20.7 ± 0.8 | 19.6 | 23.8 | 17.42 ± 2.88 |
| chancalan | input-pting | 24.6 ± 0.9 | 23.0 | 27.7 | 20.70 ± 3.43 |
| chancalan | input-kcen | 24.7 ± 0.7 | 23.2 | 27.4 | 20.72 ± 3.39 |
| chancalan | input-chancalan | 24.8 ± 0.9 | 22.9 | 27.4 | 20.84 ± 3.45 |
| chancalan | input-lanjian | 24.8 ± 0.9 | 23.6 | 27.6 | 20.85 ± 3.43 |
| chancalan | input-mattcl | 24.9 ± 1.2 | 23.2 | 32.7 | 20.89 ± 3.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|