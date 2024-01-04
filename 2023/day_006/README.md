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
| lanjian | input-kcen | 0.6 ± 0.3 | 0.0 | 1.0 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.18 ± 0.55 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.21 ± 0.59 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.23 ± 0.56 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.3 | 1.23 ± 0.56 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.3 | 1.26 ± 0.58 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.27 ± 0.58 |
| lanjian | input-mikofo | 0.8 ± 0.1 | 0.2 | 1.4 | 1.28 ± 0.55 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.0 | 1.30 ± 0.57 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.30 ± 0.59 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 9.1 | 11.0 | 15.67 ± 6.27 |
| mattcl-ts | input-chancalan | 10.0 ± 0.4 | 9.1 | 11.8 | 15.71 ± 6.29 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.0 | 11.2 | 15.74 ± 6.29 |
| mattcl-ts | input-kcen | 10.2 ± 2.1 | 8.8 | 39.2 | 15.87 ± 7.13 |
| mattcl-ts | input-lanjian | 10.7 ± 7.4 | 8.6 | 108.6 | 16.73 ± 13.32 |
| kcen | input-chancalan | 14.1 ± 0.5 | 13.2 | 17.2 | 21.98 ± 8.80 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.2 | 17.1 | 21.99 ± 8.82 |
| pting | input-mattcl | 14.1 ± 0.5 | 13.1 | 17.5 | 22.04 ± 8.83 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.1 | 18.2 | 22.08 ± 8.85 |
| chancalan | input-chancalan | 14.1 ± 0.6 | 13.1 | 16.9 | 22.09 ± 8.86 |
| chancalan | input-lanjian | 14.1 ± 0.6 | 12.8 | 18.3 | 22.10 ± 8.86 |
| chancalan | input-mikofo | 14.1 ± 0.6 | 12.9 | 18.0 | 22.11 ± 8.86 |
| chancalan | input-kcen | 14.2 ± 0.6 | 13.3 | 17.2 | 22.13 ± 8.88 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.2 | 22.15 ± 8.88 |
| mattcl-py | input-mikofo | 14.2 ± 0.7 | 13.0 | 17.7 | 22.17 ± 8.91 |
| pting | input-kcen | 14.2 ± 0.5 | 13.3 | 16.9 | 22.18 ± 8.88 |
| kcen | input-mattcl | 14.2 ± 0.7 | 13.2 | 17.8 | 22.22 ± 8.93 |
| kcen | input-mikofo | 14.2 ± 0.7 | 13.3 | 17.7 | 22.24 ± 8.94 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.5 | 17.1 | 22.25 ± 8.93 |
| pting | input-chancalan | 14.2 ± 0.7 | 13.0 | 17.7 | 22.26 ± 8.95 |
| pting | input-mikofo | 14.3 ± 0.8 | 13.3 | 17.9 | 22.29 ± 8.97 |
| kcen | input-lanjian | 14.3 ± 0.6 | 13.0 | 17.1 | 22.30 ± 8.95 |
| kcen | input-kcen | 14.4 ± 2.4 | 13.1 | 46.7 | 22.50 ± 9.70 |
| mattcl-py | input-kcen | 14.5 ± 3.5 | 13.0 | 52.5 | 22.68 ± 10.57 |
| mattcl-py | input-chancalan | 14.8 ± 3.6 | 12.7 | 50.5 | 23.07 ± 10.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|