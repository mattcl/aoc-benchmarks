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
| lanjian | input-kcen | 1.0 ± 0.2 | 0.2 | 1.8 | 1.00 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.9 | 1.03 ± 0.33 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.6 | 1.04 ± 0.29 |
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.04 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.5 | 1.3 | 1.05 ± 0.28 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.7 | 1.05 ± 0.30 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.3 | 1.7 | 1.06 ± 0.30 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 1.3 | 1.06 ± 0.29 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.3 | 1.8 | 1.07 ± 0.33 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.6 | 1.7 | 1.07 ± 0.29 |
| aspidites | input-chancalan | 12.4 ± 0.6 | 11.0 | 14.0 | 12.45 ± 2.87 |
| mattcl-ts | input-aspidites | 12.5 ± 0.3 | 11.7 | 13.5 | 12.58 ± 2.86 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.2 | 13.3 | 12.64 ± 2.88 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.7 | 13.8 | 12.65 ± 2.88 |
| mattcl-ts | input-chancalan | 12.6 ± 0.3 | 11.6 | 13.7 | 12.67 ± 2.88 |
| aspidites | input-aspidites | 12.6 ± 0.5 | 11.7 | 14.0 | 12.68 ± 2.91 |
| aspidites | input-lanjian | 12.7 ± 0.5 | 11.3 | 14.1 | 12.76 ± 2.93 |
| mikofo | input-mattcl | 12.7 ± 0.3 | 11.7 | 14.5 | 12.77 ± 2.91 |
| mikofo | input-lanjian | 12.7 ± 0.4 | 11.5 | 14.3 | 12.79 ± 2.91 |
| mikofo | input-chancalan | 12.7 ± 0.4 | 11.8 | 14.0 | 12.80 ± 2.92 |
| aspidites | input-kcen | 12.7 ± 0.5 | 11.8 | 14.1 | 12.83 ± 2.94 |
| mattcl-ts | input-mattcl | 12.7 ± 2.6 | 11.7 | 48.7 | 12.83 ± 3.89 |
| mikofo | input-kcen | 12.8 ± 0.3 | 12.0 | 13.7 | 12.85 ± 2.92 |
| aspidites | input-mattcl | 12.8 ± 0.4 | 11.6 | 14.3 | 12.93 ± 2.96 |
| mikofo | input-aspidites | 14.0 ± 8.7 | 11.9 | 84.8 | 14.14 ± 9.33 |
| pting | input-kcen | 15.4 ± 0.4 | 14.8 | 18.0 | 15.52 ± 3.54 |
| pting | input-mattcl | 15.5 ± 0.5 | 14.6 | 17.9 | 15.58 ± 3.56 |
| pting | input-lanjian | 15.5 ± 0.7 | 14.5 | 18.7 | 15.62 ± 3.59 |
| pting | input-chancalan | 15.5 ± 0.6 | 14.6 | 18.4 | 15.63 ± 3.58 |
| pting | input-aspidites | 15.7 ± 0.6 | 14.3 | 18.3 | 15.82 ± 3.62 |
| chancalan | input-lanjian | 15.7 ± 0.6 | 14.9 | 19.1 | 15.84 ± 3.63 |
| chancalan | input-kcen | 15.9 ± 0.7 | 14.8 | 18.6 | 15.96 ± 3.67 |
| mattcl-py | input-kcen | 15.9 ± 0.8 | 14.7 | 18.7 | 15.97 ± 3.70 |
| chancalan | input-mattcl | 15.9 ± 0.8 | 14.7 | 19.0 | 16.00 ± 3.70 |
| mattcl-py | input-aspidites | 15.9 ± 0.7 | 14.7 | 18.8 | 16.01 ± 3.69 |
| mattcl-py | input-chancalan | 15.9 ± 0.7 | 14.9 | 19.1 | 16.01 ± 3.69 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 15.0 | 19.4 | 16.03 ± 3.69 |
| mattcl-py | input-lanjian | 16.0 ± 1.6 | 14.6 | 35.6 | 16.07 ± 3.99 |
| chancalan | input-chancalan | 16.0 ± 0.7 | 14.8 | 19.5 | 16.10 ± 3.71 |
| chancalan | input-aspidites | 16.3 ± 4.5 | 14.6 | 76.2 | 16.38 ± 5.88 |
| kcen | input-mattcl | 16.3 ± 0.6 | 15.3 | 18.9 | 16.45 ± 3.77 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.2 | 19.3 | 16.48 ± 3.78 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.6 | 19.5 | 16.56 ± 3.80 |
| kcen | input-aspidites | 16.5 ± 0.6 | 15.3 | 19.4 | 16.58 ± 3.80 |
| kcen | input-chancalan | 16.7 ± 3.0 | 15.3 | 55.6 | 16.81 ± 4.88 |


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