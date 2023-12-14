# Day 14 benchmarks

[link to problem](https://adventofcode.com/2023/day/14)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 14)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 5.5 ± 0.4 | 4.7 | 7.9 | 1.00 |
| mattcl | input-pting | 5.6 ± 3.9 | 4.5 | 60.4 | 1.02 ± 0.71 |
| mattcl | input-kcen | 6.0 ± 0.5 | 5.1 | 8.4 | 1.09 ± 0.11 |
| mattcl | input-mattcl | 6.3 ± 0.5 | 5.6 | 9.2 | 1.14 ± 0.12 |
| lanjian | input-pting | 18.7 ± 0.8 | 17.6 | 22.3 | 3.39 ± 0.27 |
| lanjian | input-lanjian | 19.7 ± 0.9 | 18.3 | 23.4 | 3.57 ± 0.29 |
| lanjian | input-kcen | 22.0 ± 0.8 | 20.6 | 25.1 | 3.99 ± 0.30 |
| lanjian | input-mattcl | 24.0 ± 0.8 | 22.9 | 28.3 | 4.36 ± 0.33 |
| pting | input-pting | 209.3 ± 3.4 | 204.8 | 215.3 | 37.97 ± 2.62 |
| pting | input-lanjian | 228.9 ± 3.2 | 223.2 | 233.5 | 41.52 ± 2.84 |
| mattcl-py | input-pting | 229.8 ± 2.6 | 226.4 | 233.3 | 41.68 ± 2.83 |
| mattcl-py | input-lanjian | 246.1 ± 2.6 | 241.3 | 249.5 | 44.65 ± 3.03 |
| pting | input-kcen | 265.6 ± 5.8 | 255.2 | 276.0 | 48.18 ± 3.39 |
| mattcl-py | input-kcen | 284.1 ± 3.2 | 279.7 | 289.9 | 51.54 ± 3.50 |
| pting | input-mattcl | 292.1 ± 12.9 | 282.1 | 327.8 | 52.98 ± 4.25 |
| mattcl-py | input-mattcl | 302.0 ± 4.3 | 296.3 | 309.6 | 54.78 ± 3.75 |
| kcen | input-pting | 578.3 ± 7.9 | 565.8 | 586.7 | 104.90 ± 7.16 |
| kcen | input-lanjian | 633.8 ± 3.5 | 629.0 | 636.7 | 114.97 ± 7.72 |
| kcen | input-kcen | 738.1 ± 19.1 | 720.5 | 762.3 | 133.90 ± 9.61 |
| kcen | input-mattcl | 807.8 ± 7.6 | 799.6 | 814.5 | 146.53 ± 9.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|