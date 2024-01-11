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
| lanjian | input-lanjian | 977.5 ± 155.0 | 479.0 | 1588.0 | 1.00 |
| lanjian | input-pting | 984.0 ± 165.2 | 277.8 | 1615.8 | 1.01 ± 0.23 |
| lanjian | input-kcen | 985.7 ± 161.2 | 244.4 | 1184.4 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 1006.6 ± 182.0 | 210.0 | 1530.1 | 1.03 ± 0.25 |
| mattcl | input-mattcl | 1010.9 ± 165.6 | 279.6 | 1230.0 | 1.03 ± 0.24 |
| lanjian | input-mattcl | 1012.7 ± 127.4 | 285.5 | 1173.4 | 1.04 ± 0.21 |
| mattcl | input-pting | 1027.4 ± 180.9 | 291.3 | 1715.2 | 1.05 ± 0.25 |
| mattcl | input-kcen | 1055.4 ± 165.3 | 521.5 | 1503.2 | 1.08 ± 0.24 |
| mattcl-py | input-pting | 14678.9 ± 616.3 | 13522.8 | 17501.4 | 15.02 ± 2.46 |
| mattcl-py | input-lanjian | 14755.1 ± 599.5 | 13718.8 | 17845.4 | 15.09 ± 2.47 |
| pting | input-pting | 14921.3 ± 748.0 | 13569.3 | 18138.0 | 15.26 ± 2.54 |
| mattcl-py | input-mattcl | 14999.4 ± 443.1 | 13715.6 | 17424.6 | 15.34 ± 2.48 |
| pting | input-lanjian | 15003.1 ± 542.7 | 13945.4 | 17853.2 | 15.35 ± 2.50 |
| mattcl-py | input-kcen | 15079.3 ± 658.8 | 13955.2 | 18528.7 | 15.43 ± 2.54 |
| pting | input-kcen | 15226.4 ± 494.5 | 14084.6 | 17864.1 | 15.58 ± 2.52 |
| pting | input-mattcl | 15340.6 ± 683.9 | 14239.0 | 18475.5 | 15.69 ± 2.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|