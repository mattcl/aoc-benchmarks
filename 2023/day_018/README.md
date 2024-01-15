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
| mattcl | input-lanjian | 837.4 ± 189.1 | 98.4 | 1081.8 | 1.00 |
| lanjian | input-pting | 849.3 ± 183.3 | 134.8 | 1471.8 | 1.01 ± 0.32 |
| mattcl | input-mattcl | 851.7 ± 189.2 | 148.9 | 1123.3 | 1.02 ± 0.32 |
| mattcl | input-kcen | 853.0 ± 166.2 | 164.7 | 1056.9 | 1.02 ± 0.30 |
| mattcl | input-pting | 856.9 ± 164.4 | 223.1 | 1067.6 | 1.02 ± 0.30 |
| lanjian | input-kcen | 865.2 ± 169.0 | 182.7 | 1076.4 | 1.03 ± 0.31 |
| lanjian | input-mattcl | 881.1 ± 146.4 | 189.6 | 1105.9 | 1.05 ± 0.29 |
| lanjian | input-lanjian | 895.5 ± 162.2 | 303.1 | 1532.6 | 1.07 ± 0.31 |
| mattcl-py | input-pting | 14219.9 ± 603.5 | 13385.1 | 17787.4 | 16.98 ± 3.90 |
| mattcl-py | input-lanjian | 14220.6 ± 484.8 | 13372.2 | 16614.0 | 16.98 ± 3.88 |
| pting | input-pting | 14499.2 ± 683.6 | 13621.0 | 18129.3 | 17.31 ± 3.99 |
| pting | input-lanjian | 14548.2 ± 632.1 | 13605.9 | 17628.8 | 17.37 ± 3.99 |
| mattcl-py | input-kcen | 14609.3 ± 598.7 | 13651.0 | 17898.8 | 17.45 ± 4.00 |
| mattcl-py | input-mattcl | 14745.4 ± 614.3 | 13761.4 | 17713.7 | 17.61 ± 4.04 |
| pting | input-mattcl | 14922.4 ± 611.5 | 13896.1 | 18394.0 | 17.82 ± 4.09 |
| pting | input-kcen | 14938.6 ± 601.3 | 13954.3 | 18296.7 | 17.84 ± 4.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|