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
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 ± 0.29 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.9 | 1.00 ± 0.30 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.4 | 1.4 | 1.01 ± 0.26 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.7 | 1.01 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.5 | 1.04 ± 0.28 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.7 | 1.04 ± 0.28 |
| lanjian | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.6 | 1.06 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.5 | 1.4 | 1.07 ± 0.26 |
| mattcl-ts | input-aspidites | 12.5 ± 0.3 | 11.7 | 13.3 | 12.84 ± 2.52 |
| mattcl-ts | input-lanjian | 12.5 ± 0.3 | 11.6 | 13.6 | 12.84 ± 2.52 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.7 | 13.3 | 12.86 ± 2.52 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.5 | 13.3 | 12.86 ± 2.52 |
| mattcl-ts | input-chancalan | 12.5 ± 0.3 | 11.4 | 13.6 | 12.87 ± 2.53 |
| mikofo | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.7 | 12.94 ± 2.54 |
| mikofo | input-lanjian | 12.6 ± 0.3 | 11.6 | 13.7 | 12.98 ± 2.55 |
| aspidites | input-kcen | 12.6 ± 0.4 | 11.5 | 13.8 | 12.99 ± 2.57 |
| mikofo | input-kcen | 12.6 ± 0.3 | 11.8 | 13.6 | 12.99 ± 2.55 |
| aspidites | input-aspidites | 12.7 ± 0.4 | 11.8 | 14.2 | 13.01 ± 2.57 |
| mikofo | input-chancalan | 12.7 ± 0.3 | 11.9 | 13.5 | 13.02 ± 2.55 |
| mikofo | input-aspidites | 12.7 ± 0.3 | 11.7 | 13.5 | 13.02 ± 2.56 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.4 | 14.0 | 13.04 ± 2.58 |
| aspidites | input-lanjian | 12.7 ± 0.4 | 11.5 | 14.1 | 13.05 ± 2.58 |
| aspidites | input-mattcl | 12.8 ± 0.5 | 11.6 | 14.3 | 13.11 ± 2.60 |
| pting | input-kcen | 15.4 ± 0.6 | 14.5 | 18.7 | 15.80 ± 3.15 |
| pting | input-mattcl | 15.4 ± 0.7 | 14.2 | 18.5 | 15.83 ± 3.17 |
| pting | input-aspidites | 15.4 ± 0.6 | 14.4 | 19.0 | 15.84 ± 3.15 |
| pting | input-lanjian | 15.5 ± 0.7 | 14.5 | 18.4 | 15.88 ± 3.17 |
| chancalan | input-aspidites | 15.6 ± 0.4 | 14.7 | 17.8 | 15.99 ± 3.15 |
| mattcl-py | input-chancalan | 15.7 ± 0.6 | 14.6 | 19.2 | 16.08 ± 3.20 |
| mattcl-py | input-aspidites | 15.7 ± 0.6 | 14.8 | 18.5 | 16.11 ± 3.19 |
| chancalan | input-lanjian | 15.7 ± 0.7 | 14.7 | 18.7 | 16.14 ± 3.24 |
| pting | input-chancalan | 15.7 ± 3.1 | 14.5 | 57.6 | 16.15 ± 4.50 |
| chancalan | input-mattcl | 15.7 ± 0.7 | 15.0 | 19.1 | 16.16 ± 3.23 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.7 | 18.6 | 16.17 ± 3.22 |
| chancalan | input-kcen | 15.8 ± 0.7 | 14.6 | 18.8 | 16.19 ± 3.24 |
| chancalan | input-chancalan | 15.8 ± 0.7 | 14.8 | 18.5 | 16.19 ± 3.23 |
| mattcl-py | input-lanjian | 15.8 ± 0.8 | 14.9 | 19.2 | 16.25 ± 3.26 |
| mattcl-py | input-kcen | 16.0 ± 3.2 | 14.5 | 53.0 | 16.45 ± 4.57 |
| kcen | input-lanjian | 16.3 ± 0.6 | 15.1 | 18.8 | 16.70 ± 3.32 |
| kcen | input-kcen | 16.3 ± 0.9 | 15.2 | 25.9 | 16.74 ± 3.38 |
| kcen | input-aspidites | 16.3 ± 0.6 | 15.3 | 19.3 | 16.74 ± 3.33 |
| kcen | input-mattcl | 16.3 ± 0.7 | 15.3 | 19.7 | 16.76 ± 3.33 |
| kcen | input-chancalan | 16.3 ± 0.7 | 15.0 | 19.6 | 16.79 ± 3.36 |


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