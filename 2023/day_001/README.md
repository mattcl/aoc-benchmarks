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
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.3 | 1.10 ± 0.43 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.14 ± 0.41 |
| mattcl | input-aspidites | 0.9 ± 0.2 | 0.2 | 1.2 | 1.14 ± 0.40 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.4 | 1.2 | 1.19 ± 0.40 |
| mattcl | input-chancalan | 1.0 ± 0.1 | 0.6 | 1.1 | 1.20 ± 0.39 |
| lanjian | input-lanjian | 1.9 ± 0.1 | 1.2 | 2.4 | 2.32 ± 0.73 |
| lanjian | input-chancalan | 1.9 ± 0.2 | 1.0 | 2.6 | 2.33 ± 0.74 |
| lanjian | input-aspidites | 1.9 ± 0.2 | 1.2 | 2.7 | 2.33 ± 0.74 |
| lanjian | input-pting | 1.9 ± 0.2 | 1.3 | 2.8 | 2.34 ± 0.75 |
| lanjian | input-mattcl | 1.9 ± 0.2 | 1.4 | 2.9 | 2.37 ± 0.77 |
| lanjian | input-kcen | 2.1 ± 2.9 | 1.2 | 43.1 | 2.59 ± 3.72 |
| aspidites | input-chancalan | 12.6 ± 0.5 | 11.3 | 14.1 | 15.72 ± 4.85 |
| aspidites | input-pting | 12.7 ± 0.5 | 11.5 | 14.2 | 15.83 ± 4.89 |
| aspidites | input-aspidites | 12.8 ± 0.5 | 11.5 | 14.1 | 15.91 ± 4.91 |
| aspidites | input-lanjian | 12.8 ± 0.5 | 11.5 | 14.4 | 15.92 ± 4.92 |
| aspidites | input-kcen | 12.9 ± 0.5 | 11.7 | 14.1 | 16.03 ± 4.95 |
| aspidites | input-mattcl | 12.9 ± 0.4 | 11.9 | 14.2 | 16.04 ± 4.95 |
| pting | input-aspidites | 15.7 ± 0.6 | 14.7 | 18.6 | 19.47 ± 6.02 |
| pting | input-mattcl | 15.7 ± 0.7 | 14.4 | 18.8 | 19.50 ± 6.03 |
| pting | input-pting | 15.7 ± 0.6 | 14.7 | 18.6 | 19.50 ± 6.03 |
| pting | input-chancalan | 15.7 ± 0.7 | 14.6 | 18.5 | 19.55 ± 6.05 |
| pting | input-lanjian | 15.8 ± 0.8 | 14.9 | 19.3 | 19.63 ± 6.09 |
| pting | input-kcen | 15.8 ± 0.7 | 14.6 | 18.9 | 19.68 ± 6.10 |
| mattcl-py | input-lanjian | 15.8 ± 0.5 | 14.7 | 18.0 | 19.69 ± 6.06 |
| mattcl-py | input-aspidites | 15.9 ± 0.7 | 14.8 | 19.0 | 19.83 ± 6.14 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.9 | 19.1 | 19.83 ± 6.14 |
| mattcl-py | input-chancalan | 16.0 ± 0.7 | 14.7 | 19.6 | 19.90 ± 6.15 |
| chancalan | input-aspidites | 16.0 ± 0.7 | 14.9 | 18.8 | 19.94 ± 6.17 |
| mattcl-py | input-pting | 16.0 ± 0.7 | 14.9 | 19.2 | 19.95 ± 6.17 |
| mattcl-py | input-kcen | 16.2 ± 2.7 | 14.9 | 51.5 | 20.09 ± 7.04 |
| chancalan | input-pting | 16.2 ± 0.5 | 15.1 | 18.5 | 20.09 ± 6.19 |
| chancalan | input-chancalan | 16.2 ± 0.7 | 15.0 | 19.1 | 20.10 ± 6.23 |
| chancalan | input-lanjian | 16.2 ± 0.6 | 15.1 | 19.7 | 20.11 ± 6.22 |
| chancalan | input-mattcl | 16.2 ± 0.7 | 15.2 | 20.0 | 20.11 ± 6.23 |
| chancalan | input-kcen | 16.2 ± 0.6 | 15.2 | 19.6 | 20.19 ± 6.24 |
| kcen | input-aspidites | 16.4 ± 0.6 | 15.6 | 19.3 | 20.36 ± 6.28 |
| kcen | input-kcen | 16.5 ± 0.5 | 15.6 | 19.8 | 20.51 ± 6.32 |
| kcen | input-lanjian | 16.5 ± 0.7 | 15.3 | 20.1 | 20.51 ± 6.35 |
| kcen | input-chancalan | 16.6 ± 0.7 | 15.4 | 19.5 | 20.61 ± 6.38 |
| kcen | input-pting | 16.6 ± 0.7 | 15.4 | 20.2 | 20.63 ± 6.39 |
| kcen | input-mattcl | 16.6 ± 0.8 | 15.2 | 19.9 | 20.65 ± 6.41 |
| mattcl-ts | input-chancalan | 20.1 ± 0.4 | 19.1 | 21.4 | 24.99 ± 7.67 |
| mattcl-ts | input-aspidites | 20.1 ± 0.4 | 19.3 | 21.1 | 24.99 ± 7.67 |
| mattcl-ts | input-kcen | 20.1 ± 0.4 | 19.1 | 21.3 | 25.06 ± 7.70 |
| mattcl-ts | input-lanjian | 20.2 ± 0.4 | 19.3 | 21.6 | 25.13 ± 7.72 |
| mattcl-ts | input-mattcl | 20.3 ± 0.4 | 19.4 | 21.8 | 25.20 ± 7.74 |
| mattcl-ts | input-pting | 20.3 ± 0.4 | 19.4 | 21.4 | 25.25 ± 7.75 |
| mikofo | input-aspidites | 280.3 ± 1.2 | 279.0 | 282.6 | 348.60 ± 106.84 |
| mikofo | input-lanjian | 280.4 ± 2.6 | 277.2 | 284.2 | 348.76 ± 106.93 |
| mikofo | input-chancalan | 280.8 ± 1.4 | 278.9 | 282.9 | 349.27 ± 107.05 |
| mikofo | input-kcen | 280.9 ± 1.7 | 277.8 | 284.0 | 349.40 ± 107.09 |
| mikofo | input-pting | 281.4 ± 1.8 | 278.4 | 283.7 | 349.92 ± 107.26 |
| mikofo | input-mattcl | 281.9 ± 1.4 | 279.0 | 283.7 | 350.56 ± 107.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|