# Day 1 benchmarks

[link to problem](https://adventofcode.com/2023/day/1)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 1)

- [aspidites](https://github.com/aspidites/aoc2023) (haskell)
- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-kcen | 1.0 ± 0.2 | 0.4 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.8 | 1.01 ± 0.25 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.25 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.2 | 1.8 | 1.02 ± 0.25 |
| mattcl | input-aspidites | 1.1 ± 0.1 | 0.5 | 1.5 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.6 | 1.04 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.26 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.7 | 1.05 ± 0.25 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.4 | 1.6 | 1.05 ± 0.26 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.6 | 1.8 | 1.05 ± 0.24 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.9 | 13.7 | 12.12 ± 2.19 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.7 | 13.9 | 12.15 ± 2.20 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.5 | 13.9 | 12.16 ± 2.20 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.9 | 13.6 | 12.18 ± 2.20 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.9 | 14.0 | 12.19 ± 2.20 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.8 | 14.1 | 12.25 ± 2.24 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.9 | 14.1 | 12.31 ± 2.24 |
| mikofo | input-chancalan | 12.8 ± 0.4 | 11.9 | 14.1 | 12.34 ± 2.24 |
| mikofo | input-mattcl | 12.8 ± 0.3 | 12.2 | 13.6 | 12.35 ± 2.23 |
| mikofo | input-lanjian | 12.8 ± 0.4 | 11.9 | 13.9 | 12.37 ± 2.24 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.4 | 12.37 ± 2.27 |
| mikofo | input-aspidites | 12.8 ± 0.4 | 11.6 | 13.8 | 12.38 ± 2.24 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.8 | 15.2 | 12.42 ± 2.28 |
| aspidites | input-aspidites | 12.9 ± 0.5 | 11.9 | 14.5 | 12.46 ± 2.28 |
| mikofo | input-kcen | 13.0 ± 2.2 | 12.2 | 43.8 | 12.57 ± 3.11 |
| pting | input-aspidites | 15.7 ± 0.6 | 14.6 | 18.7 | 15.13 ± 2.78 |
| pting | input-kcen | 15.7 ± 0.6 | 14.8 | 18.7 | 15.15 ± 2.78 |
| pting | input-chancalan | 15.8 ± 0.8 | 14.3 | 18.4 | 15.23 ± 2.83 |
| pting | input-lanjian | 15.8 ± 0.6 | 14.6 | 18.7 | 15.25 ± 2.80 |
| pting | input-mattcl | 15.8 ± 3.0 | 14.6 | 55.3 | 15.28 ± 3.98 |
| mattcl-py | input-aspidites | 15.9 ± 0.7 | 14.5 | 18.5 | 15.32 ± 2.81 |
| chancalan | input-lanjian | 15.9 ± 0.7 | 14.7 | 19.1 | 15.32 ± 2.83 |
| chancalan | input-chancalan | 15.9 ± 0.7 | 14.7 | 19.5 | 15.33 ± 2.82 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.9 | 18.6 | 15.40 ± 2.84 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.9 | 18.6 | 15.42 ± 2.83 |
| mattcl-py | input-lanjian | 16.0 ± 0.7 | 14.5 | 18.5 | 15.42 ± 2.84 |
| chancalan | input-mattcl | 16.0 ± 0.8 | 14.9 | 18.9 | 15.43 ± 2.86 |
| chancalan | input-aspidites | 16.0 ± 0.7 | 15.0 | 18.8 | 15.47 ± 2.86 |
| chancalan | input-kcen | 16.0 ± 0.7 | 14.6 | 19.7 | 15.48 ± 2.86 |
| mattcl-py | input-chancalan | 16.1 ± 1.6 | 14.7 | 35.9 | 15.54 ± 3.19 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.5 | 19.9 | 15.86 ± 2.92 |
| kcen | input-aspidites | 16.4 ± 0.6 | 15.3 | 19.9 | 15.86 ± 2.90 |
| kcen | input-lanjian | 16.4 ± 0.7 | 15.2 | 20.1 | 15.86 ± 2.92 |
| kcen | input-mattcl | 16.5 ± 0.6 | 15.8 | 19.7 | 15.93 ± 2.91 |
| kcen | input-chancalan | 16.5 ± 0.8 | 15.1 | 19.8 | 15.94 ± 2.95 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-mikofo|<pre>55538</pre>|<pre>54875</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|