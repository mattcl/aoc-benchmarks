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
| lanjian | input-mattcl | 852.0 ± 197.3 | 200.4 | 1169.3 | 1.00 |
| lanjian | input-kcen | 884.1 ± 172.2 | 156.0 | 1125.1 | 1.04 ± 0.31 |
| lanjian | input-pting | 890.0 ± 168.5 | 161.6 | 1284.2 | 1.04 ± 0.31 |
| lanjian | input-lanjian | 891.9 ± 153.6 | 176.8 | 1092.6 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 898.7 ± 186.9 | 148.7 | 1371.2 | 1.05 ± 0.33 |
| mattcl | input-pting | 906.7 ± 158.3 | 189.0 | 1147.2 | 1.06 ± 0.31 |
| mattcl | input-lanjian | 922.3 ± 154.2 | 182.1 | 1111.7 | 1.08 ± 0.31 |
| mattcl | input-kcen | 946.5 ± 161.7 | 213.7 | 1197.5 | 1.11 ± 0.32 |
| mattcl-py | input-pting | 14324.3 ± 748.7 | 13338.9 | 17935.1 | 16.81 ± 3.99 |
| mattcl-py | input-lanjian | 14387.0 ± 596.4 | 13519.2 | 17419.5 | 16.89 ± 3.97 |
| pting | input-pting | 14535.6 ± 649.3 | 13647.5 | 18212.7 | 17.06 ± 4.02 |
| pting | input-lanjian | 14614.8 ± 656.3 | 13476.5 | 17713.8 | 17.15 ± 4.05 |
| mattcl-py | input-mattcl | 14704.4 ± 634.4 | 13695.1 | 17525.0 | 17.26 ± 4.06 |
| mattcl-py | input-kcen | 14710.2 ± 610.3 | 13694.5 | 17975.5 | 17.26 ± 4.06 |
| pting | input-mattcl | 14976.1 ± 432.9 | 13804.8 | 17431.8 | 17.58 ± 4.10 |
| pting | input-kcen | 15015.4 ± 664.7 | 13940.2 | 17928.2 | 17.62 ± 4.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>52035</pre>|<pre>60612092439765</pre>|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|