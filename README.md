![image](https://github.com/patternizer/SST_L3U-L4/blob/master/AVHRRMTA_G_20101010.png)

# SST_L3U-L4

ESA SST CCI work forward modeled comparison between L3U and L4 SST variation with latitude.

## Contents

* `sst_lat_l3u_l4.py` - main script to be run with Python 3.6
* `run_sst_lat_l3u_l4.sh` - shell script
* `PLOTS/` - analysis figures

The first step is to clone the latest SST_L3U-L4 code and step into the check out directory: 

    $ git clone https://github.com/patternizer/SST_L3U-L4.git
    $ cd SST_L3U-L4
    
### Using Standard Python 

The code should run with the [standard CPython](https://www.python.org/downloads/) installation and was tested in a conda virtual environment running a 64-bit version of Python 3.6+.

SST_L3U-L4 can be run from sources directly, once the following module requirements are resolved:

* `numpy`
* `xarray`
* `matplotlib`
* `seaborn`

Run with:

    $ ./run_sst_lat_l3u_l4 
	
## License

The code is distributed under terms and conditions of the [MIT license](https://opensource.org/licenses/MIT).

## Contact information

* [Michael Taylor](https://patternizer.github.io/