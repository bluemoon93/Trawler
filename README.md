A manga crawler from MangaReader.

To build

    mkdir build
    cd build
    cmake ..
    make

And run with something like

    ./Trawler https://www.mangareader.net/soul-eater 


Or use options

    ./Trawler https://www.mangareader.net/soul-eater --no-compress --start 1 --end 100 --save /tmp

