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
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.00 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.02 ± 0.26 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.7 | 1.03 ± 0.27 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.7 | 1.04 ± 0.26 |
| lanjian | input-kcen | 1.2 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.26 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.26 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.27 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.7 | 1.07 ± 0.26 |
| mattcl | input-lanjian | 1.2 ± 2.5 | 0.3 | 36.2 | 1.10 ± 2.21 |
| lanjian | input-chancalan | 1.3 ± 3.5 | 0.3 | 50.2 | 1.17 ± 3.07 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 13.7 | 16.0 | 13.18 ± 2.76 |
| mattcl-ts | input-chancalan | 15.0 ± 0.4 | 14.1 | 15.9 | 13.20 ± 2.76 |
| mattcl-ts | input-lanjian | 15.1 ± 0.4 | 14.1 | 16.1 | 13.25 ± 2.78 |
| mattcl-ts | input-pting | 15.1 ± 0.4 | 14.3 | 16.2 | 13.26 ± 2.78 |
| mattcl-ts | input-kcen | 15.1 ± 0.4 | 14.2 | 16.3 | 13.28 ± 2.78 |
| mattcl-py | input-kcen | 16.8 ± 0.6 | 16.0 | 19.5 | 14.75 ± 3.12 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.9 | 19.6 | 14.79 ± 3.13 |
| mattcl-py | input-pting | 16.9 ± 0.6 | 15.8 | 19.7 | 14.83 ± 3.13 |
| mattcl-py | input-chancalan | 16.9 ± 0.8 | 15.6 | 20.1 | 14.88 ± 3.17 |
| mattcl-py | input-lanjian | 17.1 ± 3.1 | 15.7 | 56.8 | 15.03 ± 4.16 |
| pting | input-lanjian | 17.2 ± 0.8 | 15.7 | 20.5 | 15.14 ± 3.22 |
| pting | input-kcen | 17.2 ± 0.7 | 16.2 | 20.8 | 15.15 ± 3.21 |
| pting | input-pting | 17.3 ± 0.7 | 15.9 | 20.9 | 15.19 ± 3.21 |
| pting | input-mattcl | 17.3 ± 0.6 | 16.3 | 19.6 | 15.19 ± 3.21 |
| pting | input-chancalan | 17.4 ± 0.8 | 16.0 | 21.0 | 15.27 ± 3.25 |
| kcen | input-lanjian | 20.5 ± 0.8 | 19.0 | 24.0 | 18.05 ± 3.82 |
| kcen | input-chancalan | 20.6 ± 0.8 | 19.3 | 23.7 | 18.09 ± 3.82 |
| kcen | input-kcen | 20.6 ± 0.8 | 19.4 | 23.9 | 18.10 ± 3.83 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.4 | 23.5 | 18.15 ± 3.84 |
| kcen | input-pting | 20.7 ± 0.8 | 18.9 | 24.0 | 18.19 ± 3.85 |
| chancalan | input-lanjian | 24.7 ± 1.0 | 22.9 | 27.6 | 21.75 ± 4.60 |
| chancalan | input-kcen | 24.7 ± 0.8 | 23.7 | 27.7 | 21.75 ± 4.58 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.7 | 27.6 | 21.76 ± 4.57 |
| chancalan | input-mattcl | 24.8 ± 0.8 | 23.6 | 27.5 | 21.80 ± 4.59 |
| chancalan | input-pting | 24.9 ± 0.9 | 23.7 | 27.7 | 21.88 ± 4.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|