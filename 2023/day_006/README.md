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

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.33 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.35 |
| lanjian | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.02 ± 0.31 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.03 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.4 | 1.03 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.07 ± 0.31 |
| mattcl-ts | input-pting | 9.2 ± 0.3 | 8.3 | 10.0 | 11.03 ± 2.46 |
| mattcl-ts | input-lanjian | 9.3 ± 0.3 | 8.2 | 10.1 | 11.06 ± 2.47 |
| mattcl-ts | input-mattcl | 9.3 ± 0.4 | 8.3 | 10.3 | 11.10 ± 2.49 |
| mattcl-ts | input-kcen | 9.3 ± 0.3 | 8.5 | 10.4 | 11.14 ± 2.49 |
| mattcl-py | input-mattcl | 14.0 ± 0.4 | 13.1 | 16.8 | 16.74 ± 3.73 |
| kcen | input-kcen | 14.1 ± 0.5 | 13.1 | 16.5 | 16.79 ± 3.75 |
| kcen | input-pting | 14.1 ± 0.5 | 13.1 | 17.1 | 16.79 ± 3.76 |
| pting | input-pting | 14.1 ± 0.5 | 13.1 | 16.6 | 16.80 ± 3.76 |
| pting | input-kcen | 14.1 ± 0.5 | 13.5 | 17.0 | 16.82 ± 3.76 |
| pting | input-mattcl | 14.1 ± 0.6 | 13.2 | 17.4 | 16.83 ± 3.78 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.8 | 16.84 ± 3.79 |
| kcen | input-mattcl | 14.1 ± 0.7 | 13.2 | 17.4 | 16.86 ± 3.80 |
| pting | input-lanjian | 14.2 ± 0.7 | 13.0 | 17.4 | 16.90 ± 3.82 |
| mattcl-py | input-lanjian | 14.3 ± 2.7 | 13.0 | 51.3 | 17.03 ± 4.93 |
| mattcl-py | input-kcen | 14.3 ± 2.8 | 13.1 | 52.3 | 17.07 ± 5.00 |
| mattcl-py | input-pting | 14.3 ± 2.5 | 12.9 | 43.4 | 17.09 ± 4.82 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|