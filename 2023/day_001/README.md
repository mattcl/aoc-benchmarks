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
- [mikofo](https://github.com/mikofo/advent-of-code-2023) (javascript)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.29 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.5 | 1.5 | 1.04 ± 0.29 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.3 | 1.5 | 1.04 ± 0.30 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.4 | 1.8 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.2 | 2.1 | 1.08 ± 0.33 |
| lanjian | input-chancalan | 1.9 ± 0.3 | 1.7 | 3.0 | 1.96 ± 0.54 |
| lanjian | input-mattcl | 1.9 ± 0.3 | 1.3 | 2.8 | 1.97 ± 0.53 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.2 | 2.8 | 1.97 ± 0.53 |
| lanjian | input-aspidites | 2.0 ± 0.3 | 1.7 | 2.8 | 1.99 ± 0.53 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.3 | 3.3 | 2.01 ± 0.56 |
| lanjian | input-pting | 2.0 ± 0.3 | 1.3 | 2.9 | 2.01 ± 0.56 |
| aspidites | input-aspidites | 13.0 ± 0.4 | 11.8 | 14.2 | 13.20 ± 3.08 |
| aspidites | input-mattcl | 13.1 ± 0.5 | 12.0 | 14.7 | 13.29 ± 3.11 |
| aspidites | input-lanjian | 13.2 ± 0.5 | 12.1 | 14.6 | 13.35 ± 3.12 |
| aspidites | input-chancalan | 13.2 ± 0.4 | 12.2 | 14.4 | 13.35 ± 3.12 |
| aspidites | input-pting | 13.2 ± 0.5 | 12.1 | 14.6 | 13.36 ± 3.12 |
| aspidites | input-kcen | 13.4 ± 4.0 | 11.2 | 57.2 | 13.56 ± 5.14 |
| pting | input-lanjian | 18.1 ± 0.5 | 17.2 | 20.8 | 18.33 ± 4.27 |
| pting | input-kcen | 18.1 ± 0.6 | 17.2 | 21.5 | 18.38 ± 4.28 |
| pting | input-aspidites | 18.2 ± 0.7 | 17.2 | 21.1 | 18.47 ± 4.32 |
| pting | input-mattcl | 18.4 ± 0.8 | 17.2 | 21.6 | 18.61 ± 4.37 |
| pting | input-chancalan | 18.4 ± 0.9 | 17.2 | 21.6 | 18.64 ± 4.40 |
| pting | input-pting | 18.4 ± 0.9 | 17.2 | 21.5 | 18.70 ± 4.42 |
| chancalan | input-pting | 18.6 ± 0.6 | 17.5 | 21.5 | 18.90 ± 4.40 |
| mattcl-py | input-lanjian | 18.7 ± 0.6 | 17.8 | 21.6 | 18.92 ± 4.42 |
| chancalan | input-aspidites | 18.7 ± 0.7 | 17.6 | 22.0 | 18.95 ± 4.44 |
| mattcl-py | input-aspidites | 18.7 ± 0.6 | 17.7 | 21.7 | 18.96 ± 4.42 |
| mattcl-py | input-kcen | 18.7 ± 0.8 | 17.3 | 21.7 | 18.97 ± 4.46 |
| mattcl-py | input-mattcl | 18.7 ± 0.7 | 17.6 | 21.9 | 18.97 ± 4.43 |
| chancalan | input-chancalan | 18.7 ± 0.8 | 17.4 | 21.7 | 18.97 ± 4.45 |
| chancalan | input-lanjian | 18.7 ± 0.8 | 17.6 | 22.3 | 18.99 ± 4.46 |
| chancalan | input-mattcl | 18.8 ± 0.8 | 17.8 | 22.2 | 19.03 ± 4.47 |
| mattcl-py | input-chancalan | 18.8 ± 0.6 | 17.8 | 21.4 | 19.03 ± 4.44 |
| chancalan | input-kcen | 18.8 ± 0.7 | 17.8 | 21.8 | 19.03 ± 4.46 |
| kcen | input-aspidites | 19.0 ± 0.7 | 17.7 | 22.1 | 19.25 ± 4.51 |
| kcen | input-lanjian | 19.0 ± 0.7 | 18.0 | 21.9 | 19.31 ± 4.52 |
| kcen | input-pting | 19.1 ± 0.8 | 17.8 | 22.8 | 19.32 ± 4.54 |
| kcen | input-kcen | 19.1 ± 0.8 | 18.0 | 22.2 | 19.37 ± 4.54 |
| kcen | input-chancalan | 19.1 ± 0.8 | 18.1 | 21.8 | 19.39 ± 4.54 |
| kcen | input-mattcl | 19.1 ± 0.8 | 18.2 | 22.0 | 19.41 ± 4.55 |
| mattcl-py | input-pting | 19.5 ± 5.1 | 17.8 | 72.3 | 19.78 ± 6.92 |
| mikofo | input-kcen | 318.5 ± 3.2 | 314.2 | 321.7 | 323.09 ± 74.68 |
| mikofo | input-aspidites | 318.6 ± 2.8 | 313.9 | 322.6 | 323.20 ± 74.69 |
| mikofo | input-lanjian | 319.2 ± 1.3 | 317.6 | 321.3 | 323.79 ± 74.78 |
| mikofo | input-chancalan | 319.5 ± 1.0 | 318.5 | 321.4 | 324.12 ± 74.85 |
| mikofo | input-pting | 319.8 ± 2.1 | 316.1 | 322.8 | 324.39 ± 74.94 |
| mikofo | input-mattcl | 320.3 ± 1.8 | 317.4 | 323.4 | 324.85 ± 75.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|