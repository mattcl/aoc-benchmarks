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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.6 | 1.00 |
| lanjian | input-mikofo | 0.8 ± 0.2 | 0.1 | 1.5 | 1.01 ± 0.35 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.33 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.03 ± 0.33 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.32 |
| lanjian | input-chancalan | 0.9 ± 0.1 | 0.5 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.0 | 1.05 ± 0.33 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.5 | 1.1 | 1.08 ± 0.30 |
| mattcl | input-chancalan | 0.9 ± 0.1 | 0.5 | 1.4 | 1.09 ± 0.31 |
| mattcl-ts | input-chancalan | 9.5 ± 0.4 | 8.4 | 10.5 | 11.49 ± 2.96 |
| mattcl-ts | input-mikofo | 9.6 ± 0.4 | 8.6 | 10.3 | 11.51 ± 2.97 |
| mattcl-ts | input-lanjian | 9.6 ± 0.4 | 8.5 | 10.5 | 11.51 ± 2.97 |
| mattcl-ts | input-kcen | 9.6 ± 0.3 | 8.7 | 10.7 | 11.52 ± 2.97 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.5 | 10.4 | 11.55 ± 2.98 |
| chancalan | input-mattcl | 13.9 ± 0.4 | 13.0 | 16.5 | 16.75 ± 4.29 |
| chancalan | input-mikofo | 13.9 ± 0.5 | 13.0 | 17.4 | 16.75 ± 4.32 |
| pting | input-mikofo | 13.9 ± 0.4 | 13.0 | 17.0 | 16.75 ± 4.30 |
| pting | input-chancalan | 13.9 ± 0.4 | 12.9 | 16.4 | 16.75 ± 4.30 |
| mattcl-py | input-mattcl | 13.9 ± 0.4 | 12.9 | 16.4 | 16.76 ± 4.30 |
| kcen | input-chancalan | 13.9 ± 0.5 | 12.9 | 17.0 | 16.78 ± 4.32 |
| pting | input-kcen | 14.0 ± 0.6 | 13.3 | 17.7 | 16.79 ± 4.34 |
| chancalan | input-lanjian | 14.0 ± 0.6 | 13.1 | 17.0 | 16.79 ± 4.33 |
| mattcl-py | input-lanjian | 14.0 ± 0.5 | 13.1 | 16.9 | 16.80 ± 4.32 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.0 | 16.8 | 16.80 ± 4.33 |
| kcen | input-lanjian | 14.0 ± 0.6 | 12.9 | 17.4 | 16.82 ± 4.34 |
| mattcl-py | input-kcen | 14.0 ± 0.6 | 13.0 | 16.9 | 16.83 ± 4.35 |
| kcen | input-kcen | 14.0 ± 0.5 | 12.9 | 16.9 | 16.83 ± 4.33 |
| mattcl-py | input-mikofo | 14.0 ± 0.6 | 13.3 | 17.0 | 16.83 ± 4.35 |
| kcen | input-mikofo | 14.0 ± 0.6 | 13.0 | 17.2 | 16.84 ± 4.36 |
| kcen | input-mattcl | 14.0 ± 0.6 | 13.2 | 17.7 | 16.85 ± 4.36 |
| chancalan | input-kcen | 14.0 ± 0.8 | 13.2 | 17.8 | 16.86 ± 4.39 |
| pting | input-mattcl | 14.0 ± 0.7 | 13.0 | 17.6 | 16.87 ± 4.38 |
| chancalan | input-chancalan | 14.0 ± 0.7 | 13.0 | 16.9 | 16.87 ± 4.39 |
| mattcl-py | input-chancalan | 14.0 ± 0.6 | 12.9 | 17.2 | 16.88 ± 4.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|