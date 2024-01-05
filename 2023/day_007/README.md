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
| lanjian | input-kcen | 0.9 ± 1.3 | 0.3 | 18.7 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.7 | 1.32 ± 1.94 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.4 | 1.7 | 1.33 ± 1.96 |
| mattcl | input-chancalan | 1.2 ± 0.2 | 0.3 | 1.8 | 1.35 ± 1.98 |
| lanjian | input-mattcl | 1.2 ± 0.2 | 0.7 | 1.8 | 1.37 ± 2.02 |
| lanjian | input-chancalan | 1.2 ± 0.2 | 0.4 | 1.7 | 1.38 ± 2.02 |
| mattcl | input-pting | 1.2 ± 0.2 | 0.5 | 1.7 | 1.38 ± 2.03 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.8 | 1.38 ± 2.03 |
| lanjian | input-pting | 1.3 ± 0.1 | 0.8 | 1.7 | 1.42 ± 2.08 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.7 | 1.8 | 1.42 ± 2.09 |
| mattcl-ts | input-lanjian | 14.8 ± 0.3 | 14.0 | 15.7 | 16.77 ± 24.54 |
| mattcl-ts | input-pting | 14.8 ± 0.3 | 14.0 | 15.9 | 16.77 ± 24.54 |
| mattcl-ts | input-chancalan | 14.8 ± 0.4 | 14.0 | 16.1 | 16.77 ± 24.55 |
| mattcl-ts | input-kcen | 14.9 ± 0.4 | 13.8 | 15.9 | 16.80 ± 24.59 |
| mattcl-ts | input-mattcl | 14.9 ± 0.3 | 13.9 | 15.8 | 16.83 ± 24.63 |
| mattcl-py | input-mattcl | 16.5 ± 0.5 | 15.6 | 19.3 | 18.60 ± 27.23 |
| mattcl-py | input-pting | 16.5 ± 0.6 | 15.7 | 19.8 | 18.62 ± 27.26 |
| mattcl-py | input-chancalan | 16.5 ± 0.7 | 15.6 | 19.9 | 18.67 ± 27.33 |
| mattcl-py | input-lanjian | 16.5 ± 0.7 | 15.5 | 19.5 | 18.68 ± 27.34 |
| pting | input-mattcl | 16.9 ± 0.6 | 15.9 | 20.1 | 19.13 ± 27.99 |
| mattcl-py | input-kcen | 16.9 ± 3.4 | 15.4 | 54.2 | 19.15 ± 28.27 |
| pting | input-kcen | 16.9 ± 0.7 | 15.6 | 20.4 | 19.16 ± 28.04 |
| pting | input-lanjian | 16.9 ± 0.6 | 15.8 | 20.4 | 19.16 ± 28.04 |
| pting | input-chancalan | 17.0 ± 0.7 | 16.2 | 20.2 | 19.23 ± 28.15 |
| pting | input-pting | 17.0 ± 0.8 | 15.6 | 20.2 | 19.23 ± 28.16 |
| kcen | input-pting | 20.2 ± 0.8 | 19.1 | 23.2 | 22.84 ± 33.44 |
| kcen | input-kcen | 20.2 ± 0.8 | 19.2 | 23.9 | 22.85 ± 33.45 |
| kcen | input-mattcl | 20.3 ± 0.7 | 19.2 | 23.1 | 22.92 ± 33.54 |
| kcen | input-chancalan | 20.3 ± 0.9 | 19.4 | 23.3 | 22.95 ± 33.59 |
| kcen | input-lanjian | 20.3 ± 0.8 | 19.1 | 23.4 | 22.96 ± 33.60 |
| chancalan | input-mattcl | 24.2 ± 0.7 | 23.3 | 27.4 | 27.37 ± 40.06 |
| chancalan | input-lanjian | 24.3 ± 0.6 | 23.2 | 26.8 | 27.48 ± 40.22 |
| chancalan | input-chancalan | 24.3 ± 0.7 | 23.3 | 27.0 | 27.50 ± 40.24 |
| chancalan | input-pting | 24.3 ± 0.7 | 23.1 | 27.5 | 27.50 ± 40.25 |
| chancalan | input-kcen | 24.4 ± 0.8 | 23.0 | 27.0 | 27.60 ± 40.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>249390788</pre>|<pre>248750248</pre>|
|input-kcen|<pre>248812215</pre>|<pre>250057090</pre>|
|input-lanjian|<pre>249726565</pre>|<pre>251135960</pre>|
|input-mattcl|<pre>250453939</pre>|<pre>248652697</pre>|
|input-pting|<pre>253866470</pre>|<pre>254494947</pre>|