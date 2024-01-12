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
| lanjian | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.3 | 1.00 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.5 | 1.00 ± 0.30 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.6 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.2 | 1.6 | 1.02 ± 0.29 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.3 | 1.2 | 1.02 ± 0.29 |
| lanjian | input-aspidites | 1.0 ± 0.2 | 0.3 | 1.6 | 1.03 ± 0.28 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.03 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.4 | 2.0 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.4 | 1.05 ± 0.27 |
| mattcl-ts | input-chancalan | 12.0 ± 0.4 | 10.7 | 12.9 | 12.21 ± 2.70 |
| mattcl-ts | input-lanjian | 12.1 ± 0.4 | 11.2 | 13.1 | 12.29 ± 2.71 |
| mikofo | input-chancalan | 12.1 ± 0.4 | 10.9 | 13.3 | 12.29 ± 2.71 |
| mattcl-ts | input-kcen | 12.1 ± 0.4 | 11.0 | 13.2 | 12.30 ± 2.71 |
| mattcl-ts | input-mattcl | 12.1 ± 0.4 | 11.0 | 13.1 | 12.35 ± 2.73 |
| mikofo | input-mattcl | 12.1 ± 0.5 | 11.1 | 14.2 | 12.36 ± 2.73 |
| mikofo | input-kcen | 12.1 ± 0.4 | 11.1 | 13.5 | 12.36 ± 2.73 |
| mattcl-ts | input-aspidites | 12.2 ± 0.4 | 11.1 | 13.0 | 12.37 ± 2.73 |
| mikofo | input-lanjian | 12.2 ± 0.4 | 11.0 | 13.1 | 12.40 ± 2.73 |
| mikofo | input-aspidites | 12.2 ± 0.4 | 11.1 | 13.4 | 12.42 ± 2.74 |
| aspidites | input-kcen | 12.6 ± 0.4 | 11.7 | 14.0 | 12.77 ± 2.82 |
| aspidites | input-aspidites | 12.6 ± 0.4 | 11.7 | 13.8 | 12.80 ± 2.81 |
| aspidites | input-mattcl | 12.6 ± 0.4 | 11.4 | 14.0 | 12.84 ± 2.83 |
| aspidites | input-chancalan | 12.7 ± 0.5 | 11.9 | 14.8 | 12.91 ± 2.85 |
| aspidites | input-lanjian | 12.8 ± 4.3 | 11.5 | 73.0 | 13.07 ± 5.22 |
| pting | input-chancalan | 15.4 ± 0.5 | 14.5 | 18.6 | 15.63 ± 3.44 |
| pting | input-lanjian | 15.4 ± 0.6 | 14.3 | 18.5 | 15.70 ± 3.48 |
| pting | input-mattcl | 15.4 ± 0.6 | 14.6 | 19.0 | 15.71 ± 3.48 |
| pting | input-aspidites | 15.5 ± 0.6 | 14.7 | 18.5 | 15.74 ± 3.49 |
| chancalan | input-kcen | 15.7 ± 0.6 | 14.8 | 18.3 | 15.94 ± 3.52 |
| chancalan | input-aspidites | 15.7 ± 0.6 | 14.7 | 18.5 | 15.95 ± 3.53 |
| chancalan | input-mattcl | 15.7 ± 0.6 | 14.6 | 18.6 | 15.97 ± 3.53 |
| mattcl-py | input-aspidites | 15.7 ± 0.6 | 14.7 | 18.4 | 15.99 ± 3.54 |
| chancalan | input-lanjian | 15.7 ± 0.8 | 14.6 | 18.8 | 16.00 ± 3.57 |
| mattcl-py | input-chancalan | 15.7 ± 0.6 | 14.7 | 18.2 | 16.00 ± 3.54 |
| mattcl-py | input-lanjian | 15.8 ± 0.7 | 14.7 | 18.8 | 16.05 ± 3.57 |
| mattcl-py | input-mattcl | 15.8 ± 0.6 | 14.8 | 18.4 | 16.06 ± 3.55 |
| chancalan | input-chancalan | 15.8 ± 0.8 | 14.8 | 19.3 | 16.07 ± 3.59 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.8 | 18.4 | 16.07 ± 3.55 |
| pting | input-kcen | 15.8 ± 4.3 | 14.3 | 72.8 | 16.09 ± 5.60 |
| kcen | input-mattcl | 16.3 ± 0.7 | 15.1 | 19.5 | 16.61 ± 3.70 |
| kcen | input-chancalan | 16.3 ± 0.6 | 15.2 | 19.5 | 16.61 ± 3.68 |
| kcen | input-kcen | 16.4 ± 0.7 | 15.0 | 19.5 | 16.65 ± 3.70 |
| kcen | input-aspidites | 16.4 ± 0.8 | 15.1 | 19.6 | 16.66 ± 3.72 |
| kcen | input-lanjian | 16.4 ± 0.6 | 15.2 | 19.5 | 16.67 ± 3.69 |


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