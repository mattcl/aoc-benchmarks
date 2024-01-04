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
| mattcl | input-chancalan | 0.8 ± 0.3 | 0.3 | 1.3 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 3.0 | 0.3 | 42.8 | 1.03 ± 3.84 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.3 | 1.7 | 1.43 ± 0.63 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.6 | 1.8 | 1.44 ± 0.64 |
| mattcl | input-aspidites | 1.1 ± 0.2 | 0.3 | 1.7 | 1.45 ± 0.64 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.45 ± 0.64 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.7 | 1.47 ± 0.64 |
| lanjian | input-aspidites | 1.2 ± 0.1 | 0.6 | 1.7 | 1.47 ± 0.63 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.9 | 1.48 ± 0.65 |
| lanjian | input-lanjian | 1.2 ± 0.1 | 0.6 | 1.7 | 1.50 ± 0.64 |
| mattcl-ts | input-aspidites | 12.7 ± 0.3 | 11.8 | 14.0 | 16.20 ± 6.67 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.9 | 13.8 | 16.21 ± 6.68 |
| mattcl-ts | input-kcen | 12.8 ± 0.3 | 12.0 | 13.6 | 16.27 ± 6.70 |
| aspidites | input-kcen | 12.8 ± 0.5 | 11.9 | 14.6 | 16.29 ± 6.73 |
| aspidites | input-aspidites | 12.8 ± 0.4 | 11.9 | 14.2 | 16.30 ± 6.72 |
| aspidites | input-chancalan | 12.9 ± 0.4 | 11.8 | 14.3 | 16.39 ± 6.76 |
| aspidites | input-lanjian | 12.9 ± 0.5 | 11.8 | 15.1 | 16.40 ± 6.78 |
| aspidites | input-mattcl | 12.9 ± 0.5 | 11.9 | 14.6 | 16.50 ± 6.81 |
| mikofo | input-chancalan | 13.0 ± 0.3 | 12.2 | 13.8 | 16.60 ± 6.84 |
| mikofo | input-lanjian | 13.0 ± 0.4 | 12.1 | 13.9 | 16.62 ± 6.85 |
| mikofo | input-kcen | 13.0 ± 0.3 | 12.1 | 13.8 | 16.63 ± 6.85 |
| mikofo | input-aspidites | 13.1 ± 0.4 | 12.0 | 14.8 | 16.66 ± 6.87 |
| mattcl-ts | input-chancalan | 13.2 ± 4.7 | 11.8 | 62.3 | 16.81 ± 9.15 |
| mattcl-ts | input-mattcl | 13.2 ± 3.6 | 11.7 | 46.6 | 16.83 ± 8.33 |
| mikofo | input-mattcl | 13.5 ± 4.2 | 12.3 | 59.5 | 17.23 ± 8.90 |
| pting | input-kcen | 15.8 ± 0.6 | 14.7 | 18.1 | 20.10 ± 8.30 |
| pting | input-lanjian | 15.8 ± 0.6 | 14.9 | 19.1 | 20.13 ± 8.31 |
| pting | input-aspidites | 15.8 ± 0.7 | 14.8 | 19.3 | 20.19 ± 8.35 |
| pting | input-chancalan | 15.9 ± 0.7 | 14.9 | 18.7 | 20.26 ± 8.37 |
| mattcl-py | input-aspidites | 16.0 ± 0.6 | 14.7 | 18.7 | 20.44 ± 8.44 |
| chancalan | input-aspidites | 16.0 ± 0.7 | 15.0 | 19.2 | 20.46 ± 8.46 |
| mattcl-py | input-kcen | 16.1 ± 0.8 | 15.0 | 18.9 | 20.50 ± 8.48 |
| chancalan | input-chancalan | 16.1 ± 0.7 | 14.9 | 19.3 | 20.57 ± 8.51 |
| mattcl-py | input-lanjian | 16.1 ± 0.8 | 14.9 | 18.9 | 20.57 ± 8.51 |
| chancalan | input-mattcl | 16.2 ± 0.8 | 15.1 | 19.8 | 20.61 ± 8.53 |
| chancalan | input-lanjian | 16.2 ± 0.8 | 14.9 | 19.4 | 20.66 ± 8.55 |
| mattcl-py | input-mattcl | 16.2 ± 0.8 | 14.9 | 19.8 | 20.67 ± 8.55 |
| chancalan | input-kcen | 16.2 ± 0.7 | 15.0 | 19.1 | 20.71 ± 8.56 |
| pting | input-mattcl | 16.3 ± 3.3 | 14.8 | 50.0 | 20.73 ± 9.50 |
| kcen | input-lanjian | 16.5 ± 0.6 | 15.2 | 19.6 | 21.05 ± 8.69 |
| mattcl-py | input-chancalan | 16.5 ± 3.6 | 15.0 | 53.9 | 21.09 ± 9.82 |
| kcen | input-mattcl | 16.7 ± 0.7 | 15.5 | 19.4 | 21.25 ± 8.78 |
| kcen | input-aspidites | 16.7 ± 0.7 | 15.7 | 19.7 | 21.25 ± 8.78 |
| kcen | input-kcen | 16.9 ± 0.9 | 15.7 | 22.2 | 21.52 ± 8.92 |
| kcen | input-chancalan | 17.0 ± 2.7 | 15.6 | 45.0 | 21.63 ± 9.55 |


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