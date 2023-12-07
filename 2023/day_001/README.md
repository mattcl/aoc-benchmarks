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
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.2 | 1.01 ± 0.28 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.03 ± 0.29 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.3 | 1.04 ± 0.33 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.4 | 1.06 ± 0.28 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.6 | 1.07 ± 0.27 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.3 | 1.07 ± 0.28 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.5 | 1.09 ± 0.29 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.3 | 1.09 ± 0.28 |
| lanjian | input-aspidites | 1.1 ± 0.1 | 0.3 | 1.3 | 1.09 ± 0.27 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.5 | 1.4 | 1.11 ± 0.28 |
| mattcl-ts | input-chancalan | 12.1 ± 0.4 | 11.0 | 13.1 | 12.49 ± 2.57 |
| mattcl-ts | input-aspidites | 12.1 ± 0.4 | 11.2 | 13.0 | 12.50 ± 2.57 |
| mattcl-ts | input-kcen | 12.1 ± 0.4 | 11.2 | 13.4 | 12.56 ± 2.59 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 10.8 | 13.2 | 12.56 ± 2.59 |
| mattcl-ts | input-pting | 12.2 ± 0.4 | 11.1 | 13.1 | 12.60 ± 2.60 |
| aspidites | input-aspidites | 12.7 ± 0.4 | 11.6 | 14.2 | 13.16 ± 2.72 |
| aspidites | input-pting | 12.7 ± 0.4 | 11.6 | 14.2 | 13.17 ± 2.72 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.3 | 13.24 ± 2.74 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.9 | 14.0 | 13.24 ± 2.74 |
| aspidites | input-chancalan | 12.9 ± 0.4 | 12.0 | 14.4 | 13.33 ± 2.75 |
| aspidites | input-mattcl | 12.9 ± 0.4 | 11.9 | 14.1 | 13.33 ± 2.75 |
| mattcl-ts | input-lanjian | 12.9 ± 5.2 | 11.2 | 49.9 | 13.39 ± 6.03 |
| pting | input-aspidites | 15.4 ± 0.6 | 14.4 | 18.5 | 15.95 ± 3.32 |
| pting | input-kcen | 15.5 ± 0.6 | 14.4 | 19.1 | 16.02 ± 3.33 |
| pting | input-pting | 15.5 ± 0.6 | 14.5 | 18.3 | 16.02 ± 3.31 |
| pting | input-mattcl | 15.5 ± 0.6 | 14.6 | 18.3 | 16.03 ± 3.32 |
| pting | input-chancalan | 15.5 ± 0.7 | 14.5 | 18.8 | 16.05 ± 3.35 |
| pting | input-lanjian | 15.5 ± 0.8 | 14.5 | 18.8 | 16.07 ± 3.37 |
| mattcl-py | input-aspidites | 15.7 ± 0.7 | 14.7 | 19.8 | 16.24 ± 3.39 |
| mattcl-py | input-chancalan | 15.7 ± 0.7 | 14.7 | 18.7 | 16.26 ± 3.39 |
| mattcl-py | input-kcen | 15.7 ± 0.7 | 14.9 | 19.0 | 16.30 ± 3.39 |
| chancalan | input-aspidites | 15.8 ± 0.6 | 14.9 | 18.4 | 16.32 ± 3.38 |
| mattcl-py | input-mattcl | 15.8 ± 0.8 | 14.7 | 19.2 | 16.32 ± 3.42 |
| mattcl-py | input-pting | 15.9 ± 0.8 | 14.7 | 18.8 | 16.43 ± 3.44 |
| mattcl-py | input-lanjian | 15.9 ± 0.8 | 14.7 | 19.5 | 16.43 ± 3.45 |
| chancalan | input-chancalan | 15.9 ± 0.6 | 15.0 | 19.7 | 16.48 ± 3.42 |
| chancalan | input-lanjian | 15.9 ± 0.8 | 14.7 | 19.2 | 16.50 ± 3.45 |
| chancalan | input-kcen | 15.9 ± 0.6 | 14.9 | 18.6 | 16.51 ± 3.43 |
| chancalan | input-mattcl | 16.0 ± 0.6 | 14.7 | 18.6 | 16.52 ± 3.43 |
| chancalan | input-pting | 16.0 ± 0.8 | 14.9 | 18.7 | 16.60 ± 3.47 |
| kcen | input-aspidites | 16.2 ± 0.6 | 15.1 | 19.3 | 16.78 ± 3.48 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.7 | 16.89 ± 3.51 |
| kcen | input-chancalan | 16.3 ± 0.6 | 15.4 | 19.2 | 16.92 ± 3.51 |
| kcen | input-pting | 16.4 ± 0.5 | 15.3 | 18.8 | 16.95 ± 3.49 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.2 | 19.8 | 16.95 ± 3.54 |
| kcen | input-mattcl | 16.4 ± 0.8 | 15.3 | 19.6 | 17.02 ± 3.56 |
| mikofo | input-aspidites | 31.3 ± 0.4 | 30.5 | 32.6 | 32.42 ± 6.62 |
| mikofo | input-chancalan | 31.4 ± 0.4 | 30.3 | 32.7 | 32.47 ± 6.63 |
| mikofo | input-kcen | 31.4 ± 0.4 | 30.5 | 32.7 | 32.53 ± 6.64 |
| mikofo | input-pting | 31.5 ± 0.5 | 30.4 | 32.7 | 32.60 ± 6.65 |
| mikofo | input-mattcl | 31.7 ± 1.6 | 30.7 | 46.6 | 32.82 ± 6.89 |
| mikofo | input-lanjian | 33.0 ± 8.9 | 30.3 | 86.5 | 34.18 ± 11.52 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|