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
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.05 ± 0.33 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.0 | 1.06 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.37 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.36 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.07 ± 0.36 |
| lanjian | input-mikofo | 0.8 ± 0.1 | 0.2 | 1.0 | 1.07 ± 0.33 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.0 | 1.08 ± 0.34 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.1 | 1.10 ± 0.35 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.5 | 1.3 | 1.11 ± 0.33 |
| mattcl-ts | input-mattcl | 9.8 ± 0.4 | 8.8 | 10.8 | 12.66 ± 3.24 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.8 | 10.7 | 12.69 ± 3.25 |
| mattcl-ts | input-chancalan | 9.9 ± 0.3 | 8.8 | 10.6 | 12.72 ± 3.25 |
| mattcl-ts | input-mikofo | 9.9 ± 0.3 | 9.1 | 10.9 | 12.75 ± 3.26 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 8.9 | 10.8 | 12.76 ± 3.27 |
| chancalan | input-chancalan | 13.9 ± 0.4 | 12.9 | 16.9 | 17.81 ± 4.54 |
| chancalan | input-lanjian | 13.9 ± 0.5 | 13.0 | 16.6 | 17.88 ± 4.57 |
| chancalan | input-mikofo | 13.9 ± 0.5 | 12.9 | 16.9 | 17.89 ± 4.57 |
| pting | input-kcen | 13.9 ± 0.4 | 12.9 | 17.1 | 17.90 ± 4.57 |
| chancalan | input-kcen | 13.9 ± 0.6 | 13.2 | 17.1 | 17.92 ± 4.61 |
| mattcl-py | input-mattcl | 14.0 ± 0.5 | 13.0 | 17.3 | 17.94 ± 4.59 |
| mattcl-py | input-lanjian | 14.0 ± 0.5 | 13.2 | 17.3 | 17.94 ± 4.59 |
| mattcl-py | input-kcen | 14.0 ± 0.6 | 13.2 | 17.0 | 17.95 ± 4.60 |
| pting | input-mattcl | 14.0 ± 0.5 | 12.9 | 16.7 | 17.95 ± 4.60 |
| chancalan | input-mattcl | 14.0 ± 0.5 | 13.1 | 16.6 | 17.96 ± 4.60 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.0 | 17.1 | 17.96 ± 4.59 |
| kcen | input-lanjian | 14.0 ± 0.6 | 12.9 | 16.8 | 17.97 ± 4.61 |
| kcen | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.2 | 17.97 ± 4.61 |
| kcen | input-mattcl | 14.0 ± 0.5 | 13.0 | 17.1 | 17.97 ± 4.60 |
| kcen | input-mikofo | 14.0 ± 0.6 | 13.2 | 16.9 | 17.98 ± 4.62 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 13.0 | 17.3 | 17.98 ± 4.63 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.1 | 17.0 | 17.98 ± 4.63 |
| pting | input-chancalan | 14.0 ± 0.7 | 13.0 | 17.5 | 18.05 ± 4.67 |
| mattcl-py | input-mikofo | 14.2 ± 2.4 | 13.2 | 46.4 | 18.22 ± 5.53 |
| pting | input-mikofo | 14.3 ± 3.9 | 12.9 | 63.6 | 18.42 ± 6.88 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|