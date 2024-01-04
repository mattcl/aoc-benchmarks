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
| mattcl | input-pting | 3.1 ± 0.3 | 2.2 | 5.8 | 1.00 |
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.4 | 6.0 | 1.02 ± 0.16 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.8 | 4.8 | 1.13 ± 0.16 |
| mattcl | input-mattcl | 4.0 ± 0.4 | 3.1 | 6.6 | 1.29 ± 0.19 |
| lanjian | input-pting | 18.3 ± 0.8 | 17.3 | 21.5 | 5.90 ± 0.64 |
| lanjian | input-lanjian | 19.3 ± 0.8 | 18.3 | 22.4 | 6.22 ± 0.68 |
| lanjian | input-kcen | 21.9 ± 0.8 | 20.8 | 25.1 | 7.05 ± 0.76 |
| lanjian | input-mattcl | 23.7 ± 0.8 | 22.6 | 26.8 | 7.62 ± 0.81 |
| mattcl-py | input-pting | 155.9 ± 1.4 | 153.7 | 159.4 | 50.18 ± 5.08 |
| mattcl-py | input-lanjian | 169.1 ± 2.9 | 165.1 | 177.5 | 54.43 ± 5.57 |
| pting | input-pting | 176.9 ± 2.2 | 172.8 | 180.0 | 56.95 ± 5.79 |
| pting | input-lanjian | 193.7 ± 3.6 | 187.8 | 200.2 | 62.34 ± 6.39 |
| mattcl-py | input-kcen | 195.4 ± 2.6 | 192.5 | 202.0 | 62.91 ± 6.40 |
| mattcl-py | input-mattcl | 205.0 ± 3.2 | 200.3 | 214.1 | 66.00 ± 6.74 |
| pting | input-kcen | 223.7 ± 3.7 | 217.6 | 229.3 | 72.01 ± 7.36 |
| pting | input-mattcl | 242.3 ± 9.5 | 229.6 | 269.2 | 78.01 ± 8.44 |
| kcen | input-pting | 572.3 ± 9.3 | 556.9 | 581.4 | 184.24 ± 18.83 |
| kcen | input-lanjian | 631.9 ± 9.8 | 618.6 | 642.0 | 203.42 ± 20.77 |
| kcen | input-kcen | 740.1 ± 11.7 | 722.6 | 747.0 | 238.27 ± 24.33 |
| kcen | input-mattcl | 799.4 ± 6.4 | 792.9 | 805.7 | 257.33 ± 26.04 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|