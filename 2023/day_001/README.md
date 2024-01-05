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
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.3 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.3 | 1.02 ± 0.24 |
| mattcl | input-chancalan | 1.1 ± 0.2 | 0.3 | 1.7 | 1.02 ± 0.24 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.4 | 1.9 | 1.03 ± 0.24 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 2.5 | 1.04 ± 0.26 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.4 | 2.6 | 1.04 ± 0.25 |
| mattcl | input-kcen | 1.1 ± 0.1 | 0.6 | 1.6 | 1.04 ± 0.22 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.5 | 1.4 | 1.05 ± 0.23 |
| lanjian | input-chancalan | 1.1 ± 0.1 | 0.6 | 1.6 | 1.05 ± 0.22 |
| mattcl | input-lanjian | 1.1 ± 0.1 | 0.5 | 1.7 | 1.06 ± 0.22 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.7 | 13.9 | 12.05 ± 2.02 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.7 | 13.3 | 12.05 ± 2.01 |
| mattcl-ts | input-aspidites | 12.6 ± 0.3 | 11.7 | 14.0 | 12.08 ± 2.02 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.9 | 13.4 | 12.08 ± 2.02 |
| mikofo | input-lanjian | 12.7 ± 0.3 | 11.8 | 13.6 | 12.16 ± 2.03 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.9 | 13.9 | 12.17 ± 2.05 |
| mikofo | input-kcen | 12.7 ± 0.3 | 11.8 | 13.6 | 12.18 ± 2.04 |
| aspidites | input-aspidites | 12.7 ± 0.5 | 11.8 | 13.9 | 12.19 ± 2.08 |
| mikofo | input-mattcl | 12.7 ± 0.3 | 11.9 | 13.5 | 12.20 ± 2.04 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.5 | 14.4 | 12.21 ± 2.08 |
| mikofo | input-aspidites | 12.8 ± 0.3 | 11.9 | 14.2 | 12.23 ± 2.05 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.7 | 13.8 | 12.26 ± 2.07 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.9 | 14.8 | 12.32 ± 2.09 |
| mikofo | input-chancalan | 13.0 ± 3.8 | 11.9 | 65.9 | 12.42 ± 4.16 |
| mattcl-ts | input-chancalan | 13.4 ± 6.1 | 11.3 | 72.7 | 12.84 ± 6.24 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.3 | 18.6 | 14.78 ± 2.51 |
| pting | input-mattcl | 15.4 ± 0.6 | 14.5 | 18.3 | 14.80 ± 2.52 |
| pting | input-kcen | 15.5 ± 0.6 | 14.6 | 18.9 | 14.82 ± 2.52 |
| pting | input-chancalan | 15.5 ± 0.6 | 14.5 | 19.0 | 14.83 ± 2.52 |
| pting | input-aspidites | 15.6 ± 0.7 | 14.8 | 18.4 | 14.95 ± 2.56 |
| chancalan | input-chancalan | 15.7 ± 0.4 | 14.8 | 17.6 | 15.04 ± 2.52 |
| chancalan | input-kcen | 15.7 ± 0.5 | 14.8 | 18.8 | 15.05 ± 2.55 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.8 | 18.7 | 15.06 ± 2.55 |
| chancalan | input-mattcl | 15.8 ± 0.7 | 14.7 | 18.5 | 15.10 ± 2.58 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.6 | 18.8 | 15.11 ± 2.58 |
| mattcl-py | input-aspidites | 15.8 ± 0.7 | 14.7 | 18.7 | 15.16 ± 2.59 |
| chancalan | input-aspidites | 15.8 ± 0.7 | 14.7 | 19.3 | 15.16 ± 2.59 |
| mattcl-py | input-mattcl | 15.9 ± 0.8 | 14.8 | 19.1 | 15.22 ± 2.62 |
| chancalan | input-lanjian | 15.9 ± 0.8 | 14.6 | 19.1 | 15.23 ± 2.64 |
| mattcl-py | input-chancalan | 15.9 ± 0.8 | 14.6 | 19.2 | 15.26 ± 2.63 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.2 | 19.5 | 15.70 ± 2.67 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.3 | 19.7 | 15.71 ± 2.69 |
| kcen | input-aspidites | 16.4 ± 0.6 | 15.3 | 19.2 | 15.71 ± 2.67 |
| kcen | input-mattcl | 16.4 ± 0.7 | 15.3 | 19.5 | 15.74 ± 2.68 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.6 | 19.7 | 15.74 ± 2.67 |


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