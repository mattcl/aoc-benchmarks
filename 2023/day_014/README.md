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
| mattcl | input-pting | 3.1 ± 0.3 | 2.3 | 3.9 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.3 | 2.4 | 5.0 | 1.02 ± 0.12 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.6 | 5.8 | 1.12 ± 0.16 |
| mattcl | input-mattcl | 4.1 ± 0.5 | 3.2 | 6.9 | 1.32 ± 0.19 |
| lanjian | input-pting | 18.7 ± 0.9 | 17.5 | 21.5 | 6.02 ± 0.61 |
| lanjian | input-lanjian | 19.5 ± 0.8 | 18.4 | 22.8 | 6.26 ± 0.60 |
| lanjian | input-kcen | 21.9 ± 0.9 | 20.7 | 25.2 | 7.05 ± 0.68 |
| lanjian | input-mattcl | 23.9 ± 0.8 | 22.7 | 27.0 | 7.68 ± 0.72 |
| mattcl-py | input-pting | 155.1 ± 2.2 | 151.3 | 158.2 | 49.88 ± 4.43 |
| mattcl-py | input-lanjian | 170.5 ± 5.8 | 167.2 | 192.2 | 54.85 ± 5.16 |
| pting | input-pting | 175.2 ± 2.5 | 171.0 | 180.9 | 56.37 ± 5.00 |
| pting | input-lanjian | 194.0 ± 4.0 | 187.0 | 200.5 | 62.42 ± 5.62 |
| mattcl-py | input-kcen | 197.2 ± 3.4 | 191.1 | 202.6 | 63.44 ± 5.67 |
| mattcl-py | input-mattcl | 206.6 ± 4.4 | 202.2 | 219.6 | 66.45 ± 5.99 |
| pting | input-kcen | 226.6 ± 3.2 | 220.4 | 230.7 | 72.90 ± 6.48 |
| pting | input-mattcl | 239.6 ± 2.0 | 236.5 | 243.6 | 77.09 ± 6.79 |
| kcen | input-pting | 578.7 ± 12.2 | 561.0 | 592.5 | 186.16 ± 16.78 |
| kcen | input-lanjian | 630.2 ± 1.8 | 628.0 | 632.2 | 202.74 ± 17.78 |
| kcen | input-kcen | 737.0 ± 10.0 | 724.7 | 746.4 | 237.10 ± 21.03 |
| kcen | input-mattcl | 810.1 ± 10.9 | 800.9 | 822.2 | 260.63 ± 23.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|