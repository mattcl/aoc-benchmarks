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
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.3 | 1.1 | 1.00 ± 0.29 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.01 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.31 |
| mattcl | input-aspidites | 0.9 ± 0.1 | 0.2 | 1.4 | 1.05 ± 0.27 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.3 | 1.3 | 1.05 ± 0.27 |
| lanjian | input-lanjian | 1.8 ± 0.1 | 1.7 | 2.0 | 2.18 ± 0.45 |
| lanjian | input-mattcl | 1.8 ± 0.1 | 1.3 | 2.2 | 2.18 ± 0.45 |
| lanjian | input-pting | 1.8 ± 0.1 | 1.3 | 2.7 | 2.19 ± 0.48 |
| lanjian | input-aspidites | 1.9 ± 0.1 | 1.3 | 2.8 | 2.20 ± 0.47 |
| lanjian | input-chancalan | 1.9 ± 0.1 | 1.2 | 2.7 | 2.20 ± 0.48 |
| lanjian | input-kcen | 1.9 ± 0.2 | 1.2 | 2.8 | 2.20 ± 0.48 |
| aspidites | input-chancalan | 12.6 ± 0.4 | 11.8 | 13.9 | 14.93 ± 3.06 |
| aspidites | input-pting | 12.7 ± 0.4 | 11.7 | 14.0 | 15.03 ± 3.08 |
| aspidites | input-mattcl | 12.7 ± 0.4 | 11.8 | 14.1 | 15.11 ± 3.10 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.8 | 14.3 | 15.14 ± 3.11 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.7 | 14.8 | 15.15 ± 3.12 |
| aspidites | input-aspidites | 13.0 ± 4.2 | 11.1 | 63.1 | 15.43 ± 5.84 |
| pting | input-chancalan | 15.4 ± 0.6 | 14.4 | 19.0 | 18.24 ± 3.76 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.5 | 18.3 | 18.28 ± 3.76 |
| pting | input-aspidites | 15.4 ± 0.6 | 14.4 | 17.9 | 18.30 ± 3.76 |
| pting | input-pting | 15.4 ± 0.5 | 14.5 | 18.2 | 18.33 ± 3.76 |
| pting | input-mattcl | 15.5 ± 0.7 | 14.3 | 18.5 | 18.36 ± 3.80 |
| pting | input-kcen | 15.5 ± 0.8 | 14.3 | 19.0 | 18.44 ± 3.85 |
| mattcl-py | input-lanjian | 15.6 ± 0.6 | 14.7 | 19.1 | 18.53 ± 3.80 |
| mattcl-py | input-pting | 15.6 ± 0.4 | 14.9 | 17.9 | 18.55 ± 3.78 |
| mattcl-py | input-aspidites | 15.6 ± 0.6 | 14.8 | 18.3 | 18.57 ± 3.83 |
| mattcl-py | input-mattcl | 15.7 ± 0.5 | 14.8 | 18.0 | 18.58 ± 3.80 |
| mattcl-py | input-chancalan | 15.7 ± 0.6 | 14.7 | 19.0 | 18.68 ± 3.84 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 14.7 | 18.8 | 18.72 ± 3.88 |
| chancalan | input-aspidites | 15.8 ± 0.6 | 14.8 | 18.4 | 18.75 ± 3.86 |
| chancalan | input-kcen | 15.8 ± 0.6 | 14.8 | 18.6 | 18.79 ± 3.87 |
| chancalan | input-chancalan | 15.9 ± 0.6 | 14.8 | 19.6 | 18.83 ± 3.87 |
| chancalan | input-mattcl | 15.9 ± 0.6 | 15.1 | 18.7 | 18.84 ± 3.86 |
| chancalan | input-pting | 15.9 ± 0.7 | 14.6 | 19.1 | 18.91 ± 3.91 |
| chancalan | input-lanjian | 16.2 ± 3.0 | 14.7 | 48.7 | 19.26 ± 5.26 |
| kcen | input-lanjian | 16.3 ± 0.7 | 15.0 | 19.6 | 19.37 ± 4.01 |
| kcen | input-pting | 16.3 ± 0.7 | 15.0 | 19.3 | 19.40 ± 4.00 |
| kcen | input-aspidites | 16.3 ± 0.7 | 15.1 | 19.7 | 19.41 ± 4.01 |
| kcen | input-mattcl | 16.4 ± 0.7 | 15.5 | 19.6 | 19.46 ± 4.02 |
| kcen | input-chancalan | 16.4 ± 0.7 | 15.3 | 19.5 | 19.49 ± 4.02 |
| kcen | input-kcen | 16.4 ± 0.8 | 15.1 | 19.5 | 19.52 ± 4.06 |
| mattcl-ts | input-chancalan | 19.8 ± 0.3 | 18.6 | 21.0 | 23.49 ± 4.76 |
| mattcl-ts | input-mattcl | 19.8 ± 0.3 | 19.1 | 20.6 | 23.52 ± 4.77 |
| mattcl-ts | input-lanjian | 19.8 ± 0.4 | 18.8 | 20.8 | 23.56 ± 4.78 |
| mattcl-ts | input-aspidites | 19.9 ± 0.4 | 19.0 | 21.1 | 23.56 ± 4.79 |
| mattcl-ts | input-kcen | 19.9 ± 0.3 | 18.8 | 20.8 | 23.58 ± 4.78 |
| mattcl-ts | input-pting | 19.9 ± 0.3 | 19.0 | 20.9 | 23.63 ± 4.79 |
| mikofo | input-mattcl | 276.6 ± 1.3 | 274.8 | 278.4 | 328.27 ± 66.37 |
| mikofo | input-aspidites | 277.2 ± 1.3 | 275.3 | 279.1 | 329.05 ± 66.52 |
| mikofo | input-pting | 277.5 ± 1.8 | 274.8 | 280.8 | 329.34 ± 66.60 |
| mikofo | input-chancalan | 277.5 ± 1.9 | 274.9 | 281.0 | 329.39 ± 66.61 |
| mikofo | input-kcen | 277.7 ± 1.6 | 274.2 | 279.6 | 329.58 ± 66.64 |
| mikofo | input-lanjian | 279.3 ± 4.4 | 274.9 | 290.8 | 331.50 ± 67.21 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|