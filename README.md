# cyclonedds-go
A Go binding for [Eclipse Cyclone DDS][1].

# Getting Started

<!----><a name="installing-from-source"></a>
## Installing from source

When installing from source you can make use of the full list of features offered by [Cyclone DDS][1]. First install [Cyclone DDS][1] as normal.

A full example installation of the quickest way to get started via git is shown below:

```bash
$ git clone https://github.com/eclipse-cyclonedds/cyclonedds
$ cd cyclonedds && mkdir build && cd build
$ cmake -DCMAKE_INSTALL_PREFIX=/usr/local/ ..
$ cmake --build . --target install
```

<!----><a name="building-the-go-binding"></a>
## Building the Go binding

```bash
$ git clone https://github.com/leeroyvg/cyclonedds-go
$ go run main.go
```


[1]: https://github.com/eclipse-cyclonedds/cyclonedds/#eclipse-cyclone-dds
