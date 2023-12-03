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
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-aspidites | 1.0 ± 0.2 | 0.5 | 1.2 | 1.00 |
| mattcl | input-chancalan | 1.0 ± 0.2 | 0.5 | 1.5 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.3 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.22 |
| mattcl | input-pting | 1.1 ± 0.1 | 0.2 | 1.5 | 1.04 ± 0.22 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.7 | 1.05 ± 0.22 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.3 | 3.3 | 1.91 ± 0.40 |
| lanjian | input-aspidites | 2.0 ± 0.3 | 1.5 | 3.3 | 1.94 ± 0.39 |
| lanjian | input-mattcl | 2.0 ± 0.3 | 1.4 | 3.3 | 1.95 ± 0.40 |
| lanjian | input-chancalan | 2.0 ± 0.3 | 1.5 | 3.3 | 1.96 ± 0.40 |
| lanjian | input-pting | 2.0 ± 0.3 | 1.4 | 3.7 | 1.97 ± 0.40 |
| lanjian | input-kcen | 2.0 ± 0.3 | 1.4 | 3.2 | 1.98 ± 0.42 |
| aspidites | input-kcen | 13.1 ± 0.4 | 12.0 | 14.3 | 12.96 ± 2.04 |
| aspidites | input-mattcl | 13.1 ± 0.4 | 12.3 | 14.3 | 12.98 ± 2.05 |
| aspidites | input-lanjian | 13.1 ± 0.4 | 12.2 | 14.1 | 13.00 ± 2.04 |
| aspidites | input-aspidites | 13.1 ± 0.5 | 12.1 | 14.5 | 13.02 ± 2.06 |
| aspidites | input-chancalan | 13.2 ± 0.5 | 12.0 | 14.5 | 13.06 ± 2.06 |
| aspidites | input-pting | 13.2 ± 0.5 | 12.1 | 14.6 | 13.08 ± 2.07 |
| pting | input-aspidites | 18.1 ± 0.8 | 17.0 | 21.5 | 17.95 ± 2.88 |
| pting | input-mattcl | 18.1 ± 0.7 | 17.3 | 22.1 | 17.96 ± 2.85 |
| pting | input-lanjian | 18.1 ± 0.8 | 17.2 | 21.4 | 17.97 ± 2.89 |
| pting | input-kcen | 18.2 ± 0.7 | 17.3 | 21.3 | 17.99 ± 2.85 |
| pting | input-chancalan | 18.2 ± 0.7 | 17.2 | 21.2 | 18.04 ± 2.87 |
| pting | input-pting | 18.2 ± 0.8 | 17.1 | 21.3 | 18.05 ± 2.89 |
| mattcl-py | input-aspidites | 18.6 ± 0.6 | 17.3 | 21.5 | 18.40 ± 2.90 |
| chancalan | input-mattcl | 18.6 ± 0.6 | 17.7 | 21.6 | 18.40 ± 2.89 |
| chancalan | input-aspidites | 18.6 ± 0.7 | 17.5 | 21.6 | 18.44 ± 2.93 |
| mattcl-py | input-lanjian | 18.6 ± 0.6 | 17.8 | 21.8 | 18.45 ± 2.91 |
| chancalan | input-chancalan | 18.6 ± 0.7 | 17.6 | 21.9 | 18.47 ± 2.94 |
| chancalan | input-lanjian | 18.7 ± 0.8 | 17.5 | 21.9 | 18.49 ± 2.95 |
| mattcl-py | input-kcen | 18.7 ± 0.7 | 17.6 | 22.1 | 18.51 ± 2.93 |
| mattcl-py | input-mattcl | 18.7 ± 0.8 | 17.8 | 21.8 | 18.53 ± 2.96 |
| chancalan | input-pting | 18.7 ± 0.7 | 17.7 | 21.4 | 18.56 ± 2.93 |
| kcen | input-aspidites | 18.8 ± 0.5 | 17.9 | 21.5 | 18.58 ± 2.91 |
| mattcl-py | input-pting | 18.8 ± 0.7 | 17.7 | 21.6 | 18.58 ± 2.94 |
| mattcl-py | input-chancalan | 18.8 ± 0.9 | 17.6 | 22.0 | 18.58 ± 3.00 |
| kcen | input-lanjian | 19.0 ± 0.6 | 17.6 | 22.1 | 18.77 ± 2.96 |
| kcen | input-kcen | 19.0 ± 0.7 | 17.9 | 22.3 | 18.79 ± 2.98 |
| chancalan | input-kcen | 19.0 ± 3.2 | 17.2 | 46.1 | 18.82 ± 4.27 |
| kcen | input-mattcl | 19.0 ± 0.8 | 18.0 | 21.9 | 18.83 ± 3.00 |
| kcen | input-pting | 19.0 ± 0.8 | 17.8 | 22.3 | 18.84 ± 3.00 |
| kcen | input-chancalan | 19.1 ± 0.8 | 17.9 | 21.9 | 18.88 ± 3.01 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-aspidites|<pre>56042</pre>|<pre>55358</pre>|
|input-chancalan|<pre>56465</pre>|<pre>55902</pre>|
|input-kcen|<pre>54331</pre>|<pre>54518</pre>|
|input-lanjian|<pre>54390</pre>|<pre>54277</pre>|
|input-mattcl|<pre>54159</pre>|<pre>53866</pre>|
|input-pting|<pre>55123</pre>|<pre>55260</pre>|