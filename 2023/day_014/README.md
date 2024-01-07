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
| mattcl | input-lanjian | 3.1 ± 0.2 | 2.3 | 3.4 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.4 | 2.2 | 6.0 | 1.00 ± 0.14 |
| mattcl | input-kcen | 3.3 ± 0.4 | 2.4 | 5.5 | 1.09 ± 0.14 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.0 | 7.5 | 1.27 ± 0.19 |
| lanjian | input-pting | 18.2 ± 0.8 | 17.4 | 21.6 | 5.94 ± 0.44 |
| lanjian | input-lanjian | 19.1 ± 0.8 | 18.2 | 22.3 | 6.23 ± 0.47 |
| lanjian | input-kcen | 21.5 ± 0.8 | 20.6 | 24.6 | 7.02 ± 0.50 |
| lanjian | input-mattcl | 23.6 ± 2.2 | 22.4 | 45.9 | 7.73 ± 0.85 |
| mattcl-py | input-pting | 154.5 ± 2.7 | 151.7 | 164.6 | 50.52 ± 3.16 |
| mattcl-py | input-lanjian | 170.0 ± 4.5 | 165.4 | 179.7 | 55.58 ± 3.64 |
| pting | input-pting | 173.1 ± 1.9 | 170.4 | 176.5 | 56.60 ± 3.45 |
| pting | input-lanjian | 192.5 ± 7.9 | 184.8 | 216.1 | 62.93 ± 4.58 |
| mattcl-py | input-kcen | 195.8 ± 4.6 | 190.2 | 208.1 | 64.02 ± 4.12 |
| mattcl-py | input-mattcl | 209.3 ± 12.4 | 201.6 | 245.5 | 68.43 ± 5.77 |
| pting | input-kcen | 223.2 ± 8.1 | 214.6 | 247.2 | 72.97 ± 5.12 |
| pting | input-mattcl | 235.8 ± 4.4 | 229.2 | 241.0 | 77.10 ± 4.84 |
| kcen | input-pting | 563.9 ± 7.3 | 557.4 | 576.1 | 184.36 ± 11.31 |
| kcen | input-lanjian | 622.9 ± 5.8 | 617.7 | 631.2 | 203.64 ± 12.36 |
| kcen | input-kcen | 734.5 ± 6.9 | 727.7 | 743.4 | 240.12 ± 14.57 |
| kcen | input-mattcl | 792.3 ± 9.1 | 785.6 | 802.7 | 259.03 ± 15.81 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|