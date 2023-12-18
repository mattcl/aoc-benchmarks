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
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.2 | 5.9 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.3 | 2.2 | 5.5 | 1.01 ± 0.15 |
| mattcl | input-kcen | 3.5 ± 0.3 | 2.8 | 5.4 | 1.12 ± 0.16 |
| mattcl | input-mattcl | 4.0 ± 0.5 | 3.3 | 7.8 | 1.28 ± 0.22 |
| lanjian | input-pting | 18.2 ± 0.8 | 17.4 | 21.2 | 5.86 ± 0.68 |
| lanjian | input-lanjian | 19.1 ± 0.7 | 18.2 | 22.3 | 6.15 ± 0.71 |
| lanjian | input-kcen | 21.6 ± 0.9 | 20.6 | 24.6 | 6.94 ± 0.80 |
| lanjian | input-mattcl | 23.5 ± 0.7 | 22.7 | 27.1 | 7.58 ± 0.86 |
| mattcl-py | input-pting | 156.6 ± 2.7 | 153.3 | 165.2 | 50.39 ± 5.53 |
| mattcl-py | input-lanjian | 169.6 ± 1.8 | 166.3 | 173.8 | 54.58 ± 5.95 |
| pting | input-pting | 176.1 ± 2.2 | 172.8 | 181.6 | 56.68 ± 6.19 |
| pting | input-lanjian | 193.1 ± 2.9 | 187.8 | 197.1 | 62.15 ± 6.80 |
| mattcl-py | input-kcen | 198.0 ± 2.7 | 193.8 | 203.0 | 63.73 ± 6.97 |
| mattcl-py | input-mattcl | 204.9 ± 2.9 | 201.5 | 213.3 | 65.95 ± 7.21 |
| pting | input-kcen | 224.6 ± 3.6 | 218.2 | 230.7 | 72.28 ± 7.92 |
| pting | input-mattcl | 238.8 ± 4.5 | 232.9 | 246.9 | 76.84 ± 8.46 |
| kcen | input-pting | 572.2 ± 7.2 | 561.7 | 579.1 | 184.14 ± 20.11 |
| kcen | input-lanjian | 626.9 ± 4.3 | 622.2 | 631.3 | 201.74 ± 21.92 |
| kcen | input-kcen | 737.9 ± 10.4 | 725.9 | 746.7 | 237.48 ± 25.97 |
| kcen | input-mattcl | 814.8 ± 4.2 | 811.1 | 819.3 | 262.21 ± 28.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|