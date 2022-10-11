# I2C-API [![Build Status](https://app.travis-ci.com/Galjente/I2C-API.svg?branch=main)](https://app.travis-ci.com/Galjente/I2C-API)
This is simple I2C api interfaces with basic functionality. This API was made for usage in Raspberry PI.

## Technologies
* Java
* Maven

## Built With
* [Maven](https://maven.apache.org/) - Dependency Management

## API
* `byte read() throws IOException` - Byte received from the device
* `byte readRegister(byte register) throws IOException` - Register byte value received from the device
* `short readRegister16(byte register) throws IOException` - Register short value received from the device
* `void write(byte value) throws IOException` - Byte sent to the device
* `void writeRegister(byte register, byte value) throws IOException` - Regiseter byte value sent to the device
* `void writeRegister16(byte register, short value) throws IOException` - Register short value sent to the device

## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/Galjente/I2C-API/tags). 

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Authors
* **Arturs Cvetkovs** - *Initial work* - [Galjente](https://github.com/Galjente)
