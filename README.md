source ./bin/activate

jupyter notebook
import pyspark
import os
del os.environ['PYSPARK_SUBMIT_ARGS']


