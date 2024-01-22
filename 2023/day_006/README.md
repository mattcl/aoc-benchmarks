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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.4 | 1.00 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.34 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.1 | 1.03 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.04 ± 0.31 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.07 ± 0.33 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.07 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.3 | 1.08 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.2 | 1.4 | 1.08 ± 0.32 |
| mattcl-ts | input-lanjian | 9.5 ± 0.4 | 8.4 | 10.7 | 11.24 ± 2.79 |
| mattcl-ts | input-chancalan | 9.6 ± 0.4 | 8.6 | 10.8 | 11.33 ± 2.81 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.3 | 10.6 | 11.33 ± 2.81 |
| mattcl-ts | input-mikofo | 9.6 ± 0.4 | 8.4 | 10.5 | 11.34 ± 2.81 |
| mattcl-ts | input-kcen | 9.6 ± 0.4 | 8.7 | 11.2 | 11.36 ± 2.82 |
| chancalan | input-mikofo | 14.1 ± 0.5 | 12.9 | 17.2 | 16.64 ± 4.11 |
| chancalan | input-kcen | 14.1 ± 0.5 | 13.2 | 16.8 | 16.65 ± 4.11 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.0 | 17.3 | 16.65 ± 4.13 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.2 | 16.72 ± 4.14 |
| pting | input-chancalan | 14.1 ± 0.5 | 13.0 | 17.4 | 16.72 ± 4.14 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.2 | 18.2 | 16.73 ± 4.16 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.2 | 17.4 | 16.73 ± 4.17 |
| pting | input-mikofo | 14.2 ± 0.6 | 13.1 | 17.3 | 16.73 ± 4.14 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.5 | 17.3 | 16.75 ± 4.16 |
| chancalan | input-lanjian | 14.2 ± 0.5 | 13.3 | 17.0 | 16.77 ± 4.15 |
| kcen | input-mikofo | 14.2 ± 0.6 | 13.2 | 17.6 | 16.77 ± 4.17 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.0 | 17.1 | 16.78 ± 4.16 |
| kcen | input-chancalan | 14.2 ± 0.6 | 13.0 | 18.2 | 16.78 ± 4.17 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.7 | 16.79 ± 4.17 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.8 | 16.79 ± 4.16 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.6 | 16.80 ± 4.18 |
| mattcl-py | input-kcen | 14.2 ± 0.8 | 13.0 | 17.4 | 16.80 ± 4.21 |
| kcen | input-mattcl | 14.2 ± 0.7 | 13.2 | 17.6 | 16.81 ± 4.19 |
| mattcl-py | input-mikofo | 14.2 ± 0.8 | 12.9 | 17.2 | 16.84 ± 4.22 |
| pting | input-kcen | 14.3 ± 0.7 | 13.4 | 17.6 | 16.85 ± 4.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|