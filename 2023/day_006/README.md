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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.5 | 1.00 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.31 |
| mattcl | input-mikofo | 0.9 ± 0.2 | 0.1 | 1.5 | 1.05 ± 0.34 |
| mattcl | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.4 | 1.07 ± 0.33 |
| lanjian | input-chancalan | 0.9 ± 0.2 | 0.2 | 1.4 | 1.07 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.08 ± 0.32 |
| lanjian | input-mikofo | 0.9 ± 0.1 | 0.3 | 1.1 | 1.09 ± 0.28 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.33 |
| mattcl-ts | input-mikofo | 10.0 ± 0.3 | 9.1 | 10.7 | 11.91 ± 2.83 |
| mattcl-ts | input-mattcl | 10.0 ± 0.4 | 9.0 | 11.0 | 11.91 ± 2.84 |
| mattcl-ts | input-kcen | 10.1 ± 0.4 | 9.0 | 11.2 | 11.97 ± 2.85 |
| mattcl-ts | input-chancalan | 10.1 ± 0.3 | 9.1 | 10.9 | 11.98 ± 2.84 |
| mattcl-ts | input-lanjian | 10.1 ± 0.3 | 9.1 | 11.0 | 12.00 ± 2.85 |
| chancalan | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.0 | 16.68 ± 3.98 |
| pting | input-kcen | 14.1 ± 0.6 | 13.1 | 17.2 | 16.74 ± 3.99 |
| mattcl-py | input-mikofo | 14.1 ± 0.6 | 13.0 | 16.8 | 16.76 ± 4.00 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.3 | 17.5 | 16.78 ± 4.01 |
| chancalan | input-mattcl | 14.1 ± 0.7 | 12.9 | 18.1 | 16.78 ± 4.02 |
| chancalan | input-chancalan | 14.1 ± 0.6 | 13.1 | 17.8 | 16.78 ± 4.02 |
| mattcl-py | input-kcen | 14.1 ± 0.5 | 13.2 | 17.9 | 16.78 ± 4.00 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.1 | 16.8 | 16.78 ± 4.00 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.3 | 17.4 | 16.79 ± 4.01 |
| pting | input-mikofo | 14.1 ± 0.6 | 13.0 | 17.6 | 16.79 ± 4.01 |
| kcen | input-chancalan | 14.2 ± 0.5 | 13.2 | 17.1 | 16.80 ± 4.00 |
| pting | input-chancalan | 14.2 ± 0.6 | 13.2 | 17.4 | 16.81 ± 4.02 |
| chancalan | input-mikofo | 14.2 ± 0.6 | 13.2 | 17.4 | 16.83 ± 4.02 |
| pting | input-lanjian | 14.2 ± 0.7 | 13.2 | 18.1 | 16.84 ± 4.04 |
| mattcl-py | input-chancalan | 14.2 ± 0.6 | 13.3 | 17.5 | 16.86 ± 4.03 |
| pting | input-mattcl | 14.2 ± 0.7 | 13.4 | 17.5 | 16.87 ± 4.04 |
| kcen | input-mattcl | 14.2 ± 1.4 | 13.3 | 33.1 | 16.88 ± 4.32 |
| kcen | input-mikofo | 14.2 ± 0.6 | 13.0 | 17.8 | 16.88 ± 4.04 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.1 | 17.4 | 16.89 ± 4.04 |
| mattcl-py | input-mattcl | 14.4 ± 3.6 | 13.1 | 60.7 | 17.15 ± 5.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-chancalan|<pre>2612736</pre>|<pre>29891250</pre>|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-mikofo|<pre>2065338</pre>|<pre>34934171</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|