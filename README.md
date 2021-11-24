## About
A Python 3 based command line tool for determining a docker container associated processes gpu utilization by joining information across 'nvidia-smi *' and 'docker *' commands.

## Usage

```
$ sudo su
$ cd /root
$ git clone https://github.com/raiso777/nvidia-docker-stats.git
$ ln /root/nvidia-docker-stats/nvidiadockerstats/nvidiadockerstats.py /bin/dgpustat
$ dgpustat
```

### Example output
```
Container   	Names             	pid    	gpu_uuid	used_memory 	used_gpu
188392f13203	jupyter-raiso
                                        1212   	0       	 1703 MiB   	 0 %
4f1d564b1d85	jupyter-rkaiii8813
                                        24291  	0       	 1661 MiB   	 0 %
```

## License
GPL 3
