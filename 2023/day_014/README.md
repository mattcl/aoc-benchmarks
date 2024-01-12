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
| mattcl | input-lanjian | 3.0 ± 0.2 | 2.2 | 4.9 | 1.00 |
| mattcl | input-pting | 3.0 ± 0.2 | 2.6 | 3.9 | 1.00 ± 0.11 |
| mattcl | input-kcen | 3.3 ± 0.4 | 2.6 | 6.0 | 1.10 ± 0.15 |
| mattcl | input-mattcl | 3.8 ± 0.5 | 3.3 | 7.5 | 1.28 ± 0.20 |
| lanjian | input-pting | 18.7 ± 0.9 | 17.6 | 21.9 | 6.27 ± 0.59 |
| lanjian | input-lanjian | 19.4 ± 0.7 | 18.2 | 22.3 | 6.49 ± 0.59 |
| lanjian | input-kcen | 22.3 ± 3.8 | 20.9 | 61.2 | 7.47 ± 1.41 |
| lanjian | input-mattcl | 24.1 ± 0.9 | 22.8 | 28.8 | 8.06 ± 0.73 |
| mattcl-py | input-pting | 154.3 ± 2.0 | 151.9 | 160.7 | 51.69 ± 4.28 |
| mattcl-py | input-lanjian | 169.5 ± 2.6 | 165.5 | 174.1 | 56.78 ± 4.72 |
| pting | input-pting | 174.9 ± 2.8 | 168.3 | 179.6 | 58.60 ± 4.88 |
| pting | input-lanjian | 189.7 ± 3.2 | 184.5 | 196.5 | 63.54 ± 5.30 |
| mattcl-py | input-kcen | 196.3 ± 2.5 | 192.9 | 202.5 | 65.75 ± 5.44 |
| mattcl-py | input-mattcl | 202.5 ± 2.1 | 199.7 | 206.8 | 67.82 ± 5.59 |
| pting | input-kcen | 223.6 ± 3.6 | 218.2 | 230.8 | 74.89 ± 6.24 |
| pting | input-mattcl | 237.2 ± 2.8 | 231.7 | 241.8 | 79.45 ± 6.56 |
| kcen | input-pting | 602.6 ± 4.4 | 598.9 | 607.7 | 201.88 ± 16.57 |
| kcen | input-lanjian | 660.8 ± 8.1 | 649.2 | 667.7 | 221.37 ± 18.30 |
| kcen | input-kcen | 775.3 ± 1.3 | 774.2 | 776.7 | 259.72 ± 21.23 |
| kcen | input-mattcl | 852.5 ± 16.3 | 839.9 | 870.9 | 285.56 ± 23.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|