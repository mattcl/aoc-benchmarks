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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.6 | 1.01 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.8 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.25 |
| lanjian | input-chancalan | 1.1 ± 0.2 | 0.5 | 1.6 | 1.02 ± 0.22 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.5 | 1.6 | 1.03 ± 0.23 |
| lanjian | input-lanjian | 1.1 ± 0.1 | 0.6 | 1.7 | 1.03 ± 0.22 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 2.0 | 1.04 ± 0.25 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 2.1 | 1.05 ± 0.25 |
| lanjian | input-aspidites | 1.1 ± 0.2 | 0.2 | 2.1 | 1.07 ± 0.26 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.4 | 11.86 ± 2.02 |
| mattcl-ts | input-chancalan | 12.7 ± 0.3 | 11.8 | 13.7 | 11.88 ± 2.02 |
| aspidites | input-kcen | 12.7 ± 0.6 | 11.5 | 14.1 | 11.89 ± 2.07 |
| mattcl-ts | input-mattcl | 12.7 ± 0.3 | 11.7 | 14.1 | 11.90 ± 2.03 |
| mattcl-ts | input-aspidites | 12.7 ± 0.3 | 12.0 | 14.5 | 11.93 ± 2.03 |
| aspidites | input-aspidites | 12.7 ± 0.4 | 11.9 | 13.8 | 11.94 ± 2.05 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.8 | 11.97 ± 2.06 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.8 | 14.7 | 11.99 ± 2.07 |
| aspidites | input-chancalan | 12.8 ± 0.5 | 11.5 | 15.1 | 12.02 ± 2.07 |
| mattcl-ts | input-kcen | 12.9 ± 3.5 | 12.0 | 61.4 | 12.11 ± 3.83 |
| mikofo | input-mattcl | 12.9 ± 0.3 | 12.2 | 13.7 | 12.13 ± 2.06 |
| mikofo | input-lanjian | 13.0 ± 0.3 | 12.1 | 13.8 | 12.19 ± 2.08 |
| mikofo | input-chancalan | 13.0 ± 0.5 | 11.9 | 16.7 | 12.20 ± 2.10 |
| mikofo | input-aspidites | 13.1 ± 0.3 | 12.3 | 14.0 | 12.24 ± 2.08 |
| mikofo | input-kcen | 13.2 ± 3.3 | 12.4 | 59.8 | 12.38 ± 3.75 |
| pting | input-kcen | 15.7 ± 0.7 | 14.6 | 18.7 | 14.75 ± 2.57 |
| pting | input-aspidites | 15.8 ± 0.6 | 14.8 | 18.4 | 14.80 ± 2.55 |
| pting | input-mattcl | 15.8 ± 0.5 | 14.6 | 18.7 | 14.82 ± 2.54 |
| pting | input-lanjian | 15.8 ± 0.6 | 14.7 | 18.4 | 14.85 ± 2.56 |
| chancalan | input-lanjian | 15.9 ± 0.5 | 14.9 | 18.7 | 14.92 ± 2.56 |
| mattcl-py | input-kcen | 16.0 ± 0.7 | 14.7 | 18.6 | 15.01 ± 2.60 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 15.0 | 19.3 | 15.02 ± 2.59 |
| chancalan | input-mattcl | 16.0 ± 0.6 | 14.8 | 18.5 | 15.03 ± 2.59 |
| chancalan | input-aspidites | 16.1 ± 0.7 | 15.0 | 19.3 | 15.08 ± 2.62 |
| mattcl-py | input-aspidites | 16.1 ± 0.7 | 14.8 | 19.6 | 15.09 ± 2.63 |
| mattcl-py | input-chancalan | 16.1 ± 0.7 | 14.9 | 19.3 | 15.09 ± 2.63 |
| chancalan | input-chancalan | 16.1 ± 0.7 | 14.7 | 19.7 | 15.10 ± 2.63 |
| mattcl-py | input-lanjian | 16.2 ± 0.7 | 14.8 | 19.3 | 15.14 ± 2.63 |
| chancalan | input-kcen | 16.2 ± 0.8 | 14.8 | 19.5 | 15.15 ± 2.66 |
| pting | input-chancalan | 16.3 ± 3.6 | 14.5 | 55.4 | 15.28 ± 4.26 |
| kcen | input-kcen | 16.5 ± 0.6 | 15.4 | 19.7 | 15.48 ± 2.67 |
| kcen | input-mattcl | 16.5 ± 0.7 | 15.2 | 19.8 | 15.49 ± 2.68 |
| kcen | input-aspidites | 16.6 ± 0.6 | 15.7 | 19.4 | 15.52 ± 2.68 |
| kcen | input-lanjian | 16.6 ± 0.6 | 15.7 | 19.4 | 15.58 ± 2.69 |
| kcen | input-chancalan | 16.6 ± 0.7 | 15.5 | 19.6 | 15.60 ± 2.71 |


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