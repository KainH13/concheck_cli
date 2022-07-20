# concheck CLI
`concheck` is a Python CLI that checks url connectivity by sending a HEAD request to the url.

## Using `concheck`
`concheck` is a CLI and run from the command line.

An example run of `concheck` looks like:
```
python -m concheck -u python.org pypi.org
```

The flags `concheck` supports are:  

`-u` `--urls` -- accepts one or more urls seperated  

`-f` `--input-file` -- accepts one file of urls seperated by new lines (`\n`)  

`-a` `--asynchronous` -- runs checks asynchronously, can lead to better performance for a long list of urls  


## Setup
`concheck` is set up as a Python module, so the entire repo will need to be cloned to the machine you want to use it on.

Once the repo is on your machine you need to install the required packages from `requirements.txt` with the following:
```
pip install -r requirements.txt
```
Now you're ready to use concheck!