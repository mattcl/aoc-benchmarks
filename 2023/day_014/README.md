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
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.3 | 5.7 | 1.00 |
| mattcl | input-pting | 3.1 ± 0.2 | 2.3 | 5.0 | 1.00 ± 0.12 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.7 | 6.4 | 1.11 ± 0.19 |
| mattcl | input-mattcl | 3.9 ± 0.5 | 3.1 | 6.8 | 1.26 ± 0.19 |
| lanjian | input-pting | 18.2 ± 0.9 | 17.2 | 22.2 | 5.90 ± 0.59 |
| lanjian | input-lanjian | 19.0 ± 0.7 | 18.2 | 21.8 | 6.17 ± 0.58 |
| lanjian | input-kcen | 21.4 ± 0.7 | 20.4 | 24.7 | 6.95 ± 0.64 |
| lanjian | input-mattcl | 23.5 ± 0.6 | 22.5 | 27.1 | 7.63 ± 0.69 |
| mattcl-py | input-pting | 155.1 ± 2.4 | 152.9 | 162.0 | 50.30 ± 4.42 |
| mattcl-py | input-lanjian | 169.5 ± 2.0 | 166.4 | 174.8 | 54.98 ± 4.80 |
| pting | input-pting | 174.9 ± 2.1 | 172.1 | 178.7 | 56.74 ± 4.95 |
| pting | input-lanjian | 191.9 ± 3.6 | 186.4 | 199.2 | 62.24 ± 5.50 |
| mattcl-py | input-kcen | 197.0 ± 3.9 | 193.7 | 207.0 | 63.90 ± 5.67 |
| mattcl-py | input-mattcl | 208.0 ± 9.2 | 201.4 | 237.9 | 67.47 ± 6.55 |
| pting | input-kcen | 224.7 ± 3.3 | 220.9 | 229.8 | 72.87 ± 6.39 |
| pting | input-mattcl | 235.8 ± 3.8 | 228.0 | 241.2 | 76.47 ± 6.72 |
| kcen | input-pting | 570.1 ± 4.6 | 565.7 | 576.8 | 184.92 ± 16.04 |
| kcen | input-lanjian | 628.1 ± 9.2 | 618.2 | 640.2 | 203.72 ± 17.85 |
| kcen | input-kcen | 735.2 ± 7.0 | 726.3 | 742.0 | 238.47 ± 20.72 |
| kcen | input-mattcl | 807.3 ± 7.1 | 802.6 | 815.4 | 261.85 ± 22.73 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|