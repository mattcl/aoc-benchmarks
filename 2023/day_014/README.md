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
| mattcl | input-pting | 3.0 ± 0.2 | 2.2 | 4.8 | 1.00 |
| mattcl | input-lanjian | 3.1 ± 0.3 | 2.2 | 4.8 | 1.02 ± 0.13 |
| mattcl | input-kcen | 3.4 ± 0.5 | 2.6 | 6.8 | 1.12 ± 0.20 |
| mattcl | input-mattcl | 3.8 ± 0.4 | 3.0 | 6.0 | 1.25 ± 0.16 |
| lanjian | input-pting | 18.0 ± 0.6 | 17.0 | 20.5 | 5.99 ± 0.52 |
| lanjian | input-lanjian | 18.9 ± 0.7 | 18.1 | 22.3 | 6.31 ± 0.54 |
| lanjian | input-kcen | 21.5 ± 0.9 | 20.5 | 25.3 | 7.16 ± 0.64 |
| lanjian | input-mattcl | 23.4 ± 0.7 | 22.3 | 26.0 | 7.80 ± 0.66 |
| mattcl-py | input-pting | 155.5 ± 1.6 | 152.3 | 159.0 | 51.76 ± 4.12 |
| mattcl-py | input-lanjian | 170.2 ± 2.9 | 166.5 | 177.0 | 56.64 ± 4.58 |
| pting | input-pting | 175.5 ± 3.4 | 168.7 | 183.6 | 58.41 ± 4.75 |
| pting | input-lanjian | 192.1 ± 3.3 | 186.6 | 198.1 | 63.93 ± 5.16 |
| mattcl-py | input-kcen | 196.0 ± 1.7 | 193.1 | 198.7 | 65.26 ± 5.18 |
| mattcl-py | input-mattcl | 204.3 ± 2.2 | 201.2 | 210.1 | 68.01 ± 5.42 |
| pting | input-kcen | 230.6 ± 29.3 | 218.2 | 327.6 | 76.77 ± 11.47 |
| pting | input-mattcl | 240.3 ± 3.2 | 235.9 | 245.4 | 79.99 ± 6.40 |
| kcen | input-pting | 567.5 ± 4.9 | 559.7 | 572.1 | 188.92 ± 15.00 |
| kcen | input-lanjian | 630.9 ± 7.9 | 619.7 | 637.9 | 210.00 ± 16.78 |
| kcen | input-kcen | 733.8 ± 5.8 | 728.0 | 741.4 | 244.25 ± 19.37 |
| kcen | input-mattcl | 809.2 ± 22.0 | 792.9 | 834.2 | 269.35 ± 22.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|