system ubuntu 24.04
install gdal manually: sudo apt install libgdal-dev
install tkinter: sudo apt-get install python3-tk
uv pip install -e external/seacharts
uv pip install -e .

To use seacharts in the simulator, you should download .gdb files from https://kartkatalog.geonorge.no in UTM 32 or 33 (see https://github.com/trymte/seacharts for instructions), and put into the data/external folder in the seacharts package directory. Otherwise, the module will not find any ENC data to use.
!!! Rename maps