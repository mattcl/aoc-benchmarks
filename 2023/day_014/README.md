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
| mattcl | input-lanjian | 3.2 ± 0.4 | 2.6 | 5.9 | 1.00 |
| mattcl | input-pting | 3.2 ± 0.4 | 2.4 | 5.4 | 1.00 ± 0.16 |
| mattcl | input-kcen | 3.6 ± 0.4 | 3.0 | 5.3 | 1.11 ± 0.18 |
| mattcl | input-mattcl | 4.1 ± 0.5 | 3.2 | 7.8 | 1.27 ± 0.22 |
| lanjian | input-pting | 18.6 ± 0.9 | 17.3 | 22.1 | 5.79 ± 0.73 |
| lanjian | input-lanjian | 19.5 ± 0.9 | 18.4 | 23.0 | 6.08 ± 0.76 |
| lanjian | input-kcen | 21.8 ± 0.7 | 21.0 | 25.2 | 6.79 ± 0.82 |
| lanjian | input-mattcl | 23.9 ± 0.9 | 22.6 | 27.1 | 7.43 ± 0.91 |
| mattcl-py | input-pting | 155.4 ± 2.0 | 151.8 | 159.5 | 48.35 ± 5.66 |
| mattcl-py | input-lanjian | 169.9 ± 3.0 | 166.5 | 178.6 | 52.84 ± 6.21 |
| pting | input-pting | 177.0 ± 2.9 | 172.4 | 183.7 | 55.06 ± 6.47 |
| pting | input-lanjian | 193.5 ± 3.4 | 187.7 | 198.2 | 60.19 ± 7.08 |
| mattcl-py | input-kcen | 195.4 ± 2.8 | 190.3 | 200.0 | 60.79 ± 7.12 |
| mattcl-py | input-mattcl | 205.4 ± 4.5 | 201.4 | 219.9 | 63.91 ± 7.56 |
| pting | input-kcen | 223.1 ± 5.0 | 217.0 | 236.1 | 69.41 ± 8.22 |
| pting | input-mattcl | 240.6 ± 3.6 | 236.1 | 246.7 | 74.85 ± 8.77 |
| kcen | input-pting | 574.0 ± 9.4 | 565.1 | 589.9 | 178.57 ± 20.97 |
| kcen | input-lanjian | 636.6 ± 12.0 | 626.8 | 654.0 | 198.05 ± 23.33 |
| kcen | input-kcen | 726.4 ± 9.0 | 714.2 | 733.9 | 225.98 ± 26.42 |
| kcen | input-mattcl | 802.7 ± 12.5 | 793.7 | 817.0 | 249.70 ± 29.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|