# proforensicsllc.com
Site for Professional Forensics LLC

------------------------------------------------

Old stuff

## Details
* [github](https://github.com/proforensicsllc/proforensicsllc.github.io)
* [github pages web site](https://proforensicsllc.github.io/)

domain owner: 

## TODO:
enforce https setting in github settings

## testing locally

    cd proforensicsllc/proforensicsllc.github.io
    docker run --rm --label=jekyll --volume=$(pwd):/srv/jekyll -it -p 4000:4000 jekyll/jekyll
    open http://localhost:4000
