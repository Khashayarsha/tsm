# tsm
run program by running the shell program run_assignment.sh

single call for the code can be done in the following way providing arguments

python assignment1.py -p 'data/Nile.dat' -c 0 -e 'no' -m '[[21, 40], [61, 80]]' -f '30' -s '1871'

-c (column index where the data is located we want to use)
-e (estimate the parameters yes/no)
-m (remove data in the dataset from this particular ranges)
-f (forecast this number of steps)
-s (the startindex of the data)


Commands for the cmd

python assignment1.py -p 'data/Nile.dat' -c 0 -e 'no' -s '1871'
python assignment1.py -p 'data/Nile.dat' -c 0 -e 'yes' -s '1871'
python assignment1.py -p 'data/Nile.dat' -c 0 -e 'no' -m '[[21, 40], [61, 80]]' -s '1871'
python assignment1.py -p 'data/Nile.dat' -c 0 -e 'no' -f '30' -s '1871'
python assignment1.py -p 'data/Nile.dat' -c 0 -e 'no' -m '[[21, 40], [61, 80]]' -f '30' -s '1871'



python assignment1.py -p 'data/netherlands-gdp-growth-rate.csv' -c 1 -e 'yes' -s '1961'
python -i assignment1.py -p 'data/netherlands-gdp-growth-rate.csv' -c 1 -e 'yes' -m '[[10, 20]]' -s '1961'
python -i assignment1.py -p 'data/netherlands-gdp-growth-rate.csv' -c 1 -e 'yes' -f '30' -s '1961'