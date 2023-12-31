# Day 6 benchmarks

[link to problem](https://adventofcode.com/2023/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.0 | 1.0 | 1.00 ± 0.37 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.36 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.35 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.37 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.5 | 1.06 ± 0.35 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.38 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.10 ± 0.37 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.2 | 1.0 | 1.12 ± 0.35 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.13 ± 0.36 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.13 ± 0.37 |
| mattcl | input-mikofo | 0.9 ± 0.1 | 0.2 | 1.0 | 1.15 ± 0.35 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.0 | 11.0 | 13.04 ± 3.48 |
| mattcl-ts | input-kcen | 10.0 ± 0.3 | 8.9 | 10.8 | 13.06 ± 3.49 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 8.8 | 11.2 | 13.08 ± 3.49 |
| mattcl-ts | input-pting | 10.1 ± 0.3 | 8.8 | 11.1 | 13.08 ± 3.50 |
| mattcl-ts | input-mikofo | 10.2 ± 2.3 | 9.1 | 42.5 | 13.33 ± 4.64 |
| mattcl-ts | input-chancalan | 10.3 ± 3.3 | 9.0 | 56.6 | 13.39 ± 5.58 |
| pting | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.1 | 18.29 ± 4.90 |
| kcen | input-pting | 14.1 ± 0.5 | 13.1 | 17.3 | 18.29 ± 4.89 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.4 | 17.6 | 18.30 ± 4.91 |
| chancalan | input-kcen | 14.1 ± 0.5 | 13.1 | 17.2 | 18.34 ± 4.91 |
| mattcl-py | input-lanjian | 14.1 ± 0.5 | 12.9 | 16.8 | 18.34 ± 4.91 |
| pting | input-chancalan | 14.1 ± 0.5 | 13.0 | 17.3 | 18.36 ± 4.90 |
| mattcl-py | input-mattcl | 14.1 ± 0.5 | 13.1 | 17.0 | 18.36 ± 4.92 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.1 | 18.37 ± 4.94 |
| chancalan | input-pting | 14.1 ± 0.6 | 13.4 | 17.0 | 18.38 ± 4.93 |
| pting | input-pting | 14.1 ± 0.6 | 13.0 | 17.3 | 18.40 ± 4.95 |
| mattcl-py | input-pting | 14.1 ± 0.7 | 13.1 | 17.4 | 18.41 ± 4.95 |
| pting | input-mattcl | 14.2 ± 0.7 | 13.4 | 18.2 | 18.41 ± 4.96 |
| pting | input-kcen | 14.2 ± 0.5 | 13.0 | 17.2 | 18.41 ± 4.93 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.0 | 16.7 | 18.41 ± 4.94 |
| mattcl-py | input-mikofo | 14.2 ± 0.7 | 13.1 | 17.5 | 18.42 ± 4.96 |
| kcen | input-chancalan | 14.2 ± 0.7 | 13.3 | 17.9 | 18.42 ± 4.96 |
| chancalan | input-mikofo | 14.2 ± 0.7 | 13.1 | 17.3 | 18.44 ± 4.97 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.4 | 18.3 | 18.46 ± 4.95 |
| kcen | input-mikofo | 14.2 ± 0.7 | 13.2 | 17.6 | 18.47 ± 4.98 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.2 | 18.51 ± 4.97 |
| pting | input-mikofo | 14.2 ± 0.7 | 12.9 | 17.3 | 18.51 ± 4.98 |
| mattcl-py | input-chancalan | 14.3 ± 2.1 | 13.1 | 42.2 | 18.55 ± 5.62 |
| kcen | input-kcen | 14.3 ± 0.7 | 13.5 | 17.5 | 18.57 ± 5.01 |
| chancalan | input-chancalan | 14.4 ± 2.2 | 13.1 | 43.6 | 18.71 ± 5.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|