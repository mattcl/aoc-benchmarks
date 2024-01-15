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
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.6 | 1.03 ± 0.36 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.03 ± 0.35 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.36 |
| mattcl | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.38 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.1 | 1.07 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.3 | 1.3 | 1.09 ± 0.35 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.0 | 1.09 ± 0.35 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.10 ± 0.37 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.2 | 1.10 ± 0.35 |
| mattcl-ts | input-lanjian | 9.3 ± 0.4 | 8.5 | 10.6 | 12.06 ± 3.19 |
| mattcl-ts | input-kcen | 9.3 ± 0.4 | 8.2 | 11.0 | 12.08 ± 3.19 |
| mattcl-ts | input-chancalan | 9.3 ± 0.3 | 8.2 | 10.4 | 12.14 ± 3.20 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.3 | 10.7 | 12.16 ± 3.22 |
| mattcl-ts | input-mikofo | 9.4 ± 0.4 | 8.5 | 10.4 | 12.19 ± 3.22 |
| chancalan | input-lanjian | 13.9 ± 0.5 | 12.7 | 16.4 | 18.07 ± 4.76 |
| pting | input-kcen | 13.9 ± 0.5 | 13.0 | 16.7 | 18.08 ± 4.77 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 12.9 | 16.9 | 18.09 ± 4.78 |
| kcen | input-mattcl | 13.9 ± 0.6 | 12.9 | 17.5 | 18.10 ± 4.79 |
| pting | input-mattcl | 13.9 ± 0.5 | 12.8 | 17.0 | 18.10 ± 4.78 |
| kcen | input-kcen | 13.9 ± 0.5 | 13.0 | 17.0 | 18.10 ± 4.78 |
| chancalan | input-kcen | 14.0 ± 0.6 | 12.8 | 17.2 | 18.12 ± 4.81 |
| chancalan | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.2 | 18.13 ± 4.80 |
| pting | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.6 | 18.13 ± 4.80 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 13.0 | 17.2 | 18.13 ± 4.82 |
| mattcl-py | input-mikofo | 14.0 ± 0.6 | 13.0 | 17.1 | 18.14 ± 4.80 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.1 | 18.15 ± 4.80 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 12.8 | 17.1 | 18.18 ± 4.82 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.2 | 18.18 ± 4.82 |
| kcen | input-mikofo | 14.0 ± 0.7 | 12.8 | 17.5 | 18.18 ± 4.83 |
| pting | input-mikofo | 14.0 ± 0.6 | 13.0 | 17.2 | 18.19 ± 4.81 |
| kcen | input-lanjian | 14.0 ± 0.7 | 12.9 | 17.2 | 18.20 ± 4.83 |
| chancalan | input-mikofo | 14.0 ± 0.8 | 12.7 | 17.3 | 18.20 ± 4.86 |
| mattcl-py | input-mattcl | 14.0 ± 0.7 | 12.9 | 17.4 | 18.23 ± 4.86 |
| kcen | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.3 | 18.23 ± 4.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|