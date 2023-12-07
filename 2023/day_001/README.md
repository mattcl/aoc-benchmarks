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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.2 | 1.00 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.4 | 1.01 ± 0.27 |
| lanjian | input-lanjian | 1.0 ± 0.3 | 0.3 | 1.5 | 1.02 ± 0.33 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.2 | 1.02 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.26 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.03 ± 0.29 |
| lanjian | input-aspidites | 1.0 ± 0.1 | 0.5 | 1.2 | 1.04 ± 0.26 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.29 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.3 | 1.05 ± 0.27 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.8 | 1.06 ± 0.30 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.4 | 1.8 | 1.07 ± 0.28 |
| mattcl-ts | input-chancalan | 12.2 ± 0.4 | 11.3 | 13.1 | 12.29 ± 2.51 |
| mattcl-ts | input-aspidites | 12.2 ± 0.4 | 11.4 | 13.2 | 12.29 ± 2.52 |
| mattcl-ts | input-mattcl | 12.2 ± 0.4 | 11.3 | 13.2 | 12.30 ± 2.52 |
| mattcl-ts | input-kcen | 12.2 ± 0.4 | 11.4 | 13.2 | 12.32 ± 2.52 |
| mattcl-ts | input-lanjian | 12.3 ± 0.4 | 11.2 | 13.2 | 12.35 ± 2.52 |
| mattcl-ts | input-pting | 12.4 ± 0.4 | 11.5 | 13.3 | 12.45 ± 2.55 |
| aspidites | input-aspidites | 12.6 ± 2.5 | 11.1 | 47.0 | 12.73 ± 3.61 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.5 | 14.3 | 12.80 ± 2.63 |
| aspidites | input-mattcl | 12.7 ± 0.5 | 11.8 | 14.9 | 12.82 ± 2.64 |
| aspidites | input-chancalan | 12.8 ± 0.4 | 11.8 | 14.0 | 12.86 ± 2.64 |
| aspidites | input-pting | 12.8 ± 0.5 | 11.7 | 14.6 | 12.86 ± 2.64 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.8 | 15.0 | 12.88 ± 2.65 |
| pting | input-chancalan | 15.6 ± 0.6 | 14.7 | 18.6 | 15.68 ± 3.22 |
| pting | input-aspidites | 15.6 ± 0.7 | 14.2 | 18.5 | 15.70 ± 3.25 |
| pting | input-lanjian | 15.6 ± 0.6 | 14.7 | 18.4 | 15.71 ± 3.23 |
| pting | input-kcen | 15.6 ± 0.6 | 14.8 | 18.4 | 15.73 ± 3.23 |
| pting | input-pting | 15.7 ± 0.7 | 14.4 | 18.9 | 15.85 ± 3.28 |
| mattcl-py | input-aspidites | 15.7 ± 0.6 | 14.9 | 18.5 | 15.86 ± 3.27 |
| pting | input-mattcl | 15.8 ± 0.7 | 14.6 | 18.8 | 15.89 ± 3.30 |
| mattcl-py | input-kcen | 15.9 ± 0.6 | 15.0 | 19.4 | 16.05 ± 3.31 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.9 | 19.2 | 16.06 ± 3.32 |
| chancalan | input-lanjian | 16.0 ± 0.6 | 14.7 | 18.8 | 16.09 ± 3.30 |
| chancalan | input-aspidites | 16.0 ± 0.7 | 14.8 | 18.8 | 16.12 ± 3.34 |
| mattcl-py | input-lanjian | 16.0 ± 0.7 | 14.8 | 18.9 | 16.13 ± 3.33 |
| chancalan | input-kcen | 16.1 ± 0.6 | 15.1 | 19.6 | 16.17 ± 3.33 |
| mattcl-py | input-mattcl | 16.1 ± 0.8 | 14.6 | 19.2 | 16.17 ± 3.37 |
| mattcl-py | input-pting | 16.1 ± 0.7 | 15.0 | 18.9 | 16.17 ± 3.34 |
| chancalan | input-chancalan | 16.1 ± 0.8 | 14.6 | 18.8 | 16.20 ± 3.36 |
| chancalan | input-pting | 16.2 ± 0.7 | 15.0 | 19.3 | 16.28 ± 3.36 |
| chancalan | input-mattcl | 16.2 ± 0.7 | 14.9 | 19.2 | 16.30 ± 3.37 |
| kcen | input-aspidites | 16.4 ± 0.7 | 15.3 | 19.6 | 16.53 ± 3.40 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.4 | 20.0 | 16.55 ± 3.41 |
| kcen | input-kcen | 16.4 ± 0.6 | 15.1 | 19.1 | 16.57 ± 3.40 |
| kcen | input-mattcl | 16.5 ± 0.5 | 15.3 | 18.5 | 16.57 ± 3.38 |
| kcen | input-pting | 16.5 ± 0.7 | 15.6 | 20.1 | 16.61 ± 3.43 |
| kcen | input-lanjian | 16.7 ± 1.7 | 15.1 | 37.2 | 16.78 ± 3.81 |
| mikofo | input-kcen | 31.5 ± 0.5 | 30.1 | 32.8 | 31.70 ± 6.43 |
| mikofo | input-aspidites | 31.5 ± 0.4 | 30.5 | 32.4 | 31.70 ± 6.42 |
| mikofo | input-chancalan | 31.5 ± 0.5 | 30.6 | 33.2 | 31.72 ± 6.43 |
| mikofo | input-pting | 31.5 ± 0.5 | 30.5 | 32.6 | 31.75 ± 6.43 |
| mikofo | input-mattcl | 31.6 ± 0.4 | 30.4 | 32.6 | 31.81 ± 6.44 |
| mikofo | input-lanjian | 31.6 ± 0.5 | 30.6 | 33.0 | 31.82 ± 6.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|