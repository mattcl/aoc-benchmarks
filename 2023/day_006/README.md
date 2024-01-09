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
| lanjian | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.4 | 1.00 |
| lanjian | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.3 | 1.1 | 1.03 ± 0.29 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.3 | 1.3 | 1.05 ± 0.30 |
| lanjian | input-lanjian | 0.9 ± 0.1 | 0.2 | 1.3 | 1.07 ± 0.29 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.7 | 1.08 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.1 | 1.09 ± 0.30 |
| mattcl | input-mikofo | 1.0 ± 0.2 | 0.3 | 1.3 | 1.09 ± 0.31 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.3 | 1.9 | 1.12 ± 0.33 |
| mattcl-ts | input-mikofo | 10.1 ± 0.3 | 9.1 | 11.4 | 11.53 ± 2.70 |
| mattcl-ts | input-mattcl | 10.1 ± 0.3 | 9.1 | 11.2 | 11.54 ± 2.71 |
| mattcl-ts | input-chancalan | 10.2 ± 0.3 | 9.1 | 11.3 | 11.58 ± 2.72 |
| mattcl-ts | input-lanjian | 10.2 ± 0.3 | 9.4 | 11.1 | 11.61 ± 2.72 |
| mattcl-ts | input-kcen | 10.3 ± 3.1 | 9.2 | 54.0 | 11.77 ± 4.49 |
| chancalan | input-mikofo | 14.1 ± 0.6 | 13.3 | 17.3 | 16.12 ± 3.81 |
| chancalan | input-lanjian | 14.2 ± 0.6 | 13.2 | 17.5 | 16.16 ± 3.82 |
| chancalan | input-chancalan | 14.2 ± 0.7 | 13.1 | 18.0 | 16.16 ± 3.84 |
| chancalan | input-kcen | 14.2 ± 0.6 | 12.8 | 17.8 | 16.18 ± 3.82 |
| pting | input-mikofo | 14.2 ± 0.6 | 13.1 | 17.7 | 16.18 ± 3.82 |
| mattcl-py | input-mattcl | 14.2 ± 0.6 | 13.0 | 16.7 | 16.19 ± 3.82 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.4 | 18.2 | 16.19 ± 3.83 |
| kcen | input-mikofo | 14.2 ± 0.5 | 13.4 | 17.9 | 16.21 ± 3.82 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.4 | 16.22 ± 3.84 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.5 | 17.1 | 16.22 ± 3.84 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.3 | 16.9 | 16.23 ± 3.83 |
| mattcl-py | input-mikofo | 14.2 ± 0.6 | 13.1 | 17.5 | 16.23 ± 3.83 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.4 | 17.9 | 16.24 ± 3.84 |
| pting | input-chancalan | 14.3 ± 0.7 | 13.4 | 18.0 | 16.24 ± 3.87 |
| pting | input-lanjian | 14.3 ± 0.6 | 13.2 | 17.6 | 16.25 ± 3.85 |
| pting | input-kcen | 14.3 ± 0.6 | 13.0 | 17.4 | 16.27 ± 3.85 |
| chancalan | input-mattcl | 14.3 ± 0.7 | 13.0 | 17.5 | 16.28 ± 3.88 |
| kcen | input-lanjian | 14.3 ± 0.7 | 13.0 | 18.1 | 16.33 ± 3.88 |
| kcen | input-chancalan | 14.5 ± 2.1 | 13.3 | 43.5 | 16.53 ± 4.55 |
| mattcl-py | input-kcen | 14.5 ± 3.5 | 13.1 | 63.0 | 16.55 ± 5.55 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|