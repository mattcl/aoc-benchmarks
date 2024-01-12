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
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.6 | 1.00 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.6 | 1.01 ± 0.20 |
| lanjian | input-pting | 1.2 ± 0.2 | 0.4 | 1.7 | 1.01 ± 0.21 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.9 | 1.02 ± 0.23 |
| lanjian | input-lanjian | 1.2 ± 0.2 | 0.6 | 1.8 | 1.02 ± 0.22 |
| lanjian | input-kcen | 1.2 ± 0.1 | 0.6 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.24 |
| mattcl | input-kcen | 1.2 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.20 |
| mattcl | input-chancalan | 1.2 ± 0.1 | 0.7 | 1.7 | 1.03 ± 0.20 |
| mattcl-ts | input-chancalan | 14.9 ± 0.4 | 14.1 | 16.1 | 12.79 ± 1.96 |
| mattcl-ts | input-pting | 15.0 ± 0.4 | 14.3 | 16.1 | 12.84 ± 1.96 |
| mattcl-ts | input-kcen | 15.0 ± 0.4 | 14.1 | 16.1 | 12.85 ± 1.97 |
| mattcl-ts | input-mattcl | 15.0 ± 0.4 | 14.0 | 15.9 | 12.86 ± 1.97 |
| mattcl-ts | input-lanjian | 15.0 ± 0.4 | 14.2 | 16.0 | 12.87 ± 1.97 |
| mattcl-py | input-chancalan | 16.8 ± 0.7 | 15.3 | 20.0 | 14.33 ± 2.24 |
| mattcl-py | input-kcen | 16.8 ± 0.7 | 15.5 | 20.4 | 14.37 ± 2.26 |
| mattcl-py | input-mattcl | 16.8 ± 0.7 | 15.9 | 20.1 | 14.37 ± 2.24 |
| mattcl-py | input-pting | 16.8 ± 0.8 | 15.8 | 20.6 | 14.40 ± 2.27 |
| mattcl-py | input-lanjian | 16.9 ± 0.7 | 15.9 | 19.7 | 14.46 ± 2.27 |
| pting | input-chancalan | 17.4 ± 0.6 | 16.5 | 20.4 | 14.85 ± 2.30 |
| pting | input-pting | 17.4 ± 0.6 | 16.4 | 20.4 | 14.85 ± 2.31 |
| pting | input-kcen | 17.4 ± 0.7 | 16.3 | 20.5 | 14.86 ± 2.32 |
| pting | input-lanjian | 17.5 ± 0.8 | 16.5 | 20.6 | 14.95 ± 2.35 |
| pting | input-mattcl | 17.5 ± 0.7 | 16.5 | 20.5 | 14.98 ± 2.34 |
| kcen | input-chancalan | 20.6 ± 0.7 | 19.0 | 23.5 | 17.62 ± 2.72 |
| kcen | input-kcen | 20.7 ± 0.7 | 19.4 | 23.6 | 17.68 ± 2.73 |
| kcen | input-mattcl | 20.8 ± 0.7 | 19.6 | 23.9 | 17.77 ± 2.75 |
| kcen | input-pting | 20.8 ± 0.9 | 19.5 | 24.0 | 17.78 ± 2.78 |
| kcen | input-lanjian | 21.1 ± 3.0 | 19.4 | 48.2 | 18.03 ± 3.75 |
| chancalan | input-chancalan | 24.7 ± 0.7 | 23.6 | 27.2 | 21.12 ± 3.24 |
| chancalan | input-pting | 24.7 ± 0.6 | 23.6 | 27.0 | 21.12 ± 3.24 |
| chancalan | input-mattcl | 24.7 ± 0.7 | 23.5 | 27.9 | 21.14 ± 3.25 |
| chancalan | input-kcen | 24.8 ± 0.8 | 23.6 | 27.8 | 21.22 ± 3.28 |
| chancalan | input-lanjian | 25.0 ± 3.8 | 23.1 | 65.3 | 21.36 ± 4.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|