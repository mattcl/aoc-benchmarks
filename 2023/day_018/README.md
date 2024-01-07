# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-pting | 811.4 ± 175.0 | 114.4 | 1063.3 | 1.00 |
| lanjian | input-kcen | 853.9 ± 138.6 | 85.7 | 1057.8 | 1.05 ± 0.28 |
| lanjian | input-lanjian | 855.6 ± 154.1 | 302.2 | 1458.1 | 1.05 ± 0.30 |
| lanjian | input-mattcl | 856.3 ± 150.2 | 155.9 | 1055.8 | 1.06 ± 0.29 |
| mattcl | input-pting | 871.5 ± 155.2 | 123.8 | 1126.6 | 1.07 ± 0.30 |
| mattcl | input-lanjian | 872.7 ± 176.0 | 95.0 | 1357.2 | 1.08 ± 0.32 |
| mattcl | input-kcen | 893.9 ± 147.8 | 338.4 | 1133.4 | 1.10 ± 0.30 |
| mattcl | input-mattcl | 894.0 ± 185.3 | 151.8 | 1475.5 | 1.10 ± 0.33 |
| mattcl-py | input-pting | 14309.8 ± 493.3 | 13523.8 | 17200.4 | 17.64 ± 3.85 |
| pting | input-pting | 14585.2 ± 506.0 | 13605.6 | 17921.2 | 17.98 ± 3.93 |
| mattcl-py | input-lanjian | 14627.5 ± 2876.3 | 13384.1 | 54431.9 | 18.03 ± 5.26 |
| pting | input-lanjian | 14644.8 ± 700.2 | 13644.4 | 18177.1 | 18.05 ± 3.99 |
| mattcl-py | input-kcen | 14717.5 ± 495.3 | 13885.4 | 17630.7 | 18.14 ± 3.96 |
| pting | input-kcen | 15106.2 ± 687.6 | 13977.1 | 18083.9 | 18.62 ± 4.10 |
| pting | input-mattcl | 15134.9 ± 723.1 | 13992.0 | 18408.6 | 18.65 ± 4.12 |
| mattcl-py | input-mattcl | 15155.3 ± 2641.0 | 14064.8 | 47867.2 | 18.68 ± 5.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|