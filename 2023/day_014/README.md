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
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.8 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.4 | 2.3 | 5.7 | 1.02 ± 0.16 |
| mattcl | input-kcen | 3.9 ± 5.1 | 2.5 | 62.9 | 1.27 ± 1.66 |
| mattcl | input-mattcl | 4.1 ± 0.5 | 3.2 | 6.7 | 1.32 ± 0.21 |
| lanjian | input-pting | 18.5 ± 1.0 | 17.3 | 21.8 | 6.05 ± 0.68 |
| lanjian | input-lanjian | 19.4 ± 0.8 | 18.2 | 22.5 | 6.34 ± 0.67 |
| lanjian | input-kcen | 22.5 ± 4.7 | 20.7 | 63.7 | 7.34 ± 1.71 |
| lanjian | input-mattcl | 23.8 ± 0.9 | 22.8 | 27.3 | 7.78 ± 0.82 |
| mattcl-py | input-pting | 157.6 ± 6.5 | 152.6 | 181.3 | 51.43 ± 5.50 |
| mattcl-py | input-lanjian | 169.7 ± 2.0 | 166.7 | 174.4 | 55.37 ± 5.50 |
| pting | input-pting | 176.2 ± 3.6 | 170.4 | 182.8 | 57.52 ± 5.79 |
| pting | input-lanjian | 193.0 ± 7.5 | 187.5 | 217.8 | 63.00 ± 6.68 |
| mattcl-py | input-kcen | 195.7 ± 2.0 | 192.2 | 199.2 | 63.88 ± 6.33 |
| mattcl-py | input-mattcl | 204.6 ± 2.4 | 200.4 | 207.5 | 66.79 ± 6.63 |
| pting | input-kcen | 223.5 ± 4.5 | 216.7 | 233.3 | 72.96 ± 7.34 |
| pting | input-mattcl | 236.9 ± 3.7 | 231.5 | 243.9 | 77.30 ± 7.71 |
| kcen | input-pting | 596.4 ± 7.5 | 588.8 | 606.2 | 194.65 ± 19.34 |
| kcen | input-lanjian | 664.2 ± 6.3 | 658.2 | 669.8 | 216.78 ± 21.46 |
| kcen | input-kcen | 762.9 ± 8.7 | 755.4 | 772.4 | 248.98 ± 24.70 |
| kcen | input-mattcl | 846.4 ± 6.7 | 839.1 | 852.1 | 276.24 ± 27.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|