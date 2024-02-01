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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-chancalan | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.35 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.0 | 1.5 | 1.01 ± 0.36 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.36 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.6 | 1.03 ± 0.35 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.6 | 1.03 ± 0.34 |
| mattcl | input-chancalan | 0.8 ± 0.2 | 0.2 | 1.3 | 1.04 ± 0.35 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.04 ± 0.38 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.2 | 1.0 | 1.06 ± 0.33 |
| mattcl | input-mikofo | 0.8 ± 0.1 | 0.3 | 1.0 | 1.07 ± 0.33 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.3 | 10.6 | 12.70 ± 3.42 |
| mattcl-ts | input-chancalan | 9.7 ± 0.4 | 8.8 | 10.5 | 12.77 ± 3.43 |
| mattcl-ts | input-mikofo | 9.7 ± 0.4 | 8.6 | 11.1 | 12.77 ± 3.44 |
| mattcl-ts | input-kcen | 9.7 ± 0.4 | 8.7 | 10.6 | 12.82 ± 3.44 |
| mattcl-ts | input-lanjian | 9.7 ± 0.4 | 8.5 | 11.0 | 12.83 ± 3.46 |
| chancalan | input-mattcl | 13.9 ± 0.5 | 13.0 | 16.5 | 18.32 ± 4.91 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.0 | 16.7 | 18.37 ± 4.93 |
| pting | input-kcen | 14.0 ± 0.5 | 13.3 | 16.7 | 18.38 ± 4.92 |
| mattcl-py | input-mikofo | 14.0 ± 0.5 | 13.1 | 16.6 | 18.39 ± 4.93 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 12.8 | 17.1 | 18.42 ± 4.95 |
| pting | input-chancalan | 14.0 ± 0.6 | 13.1 | 17.5 | 18.42 ± 4.96 |
| chancalan | input-mikofo | 14.0 ± 0.6 | 13.1 | 17.3 | 18.42 ± 4.97 |
| kcen | input-lanjian | 14.0 ± 0.5 | 12.9 | 16.3 | 18.44 ± 4.94 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 12.8 | 17.8 | 18.46 ± 4.99 |
| mattcl-py | input-lanjian | 14.0 ± 0.7 | 12.8 | 17.1 | 18.50 ± 5.00 |
| mattcl-py | input-chancalan | 14.1 ± 0.6 | 13.0 | 17.4 | 18.51 ± 4.98 |
| kcen | input-mikofo | 14.1 ± 0.6 | 13.0 | 17.1 | 18.51 ± 4.98 |
| chancalan | input-kcen | 14.1 ± 0.7 | 13.2 | 17.1 | 18.51 ± 5.01 |
| kcen | input-chancalan | 14.1 ± 0.6 | 12.8 | 17.0 | 18.51 ± 4.99 |
| kcen | input-mattcl | 14.1 ± 0.7 | 12.8 | 18.1 | 18.52 ± 5.00 |
| mattcl-py | input-mattcl | 14.1 ± 0.7 | 13.2 | 17.2 | 18.52 ± 5.01 |
| kcen | input-kcen | 14.1 ± 0.7 | 12.8 | 17.6 | 18.54 ± 5.02 |
| pting | input-mattcl | 14.1 ± 0.8 | 12.9 | 17.4 | 18.56 ± 5.03 |
| pting | input-lanjian | 14.1 ± 0.7 | 13.0 | 17.5 | 18.61 ± 5.03 |
| pting | input-mikofo | 14.1 ± 0.6 | 13.1 | 18.1 | 18.61 ± 5.02 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|