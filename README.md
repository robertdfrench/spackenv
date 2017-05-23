# spackenv
Spack Environment Manager

## Installing
```bash
curl -o /usr/local/bin/spackenv https://raw.githubusercontent.com/robertdfrench/spackenv/master/spackenv; chmod +x /usr/local/bin/spackenv
```

## Usage
```
spackenv .venv requirements.txt
```

##### Where
* `.venv` is a folder that will contain your dependencies
* `requirements.txt` has a Spack spec on each line

### Specifying Dependencies
Here is an example requirements.txt that installs zlib and netcdf with OpenMPI support:

```
zlib
netcdf+mpi
```
