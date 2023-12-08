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
| lanjian | input-lanjian | 0.6 ± 0.2 | 0.0 | 0.9 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.37 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.0 | 1.03 ± 0.40 |
| lanjian | input-pting | 0.7 ± 0.1 | 0.1 | 0.9 | 1.03 ± 0.36 |
| lanjian | input-mattcl | 0.7 ± 0.1 | 0.2 | 0.8 | 1.06 ± 0.34 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 0.9 | 1.07 ± 0.38 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 0.9 | 1.07 ± 0.40 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.0 | 0.9 | 1.09 ± 0.37 |
| mattcl-ts | input-pting | 9.4 ± 0.4 | 8.6 | 10.7 | 14.66 ± 4.03 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.4 | 10.5 | 14.69 ± 4.04 |
| mattcl-ts | input-kcen | 9.4 ± 0.4 | 8.5 | 10.8 | 14.77 ± 4.06 |
| mattcl-ts | input-lanjian | 10.3 ± 4.6 | 8.5 | 46.3 | 16.05 ± 8.40 |
| mattcl-py | input-kcen | 13.9 ± 0.4 | 12.7 | 15.6 | 21.69 ± 5.93 |
| pting | input-kcen | 13.9 ± 0.5 | 12.7 | 17.2 | 21.76 ± 5.98 |
| kcen | input-pting | 14.0 ± 0.5 | 13.0 | 17.8 | 21.83 ± 5.99 |
| pting | input-mattcl | 14.0 ± 0.5 | 13.2 | 17.4 | 21.84 ± 5.98 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 12.7 | 17.5 | 21.87 ± 6.01 |
| pting | input-pting | 14.0 ± 0.5 | 12.7 | 16.8 | 21.89 ± 6.01 |
| kcen | input-kcen | 14.0 ± 0.7 | 13.2 | 17.7 | 21.92 ± 6.06 |
| mattcl-py | input-pting | 14.1 ± 0.7 | 13.0 | 17.5 | 21.97 ± 6.08 |
| kcen | input-lanjian | 14.1 ± 0.7 | 13.2 | 17.2 | 21.99 ± 6.08 |
| mattcl-py | input-mattcl | 14.1 ± 0.7 | 13.0 | 18.8 | 22.02 ± 6.08 |
| pting | input-lanjian | 14.2 ± 2.1 | 13.0 | 43.1 | 22.13 ± 6.87 |
| kcen | input-mattcl | 14.2 ± 2.3 | 13.0 | 45.8 | 22.19 ± 7.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|