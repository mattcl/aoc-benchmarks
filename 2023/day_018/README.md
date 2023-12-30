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
| lanjian | input-mattcl | 839.3 ± 171.1 | 150.4 | 1015.1 | 1.00 |
| lanjian | input-lanjian | 851.3 ± 188.2 | 134.8 | 1410.0 | 1.01 ± 0.31 |
| lanjian | input-kcen | 854.4 ± 147.6 | 136.2 | 1045.5 | 1.02 ± 0.27 |
| lanjian | input-pting | 872.8 ± 127.7 | 429.3 | 1328.1 | 1.04 ± 0.26 |
| mattcl | input-lanjian | 886.3 ± 165.4 | 211.4 | 1444.3 | 1.06 ± 0.29 |
| mattcl | input-kcen | 890.7 ± 197.0 | 150.7 | 1614.7 | 1.06 ± 0.32 |
| mattcl | input-mattcl | 907.5 ± 157.4 | 189.1 | 1101.7 | 1.08 ± 0.29 |
| mattcl | input-pting | 920.1 ± 144.7 | 362.5 | 1617.4 | 1.10 ± 0.28 |
| mattcl-py | input-pting | 14547.7 ± 606.6 | 13222.2 | 17906.4 | 17.33 ± 3.61 |
| mattcl-py | input-lanjian | 14576.8 ± 583.9 | 13330.0 | 17761.1 | 17.37 ± 3.61 |
| pting | input-pting | 14757.6 ± 507.5 | 13425.0 | 17628.6 | 17.58 ± 3.64 |
| pting | input-lanjian | 14870.0 ± 569.6 | 13823.8 | 17884.6 | 17.72 ± 3.68 |
| mattcl-py | input-kcen | 14934.7 ± 541.8 | 13749.2 | 17281.8 | 17.79 ± 3.69 |
| pting | input-kcen | 15089.5 ± 472.1 | 13854.2 | 17843.2 | 17.98 ± 3.71 |
| mattcl-py | input-mattcl | 15110.2 ± 784.3 | 13880.4 | 18310.2 | 18.00 ± 3.79 |
| pting | input-mattcl | 15183.6 ± 596.9 | 13943.7 | 17853.5 | 18.09 ± 3.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|