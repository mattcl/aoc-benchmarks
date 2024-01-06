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
| lanjian | input-mattcl | 764.4 ± 276.0 | 153.8 | 1105.6 | 1.00 |
| lanjian | input-lanjian | 912.8 ± 177.4 | 145.6 | 1535.2 | 1.19 ± 0.49 |
| lanjian | input-kcen | 934.3 ± 162.0 | 168.6 | 1338.8 | 1.22 ± 0.49 |
| lanjian | input-pting | 935.4 ± 144.6 | 435.0 | 1691.8 | 1.22 ± 0.48 |
| mattcl | input-kcen | 965.5 ± 156.9 | 230.9 | 1143.3 | 1.26 ± 0.50 |
| mattcl | input-mattcl | 971.7 ± 165.0 | 210.1 | 1588.1 | 1.27 ± 0.51 |
| mattcl | input-pting | 971.7 ± 149.9 | 224.4 | 1147.6 | 1.27 ± 0.50 |
| mattcl | input-lanjian | 1000.0 ± 116.9 | 245.2 | 1118.8 | 1.31 ± 0.50 |
| mattcl-py | input-pting | 14616.8 ± 505.7 | 13634.5 | 17676.2 | 19.12 ± 6.94 |
| mattcl-py | input-lanjian | 14642.4 ± 566.9 | 13366.0 | 17806.0 | 19.15 ± 6.96 |
| pting | input-pting | 14805.7 ± 514.5 | 13770.6 | 17420.2 | 19.37 ± 7.03 |
| pting | input-lanjian | 14982.0 ± 616.5 | 13839.8 | 19126.3 | 19.60 ± 7.12 |
| mattcl-py | input-mattcl | 15024.6 ± 602.2 | 13928.7 | 17726.8 | 19.65 ± 7.14 |
| mattcl-py | input-kcen | 15028.5 ± 526.2 | 13985.5 | 17571.9 | 19.66 ± 7.13 |
| pting | input-kcen | 15184.7 ± 592.1 | 14033.3 | 18351.1 | 19.86 ± 7.21 |
| pting | input-mattcl | 15214.6 ± 591.7 | 14367.2 | 18437.9 | 19.90 ± 7.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|